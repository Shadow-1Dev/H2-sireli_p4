![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red) ![Build](https://img.shields.io/badge/Build-passing-brightgreen?logo=github)

# H2 Sireli P4

`H2 Sireli P4` is a custom single-player mod for H1-Mod / Call of Duty: Modern Warfare Remastered.

## What This Project Contains

- Mod asset archives in `mod.ff` and `mod.pak`
- A custom campaign loadout script in `maps\_loadout.gsc`
- A launcher batch file for starting the mod in single-player

This build focuses on campaign loadout changes, including custom mission weapon setups and early precaching for XM25-related assets.

## Installation

1. Download this repository or clone it locally.
2. Open the game directory that contains `h1-mod.exe`.
3. Create a `mods` folder if one does not already exist.
4. Copy this mod folder into `mods`.

Your final folder layout should look like this:

```text
Call of Duty Modern Warfare Remastered\
  h1-mod.exe
  mods\
    <mod folder>\
      info.json
      mod.ff
      mod.pak
      maps\
      README.md
      <launcher>.bat
```

## Launching The Mod

Place the included launcher batch file next to `h1-mod.exe` and run it, or launch manually with the matching mod folder name:

```bat
h1-mod.exe -singleplayer -mod "mods\<your_mod_folder>"
```

## Git LFS Note

`mod.ff` and `mod.pak` are stored with Git LFS.

If you downloaded a source archive and either file is only a small text pointer, fetch the real binary files with Git LFS or use a release package that already includes them.

## License

This project is distributed under the custom "All Rights Reserved" license in `LICENSE`.
