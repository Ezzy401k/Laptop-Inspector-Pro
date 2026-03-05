# Laptop Inspector Pro

**Laptop Inspector Pro** is a high-performance system utility designed for deep hardware analysis. Featuring a sleek, cyberpunk-inspired UI, it identifies CPU generations (Intel/AMD Zen), GPU specs, and RAM health with precision. Built for portability as a single-file EXE, it requires Admin rights to pull real-time sensor data from your hardware.

---

## Features

* **Deep CPU Analysis:** Accurately detects Intel generations (e.g., 8th Gen vs. 12th Gen) and AMD Zen architectures (Zen 2, Zen 3, Zen 4).
* **GPU & VRAM Insights:** Pulls manufacturer data, driver versions, and power limits.
* **Memory Diagnostics:** Scans RAM slots for part numbers, speeds, and manufacturers.
* **Storage Health:** Monitors drive lifecycle, media types (SSD/NVMe), and health status.
* **Cyberpunk UI:** High-contrast neon-green aesthetic built with WPF for a modern "hacker" feel.
* **Portable EXE:** Self-contained executable—no .NET installation required on the target machine.

---

## Installation & Usage

Since this is a **Single-File Executable**, no installation is necessary.

1. Download `LaptopInspector.exe` from the latest release.
2. **Run as Administrator:** (Required to access hardware sensors via `LibreHardwareMonitor`).
3. The app will instantly scan your system and display the results.

---

## Technical Stack

* **Framework:** .NET 8.0 (WPF)
* **Libraries:** * `LibreHardwareMonitorLib`: For low-level sensor access.
* `System.Management`: For WMI hardware querying.


* **Deployment:** Self-contained, Single-File Publish (`win-x64`).

---

## Requirements

* **OS:** Windows 10 or Windows 11 (64-bit).
* **Privileges:** Administrator access is mandatory for hardware sensor reading.

---
