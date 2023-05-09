
Debian
====================
This directory contains files used to package wendd/wend-qt
for Debian-based Linux systems. If you compile wendd/wend-qt yourself, there are some useful files here.

## pivx: URI support ##


wend-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wend-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wend-qt binary to `/usr/bin`
and the `../../share/pixmaps/wend128.png` to `/usr/share/pixmaps`

wend-qt.protocol (KDE)

