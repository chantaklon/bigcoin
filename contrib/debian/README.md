
Debian
====================
This directory contains files used to package bigd/big-qt
for Debian-based Linux systems. If you compile bigd/big-qt yourself, there are some useful files here.

## big: URI support ##


big-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install big-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bigqt binary to `/usr/bin`
and the `../../share/pixmaps/big128.png` to `/usr/share/pixmaps`

big-qt.protocol (KDE)

