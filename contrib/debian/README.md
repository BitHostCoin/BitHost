
Debian
====================
This directory contains files used to package bithostd/bithost-qt
for Debian-based Linux systems. If you compile bithostd/bithost-qt yourself, there are some useful files here.

## bithost: URI support ##


bithost-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bithost-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bithostqt binary to `/usr/bin`
and the `../../share/pixmaps/bithost128.png` to `/usr/share/pixmaps`

bithost-qt.protocol (KDE)

