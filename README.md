### Script for building retroarch, and select cores for Debian/Ubuntu/Mint

### I changed, and added a few things from the [Original script written by Sanaki](https://gist.github.com/Sanaki/44200de635032c21d5d9a11aba75b23b/)

### Features include:

* Checks for build dependencies, and installs if they are needed.

* Creates _Retroarch_ shortcut in menu - _Menu > Games > Retroarch_

* Creates _Update Retroarch_ shortcut in menu - _Menu > Accessories > Update Retroarch_

* Moves the script to where it belongs. You can run it from anywhere in your home directory the first time.

* Checks if /home/username/.local/bin is in your PATH. If not, it tells you to log out/in, or restart.

