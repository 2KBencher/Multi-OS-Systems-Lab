# Triple Boot System (Windows / Linux / macOS)

## Overview

This project demonstrates the design and implementation of a triple-boot system on a single physical disk using GPT partitioning and UEFI boot management.

---

## Operating Systems

* Windows 11
* Ubuntu Linux
* macOS (various versions depending on hardware compatibility)

---

## System Design

* GPT partition scheme
* EFI System Partition (ESP)
* Separate partitions for each OS
* Centralized boot management

---

## Boot Management

The system uses a bootloader-based approach (OpenCore / UEFI entries) to manage multiple operating systems on a single machine.

---

## Key Engineering Challenges

* EFI partition conflicts
* Boot order management
* OS installation order dependency
* Cross-OS compatibility issues

---

## Solutions Applied

* Manual partition planning before installation
* Bootloader configuration tuning
* Iterative troubleshooting of boot failures
* Recovery using live USB environments

---

## Result

A stable multi-boot environment allowing seamless switching between Windows, Linux, and macOS.

---

## Status

✔ Fully working setup on real hardware
✔ Tested across multiple boot scenarios
✔ Stable OS switching

