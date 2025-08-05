# Introduction

> [!WARNING]
> This is a fork of the Acheron MX KiCad footprint library. Certain footprints have been modified (according to my preference) to have larger pad surface area compared to the original footprints.

Acheron MX is the AcheronProject's library for MX style footprint switches. These footprints have exposed pads on the front and back of the PCB, and were independently developed using the MX switch datasheet.

## How to use

1. Clone the git repository into a ``libraries`` folder inside your KiCad project main folder, also known was ``${KIPRJMOD}``
2. In PCBNEW, go into ``Preferences > Manage Footprint Libraries... `` then under the Project tab, press the plus sign and select the ``acheron_MX.pretty`` folder.
3. After that the library footprints should be available for addition in the PCB layout from the ``Add a footprint`` button. Click that button or press O and try adding a footprint from the library like the ``MX100`` footprint.

## Copyright notice

This project is released under the Acheron Open-Hardware License V1.3. For the license, please refer to the LICENCE.md file.
