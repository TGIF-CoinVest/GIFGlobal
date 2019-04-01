
Debian
====================
This directory contains files used to package tgifglobald/tgifglobal-qt
for Debian-based Linux systems. If you compile tgifglobald/tgifglobal-qt yourself, there are some useful files here.

## tgifglobal: URI support ##


tgifglobal-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tgifglobal-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tgifglobalqt binary to `/usr/bin`
and the `../../share/pixmaps/tgifglobal128.png` to `/usr/share/pixmaps`

tgifglobal-qt.protocol (KDE)

