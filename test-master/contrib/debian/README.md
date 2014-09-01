
Debian
====================
This directory contains files used to package naturacoind/naturacoin-qt
for Debian-based Linux systems. If you compile naturacoind/naturacoin-qt yourself, there are some useful files here.

## naturacoin: URI support ##


naturacoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install naturacoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your naturacoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/naturacoin128.png` to `/usr/share/pixmaps`

naturacoin-qt.protocol (KDE)

