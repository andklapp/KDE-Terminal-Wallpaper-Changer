# KDE-Terminal-Wallpaper-Changer
This is a simple wallpaper changing script for KDE Plasma Shell. They don't seem to provide a
simple, scriptable way to do this.

The original script came from https://store.kde.org/p/1169583/

### Installation
Copy ksetwallaper to your PATH.

### Usage
Just call it with `ksetwallpaper <filename>`. Filenames can be relative or absolute.

# Notes and Known Issues
* If you lock widgets, this script will not work.

* If you point it at an incompatible image file, it appears to just change to solid black and exits
without any errors.
