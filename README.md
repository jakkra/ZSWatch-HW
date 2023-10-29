# ZSWatch Hardware

> :warning: **ZSWatch v3 uses external flash on normal SPI. ZSWatch v4 switches it to QSPI. This improves performance significantly when having LVGL resources in the external flash. If this is important please wait for us to validate ZSWatch v4, you can find the untested design here https://github.com/jakkra/ZSWatch-HW/tree/move_flash_to_qspi. The new design have been ordered and expected to arrive around ~25 November 2023. Once it's been verified to work it will be merged to main.**:


## Table of Contents

- [ZSWatch Hardware](#zswatch-hardware)
  - [Table of Contents](#table-of-contents)
  - [About](#about)
  - [Directory structure](#directory-structure)
  - [Maintainer](#maintainer)

## About

Hardware repository for the [ZSWatch](https://github.com/jakkra/ZSWatch).

![PCB Top side](/docs/images/Preview.png)

Please check the [wiki](https://github.com/jakkra/ZSWatch/wiki) for more information about the project.

## Directory structure

- `cad`: 3D model of the complete PCB
- `docs`: All kind of project documentation like schematics, BOM, etc.
  - `drawings`: 2D drawings for subcomponents, etc.
  - `images`
- `production`: Production files for the PCB
  - `PCBWay`: Ordering instructions and production files ready for ordering at [PCBWay](https://www.pcbway.com/)
- `project`: KiCad project for the PCB

## Maintainer

- [Daniel Kampert](mailto:daniel.kameprt@kampis-elektroecke.de)
- [Jakob Krantz](mail@jakobkrantz.se)