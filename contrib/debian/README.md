
Debian
====================
This directory contains files used to package prismd/prism-qt
for Debian-based Linux systems. If you compile prismd/prism-qt yourself, there are some useful files here.

## prism: URI support ##


prism-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install prism-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your prismqt binary to `/usr/bin`
and the `../../share/pixmaps/prism128.png` to `/usr/share/pixmaps`

prism-qt.protocol (KDE)

