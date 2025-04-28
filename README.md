# Magpie LADX Autotracker

This is an autotracker for Link's Awakening DX, compatible with [Magpie](https://github.com/kbranch/Magpie).

Windows, Linux and Mac binaries are available on GitHub as releases, or from download buttons in the autotracker mini tab inside Magpie.

No setup should be required beyond enabling autotracking in Magpie - just start the autotracker and a compatible emulator.

### Linux (and Mac?)
Autotracking should work on any vaguely recent version of Linux that can also run a [compatible emulator](#emulator-compatibility). Mac support is not well tested but probably similar.

### From Source
Setup is similar to the local version of Magpie:
 - Download the source (`autotracker-source.zip` from the latest release)
 - Run [setup.sh](https://github.com/kbranch/Magpie-LADX-Autotracker/blob/main/setup.sh) (Linux/Mac) or [setup.bat](https://github.com/kbranch/Magpie-LADX-Autotracker/blob/main/setup.bat) (Windows) to set up the environment
 - Run [start.sh](https://github.com/kbranch/Magpie-LADX-Autotracker/blob/main/start.sh) (Linux/Mac) or [start.bat](https://github.com/kbranch/Magpie-LADX-Autotracker/blob/main/start.bat) (Windows) to start the autotracker

### Emulator Compatibility
Currently, [BGB](https://bgb.bircd.org/), [RetroArch](https://www.retroarch.com/) and [Bizhawk](https://tasvideos.org/Bizhawk) are supported. BGB works under Windows and on Linux via Wine (the Windows autotracker exe must also be run with Wine), while RetroArch works natively on both Windows and Linux. RetroArch requires the [Network Control Interface](https://docs.libretro.com/development/retroarch/network-control-interface/) to be turned on (Archipelago has a [good guide](https://archipelago.gg/tutorial/Links%20Awakening%20DX/setup/en#retroarch-1.10.3-or-newer)). Bizhawk requires a [LUA script](https://magpietracker.us/static/bizhawk-ladxr.zip) (taken from [Archipelago](https://github.com/ArchipelagoMW/Archipelago)).

The autotracker requires a copy of the ROM for some features to work. When it is not able to pull the ROM directly from the emulator, it will request a copy from the user in the main Magpie UI.