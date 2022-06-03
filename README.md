# thundertop
Taking a desktop thunderbolt dock, and turning it into a mostly portable laptop-looking dock.

## Design
The current plan for a physical design is essentially as follows:

Take the dock, and make it look, feel, and function like a laptop when plugged in.

## Hardware
The hardware list for this project *will* change over time.

### Dock To Be Converted
* Manufacturer: `HP`
* Part Number: `P5Q58AAABA`
* Model: `HSTNN-CX01`
* Integrated Circuits:
    * Intel Thunderbolt 3 Controller IC:
        * `DSL6540`
    * Synaptics DisplayPort MST (Multi Stream Transport) hub IC:
        * `VMM3320BJG`
    * Broadcom Gigabit Ethernet Controller IC:
        * `BCM57762`
    * Synaptics Audio Cross Mixer IC:
        * `CX20701`
    * Winbond EEPROM IC:
        * `W25Q80DVSIG`
    * Asmedia USB3.2 Gen1 Hub IC:
        * `ASM1074`
    * Asmedia PCI Express to USB3.0 IC:
        * `ASM1042A`
    * Texas Instruments USB Type-C and USB PD controller power switch and high-speed multiplexer IC:
        * `TPS65982`

### Laptop Display
`TBD`

### Keyboard
`TBD`

### Speakers
`TBD`

### Trackpad
`TBD`

### Battery (?)
`TBD`
There's a good case to just not have one, as it will always be plugged in.

### Chassis
`TBD`
(something 3D printed most likely as a start)

## Issues
There will be many of them, and to document this process I will be using github issues.

The issues will be living documents for each step in the conversion process, and then be converted from there into the requisite information to have within the repository.

## My Goal
Ultimately, I hope to have something that can be connected to a Thunderbolt 3/4 device, and function as if it were a laptop.

A side goal of this project is to document this entire process, such that someone else could reproduce the work I have done.

## Inspiration
There are a few mass-market products that have similar features to what I would like to go for, but they are not Thunderbolt compatible.

*Why do I want thunderbolt?* Because I do, and for no other reason!

There's a very good argument *against* Thunderbolt:
* It complicates design
* It involves substantially more components with much tighter tolerances.
* It has direct access to the PCIe bus.
But again, I want to, because I think it would be neat.

If all else fails, there's always USB, DisplayPort, and audio adapters.
