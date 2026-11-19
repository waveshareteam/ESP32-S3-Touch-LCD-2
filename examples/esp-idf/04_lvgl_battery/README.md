# Battery voltage on the LCD

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Uses the ADC and LVGL to show the raw battery sensing reading and estimated voltage.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable
- Compatible 3.7 V lithium battery

## How to Run

Open an ESP-IDF terminal in this directory using a version listed in the [repository README](../../../README.md).

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## Expected Result

The LCD refreshes the ADC reading and voltage about once a second.

## Troubleshooting

None yet.
