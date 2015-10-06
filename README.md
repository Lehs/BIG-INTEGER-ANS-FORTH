# BIG-INTEGER-ANS-FORTH
More than a year ago I started to define words for arithmetic on arbitrary numberstrings (ascii). I've terrorized people at 
variuos sites with my questions and solutions and got a lot of feedback. By now a rather fast and general system is working in 
Forth style, with a stack for arithmetic and a second stack for storing data. Almost all the words are very similar to the 
words for other kind of calculations in Forth.

I have discovered an error in 'B-'. If n>63 then (2^n +1)-(2^n - 1) > 2 ... But I'm working on it.
