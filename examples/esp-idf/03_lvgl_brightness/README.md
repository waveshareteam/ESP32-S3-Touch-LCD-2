# Touch-controlled backlight

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Connects an LVGL slider to the LCD backlight's PWM control.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable

## How to Run

Open an ESP-IDF terminal in this directory using a version listed in the [repository README](../../../README.md).

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## Expected Result

Drag the slider to change the displayed percentage and the backlight level.

## Troubleshooting

None yet.
