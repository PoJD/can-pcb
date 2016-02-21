# can-pcb
Custom PCBs to be used for CAN bus in my home automation project
This repository contains 2 separate Eagle projects (http://www.cadsoftusa.com/) for custom PCB designed by myself to allow home automation system work with CAN BUS.

The basic idee is that there are 2 projects:

1. CanRelay
2. CanSwitch

Can-relay is a PCB that will be directly connected to the SSR relays and will consume traffic over the CAN bus (from either the webapp - hawa - or from CanSwitch) and translate that to switching output pins on that board's chip on or off. The board chip is PIC18F25K80 and is programmed through either CanRelay.X or CanSwitch.X mplab projects here: https://github.com/PoJD/can

See details of the communication protocal in that project, this is simply a project designed to have custom boards that would then be installed in the house.