# DKWDRV
Unified Single PS1DRV Replacement, compatible with mostly all PS2 models.


I take no responsibility for the program's behaviour, because I am not its author.




VERY EARLY! EXPECT BUGS

THE AUTHOR(S) ARE NOT RESPONSIBLE FOR WHAT YOU DO WITH THIS SOFTWARE



Features:

Mimic behaviour as original drivers.


Automatic switch to PAL/NTSC based on mode game sets. No more random mode patching.

Makes experience perfect with tonyhax.


Fix for homebrews gpu reset. Many PS1 homebrews were coded with a GP1 01 cmd every time. This would make them not usable in PS1DRV. Case example:

http://www.psxdev.net/forum/viewtopic.php?t=401



Option to force dither on/off. No more patches needed.

Option disable GPU color banding. PS1DRV applies to sprites rendering and drops 3bits from the color value.

http://www.psxdev.net/forum/viewtopic.php?t=1035


Universal single file for any type of PS2: PGIF/DECKARD

Properly game configs for games and regions.


Automatic LOGO check skip on DECKARD models if needed.

Automatic warning of user if the LOGO does not match for cases when logo can not be patched. Avoids user confusion on why games may not boot. Can force proceed anyway for cases where they might be a modchip.


Automatic cheats. DECKARD ONLY

Automatic analog mapping for games that do not support it, ex: Crash Bandicoot 1.   DECKARD ONLY

Custom actions depending on button combos. DECKARD ONLY

Swap X and O buttons for japanese games.   DECKARD ONLY

PS2HDMI Dongle Fix

Screen Offset Options

Ability to create custom configs and use them.

Standalone ELF can be used in PCSX2 for user who only have slim bios. And TOOLs too.

Ability to emulate PS1 region letter for any particular game or homebrew.

Proper DI and EI which waits until interrupts are properly set.

A lot more...


Future Features:
...


Use the menus to set different options before launching.



DECKARD ONLY INGAME COMBOS

L1+R1 + any DPAD - screen offsets

R1 + Triangle - Toogle Sharpening



Usage

Insert PS1 disc prior to launching software.


DECKARD VERSTR 

Patches PS1 region to other than default one. Useful for any game checking it. Libcrypt games check to run only on Europe region.



Analog Patch

Map analog to DPAD for games which do not support it.

SWAP XO

Swap X and O. Useful for Japanese games.


Cheats DECKARD ONLY

Save general config and then go to MC and inside folder with game id place "CHEATS.TXT"



Cheats format example:

#Infinite Lives "Boulders" Stage	

8009E584 6300

#Infinite Lives "Castle Machinery" Stage	

8009E88C 6300

#Infinite Lives "Cortex Power" Stage	

8009E77C 6300



Supported cheat code formats:
Refer to more details to Duckstation as the most updated emu out there.
https://github.com/stenzek/duckstation/blob/master/src/core/cheats.h

NOT RELATED OR AFFILIATED TO DUCKSTATION IN ANY WAY

CodeNop	
ConstantWrite8
ConstantWrite16
ExtConstantWrite32
ExtConstantBitSet8	
ExtConstantBitSet16	
ExtConstantBitSet32
ExtConstantBitClear8
ExtConstantBitClear16	
ExtConstantBitClear32
ExtIncrement32
ExtDecrement32
Increment16	
Decrement16
Increment8		
Decrement8
ExtCompareEqual32
ExtCompareNotEqual32	
ExtCompareLess32
ExtCompareGreater32
ExtConstantWriteIfMatch16
ExtConstantWriteIfMatchWithRestore16
CompareEqual16
CompareNotEqual16
CompareLess16
CompareGreater16
CompareEqual8
CompareNotEqual8
CompareLess8
CompareGreater8
Slide
ExtImprovedSlide
MemoryCopy
