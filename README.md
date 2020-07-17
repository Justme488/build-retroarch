#DO NOT USE - WIP


## Script for building/updating retroarch and select cores
### I changed, and added a few things from the [Original script written by Sanaki](https://gist.github.com/Sanaki/44200de635032c21d5d9a11aba75b23b/)
### Here's how it works
* Clones or pulls changes from libretro-super repo
* Builds Retroarch
* Builds cores (see cores below - WIP)
* Locks those cores (you can use the online updater to update all cores without overwrite)
* Creates a folder in _/home/username/.config_ named _retroarch_
### Features include:
* Creates a log in _/home/your-username/.config_ (when you install or update)
* Creates _Retroarch_ shortcut in menu - _Menu > Games > Retroarch_
* Creates _Update Retroarch_ shortcut in menu - _Menu > Accessories > Update Retroarch_
* Moves the script to where it belongs. You can run it from anywhere in your home directory the first time.
* Checks if /home/username/.local/bin is in your PATH. If not, it tells you restart your computer.
### There is a [_Dependency installer script_](https://github.com/Justme488/retroarch-dependency-installer) here.
### There is an [_uninstall script_](https://github.com/Justme488/remove-retroarch) here, if you would like to remove files/folders it created.
