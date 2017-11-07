Berkeley Software Distribution Timeline | README
------------------------------------------------

* Copyright (C) 2010 Donjan Rodic
* Copyright (C) 2016-2017 Fabio Loli & contributors

Released under a BSD 2-clause like license as found in the LICENSE file

Original source: http://futurist.se/gldt/2010/09/20/bsd-timeline-up-for-grabs/

Current source: https://github.com/FabioLolix/BSD-timeline

### CONTRIBUTING

See [CONTRIBUTING](https://github.com/FabioLolix/BSD-Timeline/blob/master/CONTRIBUTING)

### Installation

If you want to build your own version, make sure you have gnuclad
installed.

To install gnuclad, you can download it at https://launchpad.net/gnuclad

For Arch users, use the AUR: https://aur.archlinux.org/packages/gnuclad/

After you have installed gnuclad, to build just the svg, run:

    gnuclad bsdt.csv SVG bsdt.conf

You can run the script `build.sh` to build the svg, png, and the tarball
containing the source, Inkscape is required to convert from svg to png.
