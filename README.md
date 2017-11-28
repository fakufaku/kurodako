Kurodako
========

An eight-channel compact microphone array based on the Beaglebone Black and PDM microphones.

Bill of Materials
-----------------

* 8x SPM1437HM4H-B PDM MEMS Microphones (Mouser 721-SPM1437HM4H-B)
* 8x 100nF capacitors, 0805 package
* 2x pin headers 2x40, 2.54mm spaced

Possibly also:
* 4x 100 ohms resistors

If we want to use wires rather than only PCB microphones:
* 8x Micromatch Male-On-Wire 4 pin connector
* 8x Micromatch Female-One-Board 4 pin connector SMD
* flat cable, 1.27mm, 4 wires

Dependencies
------------

* The PRU code doing the low pass filtering [repo](https://github.com/Scrashdown/PRU-Audio-Processing) [Work in progress]

License
-------

2017 (c) Robin Scheibler

This board was designed by Robin Scheibler and is shared under the [Creative Commons CC-BY-SA](https://creativecommons.org/licenses/by-sa/4.0/) license.
