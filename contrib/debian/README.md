
Debian
====================
This directory contains files used to package MakeMyCoind/MakeMyCoin-qt
for Debian-based Linux systems. If you compile MakeMyCoind/MakeMyCoin-qt yourself, there are some useful files here.

## MakeMyCoin: URI support ##


MakeMyCoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install MakeMyCoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your MakeMyCoinqt binary to `/usr/bin`
and the `../../share/pixmaps/MakeMyCoin128.png` to `/usr/share/pixmaps`

MakeMyCoin-qt.protocol (KDE)

