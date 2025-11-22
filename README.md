# YD-ESP32-S3 KiCad Assets

This repository contains open-source KiCad assets for the [YD-ESP32-S3](https://github.com/vcc-gnd/YD-ESP32-S3) module by VCC-GND Studio, popular on AliExpress due to its lower cost compared to the "original" Espressif's [ESP32-S3-DevKitC-1](https://docs.espressif.com/projects/esp-dev-kits/en/latest/esp32s3/esp32-s3-devkitc-1/index.html). 

It took me a good few hours to locate those in various places, fix errors and piece them together, so I thought I'd save you a hassle.

## Contents

| File | Description | Source and Credits|
|------|-------------|--------|
| [`YD-ESP32-S3.kicad_sym`](https://raw.githubusercontent.com/shkuznetsov/YD-ESP32-S3/refs/heads/main/YD-ESP32-S3.kicad_sym) | KiCad **symbol** | Me
| [`YD-ESP32-S3.kicad_mod`](https://raw.githubusercontent.com/shkuznetsov/YD-ESP32-S3/refs/heads/main/YD-ESP32-S3.kicad_mod) | KiCad **footprint** | Converted from an [Altium Designer file](https://github.com/vcc-gnd/YD-ESP32-S3/blob/main/5-public-YD-ESP32-S3-Hardware%20info/ESP32-S3-size-pcb-ad.PcbDoc) shared by the board manufacturer |
| [`YD-ESP32-S3.step`](https://raw.githubusercontent.com/shkuznetsov/YD-ESP32-S3/refs/heads/main/YD-ESP32-S3.step) | **3D model** in STEP format | Created by [David Scambell](https://grabcad.com/david.scambell-1), available at [GrabCAD](https://grabcad.com/library/yd-esp32-s3-1). See below for alignment values ↓↓↓

![Sample images](https://raw.githubusercontent.com/shkuznetsov/YD-ESP32-S3/refs/heads/main/images/sample.jpg)

## References & Additional Resources

![YD-ESP32-S3 Pin-out Diagram](https://raw.githubusercontent.com/vcc-gnd/YD-ESP32-S3/refs/heads/main/IMG/img11.jpg)
*Source: [VCC-GND Studio's GitHub](https://github.com/vcc-gnd/YD-ESP32-S3/blob/main/IMG/img11.jpg)*

- OEM's documentation (Chinese): https://github.com/vcc-gnd/YD-ESP32-S3
- High-resolution pinout and detailed board specs (Renzo Mischianti): https://mischianti.org/vcc-gnd-studio-yd-esp32-s3-devkitc-1-clone-high-resolution-pinout-and-specs/
- 3D model by [David Scambell](https://grabcad.com/david.scambell-1) at GrabCAD: https://grabcad.com/library/yd-esp32-s3-1

## Licence

These files are provided under the **MIT Licence**, unless the module manufacturer’s licensing requires otherwise. Please check and update if necessary.

## Disclaimer

These KiCad assets are provided as-is. Always verify dimensions, pinouts, and clearances against the official datasheet before manufacturing PCBs.