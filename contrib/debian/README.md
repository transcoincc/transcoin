
Debian
====================
This directory contains files used to package transcoind/transcoin-qt
for Debian-based Linux systems. If you compile transcoind/transcoin-qt yourself, there are some useful files here.

## transcoin: URI support ##


transcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install transcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your transcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/transcoin128.png` to `/usr/share/pixmaps`

transcoin-qt.protocol (KDE)

