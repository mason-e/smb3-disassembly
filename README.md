# smb3
Disassembly of Super Mario Bros 3 from Southbird, forked for personal hacking use. The extra editor stuff was removed for cleanliness.

Specifically for use with NESASM (https://github.com/camsaul/nesasm), this will reassemble into a byte-for-byte perfect clone of Super Mario Bros. 3 US (PRG1)

-------------

To assemble, simply run:

nesasm smb3.asm

Intended for use for research into the inner workings of SMB3 and highly technical ROM hacks (such as Super Mario Bros. 3Mix)

## Update Letter

This change set removes the item reward from the Princess' letters at the end of each world. The item choice itself is a change that can be easily made with other editors, but it causes a visual bug. I fixed the visual bug by also removing the sprite of the rewarded item entirely. Therefore this change is probably only desirable if removing rewards from _all_ levels, not just some. 