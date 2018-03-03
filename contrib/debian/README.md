
Debian
====================
This directory contains files used to package xeroxcoind/xeroxcoin-qt
for Debian-based Linux systems. If you compile xeroxcoind/xeroxcoin-qt yourself, there are some useful files here.

## bitcoin: URI support ##


xeroxcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xeroxcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xeroxcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

xeroxcoin-qt.protocol (KDE)

