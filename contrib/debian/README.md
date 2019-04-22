
Debian
====================
This directory contains files used to package litegoldcoinmnd/litegoldcoinmn-qt
for Debian-based Linux systems. If you compile litegoldcoinmnd/litegoldcoinmn-qt yourself, there are some useful files here.

## litegoldcoinmn: URI support ##


litegoldcoinmn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install litegoldcoinmn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your litegoldcoinmnqt binary to `/usr/bin`
and the `../../share/pixmaps/litegoldcoinmn128.png` to `/usr/share/pixmaps`

litegoldcoinmn-qt.protocol (KDE)

