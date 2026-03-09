# Microchip SmartFusion2 FPGA — Driver Support

> **Status:** 🟡 In Progress  
> **Last Updated:** 2026-03-09  
> **Subsystem(s):** GPIO, SPI, UART  

---

## Overview

The [Microchip SmartFusion2](https://www.microchip.com/en-us/products/fpgas-and-plds/system-on-chip-fpgas/smartfusion2-fpgas)
is an intelligent mixed-signal FPGA SoC integrating a hard 166 MHz ARM® Cortex®-M3
processor with programmable fabric and advanced peripherals.

This page tracks the driver work done in this fork for SmartFusion2-based
hardware targets.

---

## Planned / Implemented Interfaces

| Interface | Driver Path | Status | Notes |
|---|---|:---:|---|
| GPIO | `drivers/gpio/` | 🔵 Planned | CoreGPIO soft-IP |
| SPI | `drivers/spi/` | 🔵 Planned | CoreSPI soft-IP |
| UART | `drivers/serial/` | 🔵 Planned | CoreUART soft-IP |

---

## References

- [SmartFusion2 datasheet](https://www.microchip.com/en-us/products/fpgas-and-plds/system-on-chip-fpgas/smartfusion2-fpgas)
- [Zephyr SPI driver API](https://docs.zephyrproject.org/latest/hardware/peripherals/spi.html)
- [Zephyr GPIO driver API](https://docs.zephyrproject.org/latest/hardware/peripherals/gpio.html)
- [Zephyr UART driver API](https://docs.zephyrproject.org/latest/hardware/peripherals/uart.html)

---

## Changelog

| Date | Author | Summary |
|---|---|---|
| 2026-03-09 | bavariamatic | Page created; driver work started |
