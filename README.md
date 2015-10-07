# BIG-INTEGER-ANS-FORTH
More than a year ago I started to define words for arithmetic on arbitrary numberstrings (ascii). I've terrorized people at variuos sites with my questions and solutions and got a lot of feedback. Then I changed from ascii strings with most significant numbers in lowmem to "cellimal" system with least significant cells in lowmem. By now a rather fast and general system is (almost) working in Forth style, with a stack for arithmetic and a second stack for storing data. Almost all the words are very similar to the words for other kind of calculations in Forth.

It worked (almost) fine until I submitted the b~ of ruvim on stack exchange, now with a well functioning b- the b/ algorithm doesn't work at all!  :)
