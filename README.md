# Script for building/updating retroarch and select cores for Linux Mint
Tested with Linux Mint 20, but _should_ work with Ubuntu.
### I changed, and added a few things from the [Original script written by Sanaki](https://gist.github.com/Sanaki/44200de635032c21d5d9a11aba75b23b/)
(To make it more user friendly)
### Features include:
* Creates folders in /home/username/.config/retroarch
* Creates a log in _/home/username/.config_ (when you install or update - removes the old log when you update)
* Creates _Retroarch_ shortcut in menu - _Menu > Games > Retroarch_
* Creates _Update Retroarch_ shortcut in menu - _Menu > Accessories > Update Retroarch_
* Moves the script to where it belongs. You can run it from anywhere in your home directory the first time.
* Checks if /home/username/.local/bin is in your PATH. If not, it tells you restart your computer.<br />
  ( _/home/username/.local/bin_ will be in your PATH after you reboot )
* See the cores below that it builds and updates. ( They can be changed in 
### There is a [_dependency installer_](https://github.com/Justme488/retroarch-dependency-installer) script.
### There is an [_uninstall_](https://github.com/Justme488/remove-retroarch) script, if you would like to remove files/folders it created.

# How to use:
* Enable "[_Source code repositories_]( https://github.com/Justme488/screenshots/blob/master/build-retroarch/mint-software-sources.png)" in _Menu > System Settings > Software Sources_
* Install the needed dependencies (The [dependency installer link](https://github.com/Justme488/retroarch-dependency-installer) shows what I needed)
* Run `./build-retroarch`
