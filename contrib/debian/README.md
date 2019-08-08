
Debian
====================
This directory contains files used to package bcxd/bcx-qt
for Debian-based Linux systems. If you compile bcxd/bcx-qt yourself, there are some useful files here.

## bcx: URI support ##


bcx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bcx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bcxqt binary to `/usr/bin`
and the `../../share/pixmaps/bcx128.png` to `/usr/share/pixmaps`

bcx-qt.protocol (KDE)

