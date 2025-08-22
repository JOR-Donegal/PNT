# Bits, Nibbles, Bytes and Words

It would be unusual for us to want to exchange single bits. We could exchange data in groups of 4 bits, this is called a _nibble_ and is very unusual. However, the first production microprocessor (4004) was a 4-bit computer.

When we began exchanging characters first, we did so with a standard called _ASCII_, the American Standard Code for Information Interchange. Work began on this in 1960 with the American Standards Association's (ASA) X3.2 subcommittee and the standards were released in 1963, revised in 1967 and 1986. ASCII was developed from early telegraphic codes, and its first commercial use was as a 7-bit teleprinter code. 7 bits gives us 2^7 or 128 possible characters.

* 26 Capital (65-90) and 26 Lower Case (97-122)
* 10 Numbers (48-57)
* 32+1 Control Characters (0-31, 127)

It may seem strange to use 7 bits, but we needed some other things like start and stop bits and our early serial chips could only cope with 10 bits. Eventually _extended ASCII_ was developed and includes definitions for 2^8 or 256 characters. The generation of microprocessors from the 8008 onward used 8 bits internally, a byte.&#x20;

Some early mainframes and mini computer used 12 bits!

As symbol lengths went above 8 bits, we used the term word. We can have 16, 32, 64 bit words.

