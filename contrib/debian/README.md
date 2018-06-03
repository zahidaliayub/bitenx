
Debian
====================
This directory contains files used to package bitenxd/bitenx-qt
for Debian-based Linux systems. If you compile bitenxd/bitenx-qt yourself, there are some useful files here.

## bitenx: URI support ##


bitenx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitenx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitenx-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitenx128.png` to `/usr/share/pixmaps`

bitenx-qt.protocol (KDE)

