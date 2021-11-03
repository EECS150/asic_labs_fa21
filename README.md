# EECS 151/251A ASIC Labs Fall 21

This lab course consists of 6 labs and a final project. The labs go through the ASIC design flow, from RTL through GDS. 
These labs are now available in two process technologies, 
the [ASAP7 7nm Predictive PDK](http://asap.asu.edu/asap/) (a non-implementable finFET technology developed for educational purposes)
and the [Skywater 130nm PDK](https://skywater-pdk.readthedocs.io/en/latest/) (a real open-source 130nm CMOS process developed by Google and Skywater foundries).

## ASAP7 Labs
- [Lab 1: Getting Around the Compute Environment](lab1/spec.md)
- [Lab 2: Simulation](lab2/spec.md)
- [Lab 3: Logic Synthesis](lab3/spec.md)
- [Lab 4: Floorplanning, Placement, Power, and CTS](lab4/spec.md)
- [Lab 5: Parallelization and Routing](lab5/spec.md)
- [Lab 6: SRAM Integration, DRC, LVS](lab6/spec.md)

## ASIC Final Project
This project guides students through writing their own CPU core and cache, and pushing this design through the ASIC flow to achieve a physical design. 
- [Project Overview](project/overview.md) : Introduction, Project setup and Grading
- [Checkpoint 1](project/checkpoint1.md) :  ALU design and Pipeline diagram 
- [Checkpoint 2](project/checkpoint2.md) : Fully functioning core
- [Checkpoint 3](project/checkpoint3.md) : Cache
- [Checkpoint 4](project/checkpoint4.md) : Synthesis, PAR & Power

## Sky130 Labs
Alternate versions of the ASAP7 labs above use the Skywater 130nm PDK instead. Lab 6 is omitted because (1) the Sky130 SRAMs are currently not mature enough to be used for educational purposes, and (2) for DRC/LVS, the Sky130 Calibre decks are still under NDA, and while the open-source decks are available (for use with Magic and Netgen), our ASIC design flow does not currently support these open-source EDA tools. To learn about SRAMs, DRC, and LVS, please follow the ASAP7 version of Lab 6 above.
- [Lab 1: Getting Around the Compute Environment](lab1/spec.md)
- [Lab 2: Simulation](lab2/spec_sky130.md)
- [Lab 3: Logic Synthesis](lab3/spec_sky130.md)
- [Lab 4: Floorplanning, Placement, Power, and CTS](lab4/spec_sky130.md)
- [Lab 5: Parallelization and Routing](lab5/spec_sky130.md)
