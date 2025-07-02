# smb3
Disassembly of Super Mario Bros 3 from Southbird, forked for personal hacking use. The extra editor stuff was removed for cleanliness.

Specifically for use with NESASM (https://github.com/camsaul/nesasm), this will reassemble into a byte-for-byte perfect clone of Super Mario Bros. 3 US (PRG1)

-------------

To assemble, simply run:

nesasm smb3.asm

Intended for use for research into the inner workings of SMB3 and highly technical ROM hacks (such as Super Mario Bros. 3Mix)

## Branches

I've included branches in this repo for changes I've ended up implementing myself in my own work. Feel free to use any of these in your hack. I don't have a tool for patching directly from the changed assembly, so the way I'd suggest going about it is to compile the ASM, then determine the changes in a hex comparison or patch onto your in-progress hack.