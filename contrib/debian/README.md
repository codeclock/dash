
Debian
====================
This directory contains files used to package suppod/suppo-qt
for Debian-based Linux systems. If you compile suppod/suppo-qt yourself, there are some useful files here.

## dash: URI support ##


suppo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install suppo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your suppo-qt binary to `/usr/bin`
and the `../../share/pixmaps/dash128.png` to `/usr/share/pixmaps`

suppo-qt.protocol (KDE)

