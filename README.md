# NFCLoader

This project is based on yves.vanhal's ACR122U NFC C# Project:
https://www.instructables.com/ACR122U-NFC-C-Project/

Emulators, cores and roms are defined via mapping.txt, which contains comma separated paths to emulators, cores and roms with the format
[ID],[Path To Emulator],[Path To Core],[Path To Rom]

```484096B8F6180,C:\RetroArch-Win64\retroarch.exe,C:\RetroArch-Win64\cores\snes9x_libretro.dll,C:\RetroArch-Win64\games\snes\romname.zip```

To register a new tag easily, launch the program and hold an unconfigured tag on the reader. The program will display the ID. Copy the ID into the text file and fill out the rest, i.e. path to the emulator, path to the core and path to the rom. Save and restart the program. Now the next time you hold the NFC tag on top of the reader, it will launch the emu with the core and rom paths.


# License
CC BY-NC-SA 4.0
https://creativecommons.org/licenses/by-nc-sa/4.0/

