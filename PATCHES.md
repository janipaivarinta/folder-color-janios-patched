# JaniOS Folder Color Patches

This repository is a modified fork of [Folder Color](https://github.com/costales/folder-color), originally developed by Marcos Alvarez Costales and contributors.

## Purpose

The purpose of this fork is to improve the stability and compatibility of Folder Color with Nautilus and GTK4 on Debian 13 (trixie).

## Changes

- Improved GTK4 icon lookup error handling.
- Added fallback handling for unsupported Nautilus zoom levels.
- Improved metadata query handling.
- Reduced unnecessary icon-theme initialization.
- Removed unnecessary folder modification-time updates.
- Improved extension callback error handling.

## Compatibility

- Debian 13 (trixie)
- GNOME Files (Nautilus)
- GTK4
- Python 3

## Status

Experimental. Stability testing is ongoing.

## License

This project retains the original GPL licensing and copyright notices. Modifications are maintained as part of the JaniOS project.
