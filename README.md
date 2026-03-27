![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red) ![Bugs](https://img.shields.io/badge/bugs-0%20open-brightgreen) ![Build](https://img.shields.io/badge/Build-passing-brightgreen?logo=github) [![Members](https://img.shields.io/discord/750034898680807434?label=members&logo=discord&color=7289da)](https://discord.gg/CHZea8zvBG)

# H2 Sireli P4

Custom single-player mod for H1-Mod / Call of Duty: Modern Warfare Remastered.

## Installation Guide

1. Download the repository as a ZIP file or clone it normally.
2. Extract the files if you downloaded a ZIP archive.
3. Open your game folder that contains `h1-mod.exe`.
4. Open the `mods` folder inside the game directory. If it does not exist, create it manually.
5. Copy the full folder `h2_sireli_p3` into the `mods` folder.
6. Make sure the final layout looks like this:

```text
Call of Duty Modern Warfare Remastered\
  h1-mod.exe
  mods\
    h2_sireli_p3\
      info.json
      mod.ff
      mod.pak
      maps\
      save\
```

7. Move `sireli_p3.bat` next to `h1-mod.exe` in the main game folder.
8. Launch the mod with `sireli_p3.bat` or run:

```bat
h1-mod.exe -singleplayer -mod "mods\h2_sireli_p3"
```

## Notes

- `mod.ff` and `mod.pak` are tracked with Git LFS.
- If you downloaded a source ZIP and either file is only a tiny text pointer, get the real binary files from a proper Git LFS checkout or your release package before launching the mod.
- `sireli_p3.bat` should be placed next to `h1-mod.exe` before you run it.

## License

This project uses a custom "All Rights Reserved" license. See `LICENSE` for details.
