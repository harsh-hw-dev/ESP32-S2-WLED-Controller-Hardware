# ESP32-S2 WLED Controller – Hardware Design

This repository contains the complete hardware design of a **USB-powered WLED controller** based on the **ESP32-S2** microcontroller.  
The board is designed for reliable Wi-Fi LED control applications with clean power delivery, proper RF layout, and USB-C connectivity.

---

## 🔧 Key Features

- **MCU:** ESP32-S2FH4 (native USB support)
- **Power Input:** USB Type-C
- **Regulation:** ME6211 3.3V LDO
- **Firmware Support:** WLED compatible
- **Wireless:** 2.4 GHz external antenna (ANT3216)
- **USB Data:** USB D+ / D− routing for flashing & communication
- **Level Shifting:** BSS138 MOSFET based logic level translation
- **Protection:** USB polyfuse on VBUS
- **Clocking:** External crystal oscillator
- **Design Focus:** EMI-aware layout and stable power integrity

---

## 📂 Repository Structure

USB-powered ESP32-S2 based WLED controller hardware design featuring USB-C, onboard 3.3V LDO, external antenna, and EMI-aware layout.
