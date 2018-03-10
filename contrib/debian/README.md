
Debian
====================
This directory contains files used to package stannumd/stannum-qt
for Debian-based Linux systems. If you compile stannumd/stannum-qt yourself, there are some useful files here.

## stannum: URI support ##


stannum-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stannum-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stannum-qt binary to `/usr/bin`
and the `../../share/pixmaps/stannum128.png` to `/usr/share/pixmaps`

stannum-qt.protocol (KDE)

