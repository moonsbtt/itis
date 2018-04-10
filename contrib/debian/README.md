
Debian
====================
This directory contains files used to package itisd/itis-qt
for Debian-based Linux systems. If you compile itisd/itis-qt yourself, there are some useful files here.

## itis: URI support ##


itis-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install itis-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your itisqt binary to `/usr/bin`
and the `../../share/pixmaps/itis128.png` to `/usr/share/pixmaps`

itis-qt.protocol (KDE)

