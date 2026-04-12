# Multi-OS-Systems-Lab
Multi-boot systems, AMD Hackintosh setups, and low-level OS engineering (EFI, OpenCore, Linux, Windows)

#

## Overview

This repository documents a series of advanced system engineering projects focused on multi-boot environments, Hackintosh setups on AMD hardware, and low-level OS troubleshooting.

The goal of this lab is to design, deploy, and debug complex operating system configurations across multiple platforms using a single physical machine.

---

## Key Areas of Work

* Multi-boot system design (Windows / Linux / macOS)
* EFI partitioning (GPT, boot managers)
* Bootloader configuration (OpenCore)
* AMD Hackintosh compatibility (Ryzen CPUs, various GPUs)
* Kernel and driver troubleshooting
* Cross-version OS testing

---

## Projects

### 1. Triple Boot System

A fully functional triple-boot setup:

* Windows 11
* Ubuntu Linux
* macOS (various versions)

Key features:

* Single disk configuration (GPT/EFI)
* OpenCore bootloader
* Custom partition layout
* Stable switching between OS environments

 See: `triple-boot-system/`

---

### 2. AMD Hackintosh Compatibility Matrix

Extensive testing of macOS on unsupported AMD hardware.

Tested across:

* Ryzen 3 3200G (Vega 8)
* Ryzen 5 1600 / 2600X
* GPUs: Vega 8, RX 580, R9 290

macOS versions:

* High Sierra → Ventura → Sonoma / Tahoe (where applicable)

Focus:

* Compatibility validation
* Stability testing
* Hardware-specific fixes

 See: `amd-hackintosh-matrix/`

---

### 3. OpenCore Configurations

Custom OpenCore EFI configurations for different hardware setups.

Includes:

* Boot arguments
* ACPI patches
* Kext configuration

 See: `opencore-configs/`

---

## Technical Skills Demonstrated

* Disk partitioning (GPT, EFI systems)
* Bootloader debugging (OpenCore)
* Low-level OS troubleshooting (kernel panics, boot failures)
* Hardware compatibility analysis
* Linux system configuration
* Multi-environment system design

---

## Real-World Problem Solving

Examples of issues resolved:

* Bootloader conflicts between multiple OS installations
* Kernel panics on unsupported hardware
* GPU driver incompatibilities
* ACPI-related boot failures
* EFI misconfigurations

---

## Approach

Each project follows:

1. System design
2. Installation & configuration
3. Failure analysis
4. Debugging & fixes
5. Documentation

---

## Goal

This repository serves as a practical demonstration of system engineering skills, with emphasis on:

* Problem-solving in complex environments
* Reproducible system setups
* Deep understanding of OS-level behavior

---

## Notes

All configurations are tested on real hardware environments and documented based on actual troubleshooting experience.

---

## Contact

Open to opportunities in:

* System Administration
* DevOps / Infrastructure
* Platform Engineering
