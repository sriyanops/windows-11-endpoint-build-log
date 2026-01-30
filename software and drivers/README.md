# Windows Setup and Driver Configuration

This document outlines the operating system installation, driver configuration, and initial software validation performed for this Windows 11 endpoint.

The goal is to document a repeatable, stable setup process consistent with desktop support and endpoint management practices.



## Operating System Installation

- **Operating System:** Windows 11 Pro (64-bit)
- **Installation Type:** Clean installation
- **Installation Media:** Official Microsoft installation media
- **Partitioning:** OS installed on dedicated NVMe SSD (C:\)

Post-installation actions:
- Completed initial Windows setup and user configuration
- Applied all available Windows Updates
- Verified activation status



## Driver Installation Order

Drivers were installed in a controlled sequence to minimize conflicts and ensure stability:

1. **AMD Chipset Drivers**
   - Installed first to establish correct power management and platform behavior
   - ASUS Armoury Crate used to apply motherboard and chipset driver updates

2. **Graphics Driver**
   - NVIDIA GeForce RTX 2060 SUPER driver installed using official NVIDIA package
   - GeForce Experience and NVIDIA Control Panel installed to support easy future driver/display updates. 

3. **Network Drivers**
   - Ethernet and Wi-Fi drivers verified for connectivity and stability
   - Intel Driver & Support Assistant used to identify and apply applicable network driver updates

4. **Audio Driver**
   - Realtek audio driver installed and validated



## Device Manager Validation

After driver installation:
- No unknown or unrecognized devices present
- All hardware components properly enumerated
- No warning or error states observed

This confirms successful driver installation and hardware recognition.



## Firmware and Platform Notes

- BIOS version verified prior to OS configuration
- Default, stable firmware settings retained
- No experimental or overclocking configurations applied

Firmware updates are evaluated periodically based on stability and compatibility requirements.



## Baseline Software State

The system is maintained in a clean baseline state:
- No unnecessary startup applications
- Minimal background services enabled
- Configuration optimized for baseline reliability, performance and maintainability

This version supports future troubleshooting, benchmarking, and change tracking.



## Summary

This software configuration establishes a stable, documented Windows 11 endpoint suitable for:
- Daily operation
- Troubleshooting and diagnostics
- Performance validation
- Ongoing maintenance and updates

All changes are made conservatively with stability as the primary objective.
