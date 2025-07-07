# Jetson Orin Baseboard ICT Bottom Board

Copyright (c) 2025 [Antmicro](https://www.antmicro.com)

![](img/job-ict-bottom-board-render.png)

## Overview

This project includes PCB design files for a board which allows to perform In-Circuit Testing (ICT) of Antmicro's [Jetson Orin Baseboard](https://github.com/antmicro/jetson-orin-baseboard).
It contains a set of spring-loaded needle probes that connect to the relevant testpoints on the bottom side of the Jetson Orin Baseboard.
This allows to perform In-Circuit driving of DC/DC enable signals and measure the resulting voltages on the board under test. 
The Jetson Orin Baseboard ICT Bottom Board should be used with the [ICT Baseboard](https://github.com/antmicro/ict-baseboard) which performs the actual testing.  

The design files were prepared in KiCad 9.x.

## Key features

* Spring loaded test probes matching the notable testpoints exposed on the [Jetson Orin Baseboard's](https://github.com/antmicro/jetson-orin-baseboard)
* Four bi-color (Red/Green) LEDs for status indication
* ESD protection for all IO channels
* Compatible with [ICT Baseboard](https://github.com/antmicro/ict-baseboard)

## Project structure

The main directory contains KiCad PCB project files, a LICENSE, and a README. 
The remaining files are stored in the following directories:

* `img` - contains graphics for this README
* `mechanical` - contains mechanical part in `.step` format

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
