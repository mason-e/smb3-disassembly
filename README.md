# smb3
Disassembly of Super Mario Bros 3 from Southbird, forked for personal hacking use. The extra editor stuff was removed for cleanliness.

Specifically for use with NESASM (https://github.com/camsaul/nesasm), this will reassemble into a byte-for-byte perfect clone of Super Mario Bros. 3 US (PRG1)

-------------

To assemble, simply run:

nesasm smb3.asm

Intended for use for research into the inner workings of SMB3 and highly technical ROM hacks (such as Super Mario Bros. 3Mix)

## Always Hand Trap

Changes a routine to remove a possible "safe" landing on the hand traps in World 8 - in other words, makes the hand trap levels mandatory.