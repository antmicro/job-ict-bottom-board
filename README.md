# Jetson Orin Baseboard Test Rig Base

Copyright (c) 2025 [Antmicro](https://www.antmicro.com)


## Overview

This project contains open hardware design files for a test platform designed for Antmicro's [Jetson Orin Baseboard](https://github.com/antmicro/jetson-orin-baseboard).
The board connect with the Baseboard's test points via spring probes and passes the signals to the Antmicro's test rig base board. The test rig is also equipped with four RG LEDs to indicate the testing status.

The design files were prepared in KiCad 9.x.

## Key features

* Spring loaded test probes matching the [Jetson Orin Baseboard's](https://github.com/antmicro/jetson-orin-baseboard) pinout
* Four RG LEDs
* ESD protection on all channels
* Compatible with Test Rig Base

## Project structure

The main directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* `assets` - contains visual assets for showcasing this design on [Open Hardware Portal](https://openhardware.antmicro.com).

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
