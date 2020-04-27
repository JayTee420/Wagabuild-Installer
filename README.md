# Wagabuild Installer for Linux

A script for compiling the Wagabuild from Smash @ Wageningen on Linux. 

Currently tested on Arch Linux, but should work across *all* distributions given the right dependencies. 

Send a message to Koopa#3701 on Discord for support.

## Dependencies needed (install these first!)
For most users (including Fedora 24+), see [this page](https://wiki.dolphin-emu.org/index.php?title=Building_Dolphin_on_Linux) for an easy to install list of dependencies; otherwise, see below.

You also need `curl`.

## Instructions: (READ FULLY BEFORE FOLLOWING)

1. Install necessary dependcies listed using guide above. Don't forget that optional deps will bring fast downloads.
2. Use install script to obtain WB
3. Move Brawl into FasterProjectPlus/bin/Games directory
4. Run the game by opening the .elf file in dolphin

## To use:

```sh
sh -c "$(curl -Ls https://github.com/Koopabro/Wagabuild-Installer/raw/master/setup)"
```

If a different version is needed (e.g. not SL default), edit the script and replace the desired variables.

Packed config structure: main folder named `Binaries/`, with  `User/`, `Sys/`, `portable.txt`, and `version-####.txt`(optional) packed inside.

## Changelog
v1.0 initial release

### Thanks to:
Odie for maintaining the Smash Wageningen Build. 

The Faster Project Plus guys, this script is shamelessly ripped of of them. You can find them [here](https://github.com/Birdthulu/FPM-Installer)

The entire FasterMelee team, without their installer as a base, this would probably not have been written.

They thank the following people so it felt appropriate to thank them here as well:

    /u/ParadigmComplex. "Seriously, I could not have finished the original script without this guy."

    /u/jojorino and Hannesmann: "always testing and helping, as well as the rest of the FM discord!"

    "Also thanks to xanax, CilanMan, /u/algebra123230, /u/folfess for incremental improvements!"

### Faster Melee on Linux:

Want to play Melee on linux?
[Check out the FasterMelee team's installer here!](https://github.com/FasterMelee/FasterMelee-installer)