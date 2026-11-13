---
title: Canopy Therm
slug: canopy-therm
year: 2025
summary: A solar-powered temperature and humidity logger for long-term forest canopy studies.
maintainers:
  - Ines Barros
  - Tobias Renn
license: CERN-OHL-S-2.0
tags:
  - environmental-sensing
  - solar
  - logger
build_kit: BH-CT-100
---

## Overview

Canopy Therm records temperature and relative humidity at ten-minute intervals
and stores a full season of readings on a removable microSD card. The board is
designed around a low-power microcontroller with a switched sensor rail so that
the unit survives several weeks of overcast weather on a single 6W panel.

## Field notes

The mast is 3D-printed in ASA and the sensor head is isolated from direct sun by
a laser-cut baffle. Calibration offsets are written to EEPROM at assembly time.

## Documentation

Assembly notes, wiring tables and enclosure drawings live in the design
package repository. The kit code is printed on the inside of the lid.
