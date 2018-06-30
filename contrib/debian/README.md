
Debian
====================
This directory contains files used to package clashd/clash-qt
for Debian-based Linux systems. If you compile clashd/clash-qt yourself, there are some useful files here.

## clash: URI support ##


clash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install clash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your clashqt binary to `/usr/bin`
and the `../../share/pixmaps/clash128.png` to `/usr/share/pixmaps`

clash-qt.protocol (KDE)

