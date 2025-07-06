# smb3
Disassembly of Super Mario Bros 3 from Southbird, forked for personal hacking use. The extra editor stuff was removed for cleanliness.

Specifically for use with NESASM (https://github.com/camsaul/nesasm), this will reassemble into a byte-for-byte perfect clone of Super Mario Bros. 3 US (PRG1)

-------------

To assemble, simply run:

nesasm smb3.asm

Intended for use for research into the inner workings of SMB3 and highly technical ROM hacks (such as Super Mario Bros. 3Mix)

## Branches

I made a few changes for my own hacking purposes, so I decided to leave those branches up in this repo for reference/example purposes. Although probably not likely to be useful to most, free to create patches out of them for use in adding to your own hacks. In each branch there is a description of what the change does in its version of this README. When removing a functionality from the game I went more for changing the least amount of code rather than freeing up the most amount of memory. These changes are meant to be applied to an unexpanded/minimally modified version of the ROM.