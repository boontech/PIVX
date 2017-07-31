
Debian
====================
This directory contains files used to package boondevcoind/boondevcoin-qt
for Debian-based Linux systems. If you compile boondevcoind/boondevcoin-qt yourself, there are some useful files here.

## boondevcoin: URI support ##


boondevcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install boondevcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your boondevcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/boondevcoin128.png` to `/usr/share/pixmaps`

boondevcoin-qt.protocol (KDE)

