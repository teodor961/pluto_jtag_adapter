# PLUTO JTAG ADAPTER

JTAG programmer for the PLUTOSDR evaluation kit from ADI.

## Features
- JTAG pins breakout from 1.28mm headers to 2.54 standard header pins for use with platform cable II or other external JTAG
- Integrated FT2232 USB to sync serial controller, to serve as a JTAG + UART host (Still work in progress)

## Known issues:
v1.0.0 - VREGOUT and VREGIN should be floating but connected to 1.8V
         VPHY and VPLL connected to 1.8V supply, should be connected to 3.3V through ferrite bead
