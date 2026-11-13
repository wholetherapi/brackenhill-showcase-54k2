---
title: Pollen Counter
slug: pollen-counter
year: 2025
summary: An optical particle counter that classifies airborne pollen grains in real time.
maintainers:
  - Mira Koskinen
  - Ade Oyelaran
license: CERN-OHL-S-2.0
tags:
  - optics
  - air-quality
  - microcontroller
build_kit: BH-PC-200
package_url: https://github.com/wholetherapi/pollen-counter
---

## Overview

Pollen Counter uses a low-cost optical sensor head and a focusing aperture to
count airborne grains as they pass a sample window. A small classifier runs on
the host microcontroller and reports counts over a serial interface.

## Field notes

The intake fan is filtered with a replaceable mesh disc and the optical chamber
is coated to reduce stray reflections. Units are swapped every 48 hours during
the field campaign.

## Documentation

The fabrication package is published separately from this page; ask the
maintainers for the assembly drawings if you are building a unit.
