# NetherSX2 Turnip Updated Builds

Custom NetherSX2 builds with **Turnip Vulkan drivers bundled directly into the APK**.

The goal of this project is simple: provide different APK builds with carefully selected Turnip drivers already integrated, so users don't need to manually download, install, or configure external drivers.

---

## What is different?

Instead of including multiple drivers and adding a driver selector inside the emulator, each build includes **one specific Vulkan driver**.

The Vulkan shim has been modified to load a single bundled driver:

```text
libvulkan_freedreno.so

# Available Builds:

WN Turnip Performance
A performance-oriented Turnip driver designed to support a wide range of Adreno GPUs.
Recommended for users looking for maximum performance.
Credits: https://github.com/WinNative-Emu/Drivers

Turnip 710 / 720 / 722
A specialized Turnip driver for:
Adreno 710
Adreno 720
Adreno 722
This build is intended for devices using these GPUs, which may require specific driver optimizations.
Credits: https://github.com/Vauzi-17/710

Turnip 8XX 
A build using StevenMXZ Turnip driver focused on newer high-end Adreno GPUs.
This build is intended primarily for supported Adreno 8xx devices.
Credits: https://github.com/StevenMXZ/Adreno-Tools-Drivers

Important
These builds bundle third-party Turnip/Mesa Vulkan drivers.
Driver credits belong to their respective developers and contributors.
This project does not claim ownership of the bundled drivers.

Disclaimer
This is an experimental community project.
Compatibility is not guaranteed and different builds may behave differently depending on the device.
Always keep your existing emulator installation and settings backed up before testing experimental builds

Other credits go to:
Trixarian and nckstwrt
