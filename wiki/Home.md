# bavariamatic-GmbH/zephyr — Fork Overview

This repository is a **bavariamatic fork** of the upstream
[Zephyr Project RTOS](https://github.com/zephyrproject-rtos/zephyr).

It is used to develop, evaluate, and publish drivers and other Zephyr-related
content before or instead of upstreaming to the main Zephyr tree.

---

## Driver & Component Status

The table below tracks every driver or component that has been added or
modified in this fork relative to upstream Zephyr.

| Driver / Component | Subsystem | Description | Status | Last Updated |
|---|---|---|:---:|---|
| [Microchip SmartFusion2 FPGA](SmartFusion2-Driver) | GPIO / SPI / UART | Driver support for Microchip SmartFusion2 FPGA devices | 🟡 In Progress | 2026-03-09 |

### Status Legend

| Badge | Meaning |
|:---:|---|
| 🔵 Planned | Work is scheduled but not yet started |
| 🟡 In Progress | Actively being developed |
| 🟢 Complete | Implementation finished and tested |
| 🔴 On Hold | Work paused; reason documented in the driver page |
| ⚫ Deprecated | No longer maintained in this fork |

---

## How to Contribute

Please open a Pull Request against the `main` branch of this repository.
Follow the upstream [Zephyr contribution guidelines](https://docs.zephyrproject.org/latest/contribute/index.html)
and make sure all CI checks pass before requesting a review.

---

## Upstream Zephyr

This fork tracks the upstream Zephyr `main` branch.
Upstream documentation is available at <https://docs.zephyrproject.org>.
