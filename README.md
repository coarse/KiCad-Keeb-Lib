# KiCad Keeb Lib

KiCad libraries of commonly used parts for keyboard PCBs

## Included Libraries

### Symbol Libraries

- **keeb_chips.lib** - symbols for specific version of generic parts or other ICs, e.g. 1N4148, PRTR5V0U2x, BSS138
- **keeb_connectors.lib** - symbols for USB, pin headers, and other connectors
- **keeb_lighting.lib** - symbols for LEDs and LED drivers
- **keeb_mcu.lib** - symbols for microcontrollers, controller boards, and other controllers
- **keeb_parts.lib** - symbols for generic parts, e.g. crystal, diode, capacitor, resistor
- **keeb_power.lib** - power symbols and symbols for power-related ICs

### Footprint Libraries

- WIP

## Instructions

- Clone the repository to your computer on any folder
- Setup a new KiCad path (`Preferences > Configure Paths`) named `GIT_KB_LIBRARY` pointing to the cloned repository
- Import the libraries/symbols into your project

## Contributing

Feel free to add more footprint/symbol libraries via pull requests. I will manually check all changes so it might take some time to get them merged.
