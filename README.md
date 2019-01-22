# This fork is intended for use with the [iDraw plotter](https://uunatek.com/product/idraw/)

The version of the drivers bundled with the iDraw (on the USB and online) is very old. My goal is to keep an up to date version of the Axidraw drivers with the required edits for the iDraw plotter.

## Current Status

I have located the version of the AxiDraw software that this the iDraw software is based off of ([version 1.0.2](https://github.com/evil-mad/axidraw/releases/tag/v1.0.2)). Currently there are no plans to support the laser because I don't have the laser attachment and I have no way to test it. My current plans are to only change the paramaters that are different between the AxiDraw v1.0.2 and iDraw v1.0.2 and bring them up to the current release. I don't expect that I need to make a lot of changes considering that the current AxiDraw drivers work besides some significant scaling issues.

# AxiDraw

The AxiDraw Extensions for Inkscape - Software to drive the AxiDraw drawing machine.

More about AxiDraw:  http://www.axidraw.com/

---------


**Normal install (Mac/Windows):**

Please read through the installation instructions on the [AxiDraw documentation site](http://wiki.evilmadscientist.com/Axidraw_Software_Installation)

**Manual install (Linux):**

Install (along with the dependencies listed below) as you would any other Inkscape extension.


---------
Dependencies:

1. [plotink](https://github.com/evil-mad/plotink) helper routines for Inkscape extensions.
2. eggbot_hatch.py from the [EggBot extensions for Inkscape](https://github.com/evil-mad/EggBot/).
3. [Pyserial](https://pypi.python.org/pypi/pyserial). (Note that an older version, 2.7, must be used on Windows when using Inkscape 0.91 or older.)


---------

[![Join the chat at https://gitter.im/evil-mad/axidraw](https://badges.gitter.im/evil-mad/axidraw.svg)](https://gitter.im/evil-mad/axidraw?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
