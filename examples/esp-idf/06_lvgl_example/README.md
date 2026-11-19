# LVGL widgets

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Runs the LVGL widgets demo using the board's display and touch input.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable

## How to Run

Open an ESP-IDF terminal in this directory using a version listed in the [repository README](../../../README.md).

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## Expected Result

The display shows an interactive widgets interface. Tap or drag controls to try them.

## Troubleshooting

None yet.
