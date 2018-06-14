# Custom config to atom-runner

I found the default style very hard to read, and with needless extra information.

This config strips the `h1` from the `atom-runner-view` (which is already visible in the view title).

It also configures the `STDOUT` and `STDERR` responses to use the global input font size and family.

## Installation

To use these files, atom runner must first be installed using atom's package installer.

Then navigate to the local atom config directory:
* Atom's GUI: Preferences > Packages > atom-runner > View Code

Copy the 2 folders into their correct locations as per the layout in this repository.

## N.B.

I am not actively checking this... if my config breaks I'll look to fix it, but worth casting an eye over the changes if installing on a newer version of atom-runner. There's only a few lines different from the current version and I wouldn't want overwriting these configs to break future improvements to the mod!

There's possibly also a way to add these custom mods without havking the internal config... but I couldn't be bothered to work it out. Let me know if anyone else has such a fix!
