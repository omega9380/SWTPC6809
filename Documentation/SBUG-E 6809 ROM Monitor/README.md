# SBUG-E 6809 ROM Monitor

The 6809 SBUG monitor ROM is provided to enable the computer to communicate with a terminal for the purpose of various programming and debugging functions. It has been designed to work in a SWTPC MP-09 processor board. SBUG requires an MP-S interface installed in I/0 port 1, at least 4K of RAM memory installed at any address at or below address D000 (52K) and an MP-B or MP-B2 motherboard patched to address I/0 devices at 56K (E000 hex). While SBUG provides some functional compatibility with 6800 DISKBUG, SWTBUG, and MIKBUG monitors; in general, programs utilizing the ROM functions of the older monitors will need to be changed.

Copyright 2000-2012, Michael Holley