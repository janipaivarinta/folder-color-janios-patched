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

## AI Transparency

This project includes AI-assisted source code modifications
and documentation using OpenAI ChatGPT (GPT-6).

The modifications were developed through human-directed
investigation, debugging, and testing.

For details about AI involvement, development responsibilities,
and verification limitations, see
[AI-TRANSPARENCY.md](AI-TRANSPARENCY.md).

## License

This project is licensed under the GNU General Public License
version 3 or later (GPL-3.0-or-later).

Originally developed by Marcos Alvarez Costales.
JaniOS modifications maintained by Jani Päivärinta.
