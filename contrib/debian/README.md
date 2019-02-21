
Debian
====================
This directory contains files used to package youcoind/youcoin-qt
for Debian-based Linux systems. If you compile youcoind/youcoin-qt yourself, there are some useful files here.

## youcoin: URI support ##


youcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install youcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your youcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/youcoin128.png` to `/usr/share/pixmaps`

youcoin-qt.protocol (KDE)

