
Debian
====================
This directory contains files used to package touchd/touch-qt
for Debian-based Linux systems. If you compile touchd/touch-qt yourself, there are some useful files here.

## touch: URI support ##


touch-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install touch-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your touchqt binary to `/usr/bin`
and the `../../share/pixmaps/touch128.png` to `/usr/share/pixmaps`

touch-qt.protocol (KDE)

