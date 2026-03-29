![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red) ![Build](https://img.shields.io/badge/Build-passing-brightgreen?logo=github)

# H2 Sireli P4

`H2 Sireli P4` is a custom single-player mod for H1-Mod / Call of Duty: Modern Warfare Remastered.

## What This Project Contains

- Packaged mod assets in `mod.ff` and `mod.pak`
- A custom campaign loadout script in `maps\_loadout.gsc`
- A simple launcher script in `sireli_p4.bat`

This build is focused on single-player loadout changes, including custom mission weapon setups and early precaching for XM25-related assets.

## Installation

1. Download this repository or clone it locally.
2. Open the game directory that contains `h1-mod.exe`.
3. Create a `mods` folder if one does not already exist.
4. Copy the entire `h2_sireli_p4` folder into `mods`.

Your final folder layout should look like this:

```text
Call of Duty Modern Warfare Remastered\
  h1-mod.exe
  mods\
    h2_sireli_p4\
      info.json
      mod.ff
      mod.pak
      maps\
      README.md
      sireli_p4.bat
```

## Launching The Mod

Place `sireli_p4.bat` next to `h1-mod.exe` and run it, or launch manually with:

```bat
h1-mod.exe -singleplayer -mod "mods\h2_sireli_p4"
```

## Git LFS Note

`mod.ff` and `mod.pak` are stored with Git LFS.

If you downloaded a source archive and either file is only a small text pointer, fetch the real binary files with Git LFS or use a release package that already includes them.

## License

This project is distributed under the custom "All Rights Reserved" license in `LICENSE`.
