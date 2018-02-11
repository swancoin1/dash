
Debian
====================
This directory contains files used to package mewcoind/mewcoin-qt
for Debian-based Linux systems. If you compile mewcoind/mewcoin-qt yourself, there are some useful files here.

## mewcoin: URI support ##


mewcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mewcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mewcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/mewcoin128.png` to `/usr/share/pixmaps`

mewcoin-qt.protocol (KDE)

