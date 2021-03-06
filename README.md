# MicroMediaLauncher

MicroMediaLauncher (mmlauncher) is a super-lightweight media browser and
launcher. It was written because I got tired of slow, laggy, crashing media
centers with all their bells and whistles.

mmlauncher supports NOTHING. It's nothing more than a file browser / launcher
with a large font. It has no plugins, doesn't fetch pretty pictures, doesn't
send info on every movie you watch all over the internet. It also doesn't crash
and is exceptionally fast. It has almost no dependencies.

This is what it looks like:

![](https://raw.githubusercontent.com/fboender/micromedialauncher/master/screenshot.png)

## Installation

Install the requirement:

    sudo apt-get install python-tk

Potentially edit the configuration file to suit your machine. You may want to
look into the 'commands' section and change the commands to any of the
multimedia player that happens to be installed on your machine.

Then, run it:

    ./mmlauncher /path/to/my/media/files/

and done.

## Keybindings

    <Enter>: Enter dir or launch file under cursor
    <Backspace>: Go up one dir
    <Escape> / <Alt-F4>: Quit
    A-Z / a-z / 0-9: Jump to next item that starts with this key.

## License

MicroMediaLauncher is the Copyright of Ferry Boender and is released under the
GPL v3 License:

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

