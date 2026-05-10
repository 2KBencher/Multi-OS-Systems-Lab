# AMD Hackintosh Compatibility

## Overview

This project documents extensive testing of macOS installations on AMD-based hardware configurations, focusing on system stability, compatibility, and low-level troubleshooting.

---

## Hardware Platforms Tested

* Ryzen 3 3200G
* Ryzen 5 1600
* Ryzen 5 2600X
* iGPUs: Vega 8
* dGPUs: RX 580, R9 290

---

## macOS Versions Tested

* High Sierra
* Mojave
* Catalina
* Big Sur
* Monterey
* Ventura
* Sonoma / newer experimental builds (where applicable)

---

## Focus Areas

* Bootloader configuration (OpenCore)
* Kernel compatibility on AMD CPUs
* GPU acceleration and driver behavior
* ACPI / system patching
* Stability across updates

---

## Key Challenges

* Unsupported CPU architecture limitations
* GPU driver inconsistencies
* Kernel panics during boot
* macOS version compatibility breaks

---

## Solutions Applied

* Custom OpenCore configurations
* Iterative boot argument tuning
* Hardware-specific patches
* System-level debugging and log analysis

---

## Outcome

A structured compatibility matrix showing which hardware/software combinations are stable, partially working, or unsupported.

---

## Purpose

This project serves as a practical exploration of OS-level compatibility engineering on non-standard hardware.

