
Debian
====================
This directory contains files used to package addd/add-qt
for Debian-based Linux systems. If you compile addd/add-qt yourself, there are some useful files here.

## add: URI support ##


add-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install add-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your addqt binary to `/usr/bin`
and the `../../share/pixmaps/add128.png` to `/usr/share/pixmaps`

add-qt.protocol (KDE)

