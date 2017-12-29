# BIG-INTEGER-ANS-FORTH
Some years ago I started to define words for arithmetics on arbitrary number strings (ascii). I terrorized people at various sites with my questions and solutions and got a lot of feedback. Then I changed from ascii strings with most significant numbers in lowmem to "cellimal" system with least significant cells in lowmem. By now, it is a rather fast and general system working in Forth style, with a stack for arithmetics and a second stack for storing data. Almost all the words are very similar to the words for other kind of calculations in Forth. Tested on:

- 32 bit SP-Forth with Vista and Windows 10
- 32 bit GForth with Vista, Windows 10 and Android
- 32 bit SwiftForth with Vista and Windows 10
- Win32Forth with Vista and Windows 10
- 64 bit GForth and GForth-fast with Windows 10
- 32 bit Gforth and GForth-fast with Linux
- 64 bit Gforth and GForth-fast with Linux
- vfxlin 4.71 (MPE VFX Forth) with Linux
- GForth Raspberry Pi 2 (900MHz quad-core ARM Cortex-A7) with Raspbian

There was a typo in the definition of barrett reduction modulo that caused rare errors for big numbers. Now fixed.
