
Debian
====================
This directory contains files used to package mrv_coind/mrv_coin-qt
for Debian-based Linux systems. If you compile mrv_coind/mrv_coin-qt yourself, there are some useful files here.

## mrv_coin: URI support ##


mrv_coin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mrv_coin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mrv_coin-qt binary to `/usr/bin`
and the `../../share/pixmaps/mrv_coin128.png` to `/usr/share/pixmaps`

mrv_coin-qt.protocol (KDE)

