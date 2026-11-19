# QMI8658 readings on the LCD

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Reads the board's QMI8658 accelerometer and gyroscope and displays the readings with LVGL.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable

## How to Run

Open an ESP-IDF terminal in this directory using a version listed in the [repository README](../../../README.md).

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## Expected Result

Move or tilt the board and watch the six axis readings change on the LCD.

## Troubleshooting

None yet.
