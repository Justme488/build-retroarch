# Script for building/updating retroarch and select cores for Linux Mint
Tested with Linux Mint 20, but _should_ work with Ubuntu.
### I changed, and added a few things from the [Original script written by Sanaki](https://gist.github.com/Sanaki/44200de635032c21d5d9a11aba75b23b/)
( To make it more user friendly )
### Features include:
* Creates folders in /home/username/.config/retroarch
* Creates a log in _/home/username/.config_ (when you install or update - removes the old log when you update)
* Creates _Retroarch_ shortcut in menu - _Menu > Games > Retroarch_
* Creates _Update Retroarch_ shortcut in menu - _Menu > Accessories > Update Retroarch_
* Moves the script to where it belongs. You can run it from anywhere in your home directory the first time.
* Checks if /home/username/.local/bin is in your PATH. If not, it tells you restart your computer.</br>>
  ( _/home/username/.local/bin_ will be in your PATH after you reboot )
* See the cores below that it builds and updates.</br>
  ( They can be changed in line 31 of /home/username/.local/bin/update-retroarch )
### There is a [_dependency installer_](https://github.com/Justme488/retroarch-dependency-installer) script.
### There is an [_uninstall_](https://github.com/Justme488/remove-retroarch) script, if you would like to remove files/folders it created.

# How to use:
* Enable "[_Source code repositories_]( https://github.com/Justme488/screenshots/blob/master/build-retroarch/mint-software-sources.png)" in _Menu > System Settings > Software Sources_
* Install the needed dependencies (The [dependency installer link](https://github.com/Justme488/retroarch-dependency-installer) shows what I needed)
* Run `./build-retroarch`

## Cores built/updated:
| System | Core(s)
|--------|------|
| Arcade | FinalBurn Neo|
| Atari 2600 | Stella|
| Atari 5200 | Atari800 |
| Atari 7800 | ProSystem |
| Atari Jaguar | Virtual Jaguar |
| Atari Lynx |Handy |
| Bandai WonderSwan/Color | Beetle Cygne |
| MSX/SVI/ColecoVision/SG-1000 | blueMSX |
| NEC PC Engine / CD | Beetle PCE Fast |
| Nintendo 3DS | Citra |
| Nintendo DS | melonDS |
| Nintendo Game Boy / Color | Gambatte |
| Nintendo Game Boy Advance | gpSP</br>mGBA |
| Nintendo GameCube / Wii | Dolphin |
| Nintendo NES | FCEUmm</br>Mesen</br>Nestopia UE |
| Nintendo 64 | Mupen64Plus-Next</br>ParaLLel N64 |
| Nintendo SNES | Snes9x - current |
| Nintendo Virtual Boy | Beetle VB |
| Sega Dreamcast | Flycast |
| Sega MS/GG/MD/CD | Genesis Plus GX |
| Sega MS/MD/CD/32X | PicoDrive |
| Sega Saturn | Yabause |
| SNK Neo Geo CD | NeoCD |
| Sony PlayStation | Beetle PSX HW</br>Beetle PSX</br>DuckStation</br>PCSX ReARMed |
| Sony PlayStation Portable | PPSSPP |
| The 3DO Company - 3DO | Opera |
