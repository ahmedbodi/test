
Debian
====================
This directory contains files used to package fortcoind/fortcoin-qt
for Debian-based Linux systems. If you compile fortcoind/fortcoin-qt yourself, there are some useful files here.

## fortcoin: URI support ##


fortcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fortcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fortcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/fortcoin128.png` to `/usr/share/pixmaps`

fortcoin-qt.protocol (KDE)

