# PCIe Switch Expansion Board for Antmicro Baseboard for Jetson Orin

Copyright (c) 2026 [Antmicro](https://www.antmicro.com)
![](img/pcie-switch-render.png)

## Overview

This project contains open hardware design files for an expansion board compatible with Antmicro's [Baseboard for Jetson Orin](https://github.com/antmicro/jetson-orin-baseboard).
It features PCIe 3.0 switch that expands the number of available PCIe ports by connecting multiple PCIe endpoint devices to a single PCIe root complex.
The expansion board includes an OCuLink Connector and two M.2 (key-M) slots intended for connecting additional storage solutions with RAID support to the Baseboard for Jetson Orin.
Both M.2 slots support 2280 and 2242 M.2 NVMe discs.
The design files were prepared in KiCad 10.x.

## Key features

* Baseboard for Jetson Orin expansion connector
* Support for 2280 and 2242 disk sizes
* 1x M.2 key M PCIe x2 slot 
* 1x M.2 key M or 1x OCuLink Connector PCIe x2 (multiplexed lane)

## Project structure 

The main directory contains KiCad PCB project files, LICENSE, and README.
The remaining files are stored in the following directories:

* `img` - contains graphics for this README

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
