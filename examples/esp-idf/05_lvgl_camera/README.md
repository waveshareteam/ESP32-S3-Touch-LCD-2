# Camera preview on the LCD

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Captures camera frames in an ESP-IDF task and displays them with LVGL.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable
- OV5640 camera connected to the board's 24-pin camera connector

## How to Run

Open an ESP-IDF terminal in this directory using a version listed in the [repository README](../../../README.md).

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## Expected Result

A live camera preview appears on the LCD after the camera initializes.

## Troubleshooting

If the camera fails to initialize, disconnect power and check the ribbon cable connection.
