# smb3
Disassembly of Super Mario Bros 3 from Southbird, forked for personal hacking use. The extra editor stuff was removed for cleanliness.

Specifically for use with NESASM (https://github.com/camsaul/nesasm), this will reassemble into a byte-for-byte perfect clone of Super Mario Bros. 3 US (PRG1)

-------------

To assemble, simply run:

nesasm smb3.asm

Intended for use for research into the inner workings of SMB3 and highly technical ROM hacks (such as Super Mario Bros. 3Mix)

## Bypass Letter Screen

This change skips the world-ending letters from the Princess (and Bowser) and loads straight into the next world. The King's text was also changed to make sense with this.