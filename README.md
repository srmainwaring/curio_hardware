# Curio Hardware

Addition parts for a Sawppy rover.

## Overview

This repository contains [FreeCAD](https://www.freecadweb.org/) and
STL files for additional accessories for
[Roger Chen's Sawppy rover](https://github.com/Roger-random/Sawppy_Rover).

The parts have been printed on a Prusa i3 mk3S printer using PTEG
filament. G-code was generated using PrusaSlicer configured with the
print settings described in the
[Sawppy Rover documentation](https://github.com/Roger-random/Sawppy_Rover/blob/master/docs/Print%20Overview.md).

## Bogie stops

The stops are to prevent the bogie arm attached to the middle wheel
rising from rising above the rear rocker arm and damaging the
servo wires.

***Printing:***

- Approx. 40 mins for a pair

***Assembly:***

Fit the stops with a M3 threaded heat insert and afix to the inside
slot of each front bogie arm with a M3 square nut and M3 x 16mm socket
head screw.

## RPLidar A1 mounting plate and cowling

The mounting plate and cowling are for fixing a Slamtec RPLidar A1
onto a Sawppy rover.

***Printing:***

- Mounting plate: approx. 2h 30min
- Cowling: approx. 5h

The cowling requires support and will need to be cleaned up post-print.
It may help to clean the holes in both the mounting plate and cowling
with a 3mm drill.

***Assembly:***

The mounting plate attaches to the front left corner of the main
body box. You will need to remove the body corner to insert
8 M3 square nuts into the T-slot into which
8 M3 x 16mm socket head screws will be fixed.

Prior to attaching the mounting plate to the rover, fix the
RPLidar A1 USB-to-TTL board to the underside of the
mounting plate. Make sure it is aligned so the ribbon cable comes up
and through the rectangular slot. Attach the ribbon cable to the
laser scan assembly then fix to the top of the plate. You may also
wish to insert the micro-USB cable into the USB-to-TTL board before
attaching as it is awkward (but not impossible)
to attach once assembled.

Place the cowling over the laser scanner and check the motor is clear
and the scan drum can rotate without obstruction. Then fix the
cowling and mounting plate to the rover body box with the
M3 x 16mm screws.

## License

This software is licensed under the BSD-3-Clause license found in
the LICENSE file in the root directory of this source tree.
