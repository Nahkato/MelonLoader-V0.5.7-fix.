# MelonLoader-V0.5.7-fix.
This file is made to solve the issue where MelonLoader 0.5.7 can't download the required dependencies 

This is the file Il2CppAssemblyGenerator.dll which has an issue that me with the help of a really smart dev I managed to fix by changing the flollowing under:
Il2CppAssemblyGenerator.dll > MelonLoader.Il2CppAssemblyGenerator.Packages > Cpp2IL > line 23:
this.Version = "2022.1.0-pre-release.8"; to this.Version = "2022.1.0-pre-release.10"; using DNSpy

to use this, 

1. download [MelonLoader 0.5.7](https://github.com/LavaGang/MelonLoader/releases/tag/v0.5.7) or use the [latest installer](https://melonwiki.xyz/#/README?id=automated-installation)

2. select your game (probably CMS2021 lol) and hit install/upgrade/downgrade depending on if you have a different version installed or not.

3. Next go to your game's install location and go to MelonLoader > Dependencies > Il2CppAssemblyGenerator and replace Il2CppAssemblyGenerator.dll with the dll from this repo 

4. go to your where your main game files are installed and right click Car Mechanic Simulator 2021.exe (or whatever game you're playing) > go to properties > check the box that says "Run as Administrator"

    4.1. if you are using a pirated version of CMS2021 and have a Launcher.exe run that as administrator as well

DISCLAIMER: if you do not run the game (and/or launcher) as administrator MelonLoader will scream at you that it can't install Cpp2IL due to a connection error

WARNING: please note while the original file is from the MelonLoader dev team, this repo is not officially endorced by the devs of MelonLoader. While the only change is changing one number to another, it still is altered from the original and is used at your own risk.
