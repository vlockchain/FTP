
Debian
====================
This directory contains files used to package fictecpagosd/fictecpagos-qt
for Debian-based Linux systems. If you compile fictecpagosd/fictecpagos-qt yourself, there are some useful files here.

## fictecpagos: URI support ##


fictecpagos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fictecpagos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fictecpagosqt binary to `/usr/bin`
and the `../../share/pixmaps/fictecpagos128.png` to `/usr/share/pixmaps`

fictecpagos-qt.protocol (KDE)

