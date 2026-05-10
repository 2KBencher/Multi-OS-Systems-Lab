# Intel Hackintosh Compatibility

## Overview

This project documents extensive testing of macOS installations on Intel-based hardware configurations, focusing on system stability, compatibility, and low-level troubleshooting.

---

## Hardware Platforms Tested

* i5 7500T
* Core 2 Duo E7500
* iGPUs: UHD 630
* dGPUs: HD5870, R9 290

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

* Bootloader configuration (OpenCore, Clover)
* Kernel compatibility on Intel CPUs
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

