# Drivers and Firmware Management (Windows 11)

## Overview
This document outlines the driver and firmware management approach used for this Windows 11 desktop.  
It reflects common endpoint support practices, including BIOS updates, chipset drivers, GPU drivers, and system stability validation.

---

## BIOS / Firmware

- Motherboard: ASUS ROG Strix B550-F Gaming (Wi-Fi)
- BIOS Update Status: Updated post-build
- Update Method:
  - BIOS updated via ASUS UEFI EZ Flash utility
- Reason for Update:
  - Improved system stability
  - CPU compatibility and microcode updates
  - Memory compatibility improvements

---

## Chipset Drivers

- Vendor: AMD
- Driver Source: AMD official support site
- Components Installed:
  - AMD Chipset Driver Package
  - Power plan optimizations
- Notes:
  - Chipset drivers installed prior to GPU driver updates
  - System reboot performed after installation

---

## GPU Drivers

- GPU: NVIDIA GeForce RTX 2060 Super
- Driver Management Approach:
  - Primary: NVIDIA GeForce Experience
  - Secondary: Manual driver installation when required
- Use Cases for Manual Installation:
  - Rolling back unstable driver versions
  - Installing specific versions for compatibility or stability
- Installation Notes:
  - Clean installation selected when switching driver branches
  - Reboot performed after driver changes

---

## Network and Peripheral Drivers

- Wi-Fi / LAN:
  - Installed via motherboard vendor support page
- Audio:
  - Realtek audio driver installed from ASUS support
- Peripheral Devices:
  - Plug-and-play drivers verified via Device Manager

---

## Operating System Context

- Original OS: Windows 10 (OEM installation)
- Upgrade Path: In-place upgrade to Windows 11
- Update Management:
  - Windows Update enabled for security and cumulative updates
  - Driver updates monitored to avoid conflicts with vendor drivers

---

## Validation and Stability Checks

- Verified no unknown devices in Device Manager
- Confirmed system uptime and stability after driver updates
- Monitored system temperatures and performance post-update

---

## Change Tracking
All major driver and firmware changes are documented to support troubleshooting and rollback if necessary.

