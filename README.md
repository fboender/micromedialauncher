# MircoMediaLauncher

MicroMediaLauncher (mmlauncher) is a super-lightweight media browser and
launcher. It was written because I got tired of slow, laggy, crashing media
centers with all their bells and whistles.

mmlauncher supports NOTHING. It's nothing more than a file browser / launcher
with a large font. It has no plugins, doesn't fetch pretty pictures, doesn't
send info on every movie you watch all over the internet. It also doesn't crash
and is exeptionally fast. It has almost no dependencies.

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


