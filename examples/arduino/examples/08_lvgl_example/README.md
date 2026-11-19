# LVGL widgets

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Runs the LVGL widgets demo on the onboard touchscreen.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable

## How to Run

1. Install the Arduino-ESP32 board package version listed in the [repository README](../../../../README.md).
2. Set the sketchbook location to `examples/arduino/`, or copy the [bundled libraries](../../libraries/) into the sketchbook's `libraries` folder.
3. Select **ESP32S3 Dev Module** and apply the options in the [product configuration](../../../../.github/product.json).
4. Open the `.ino` file in this folder and upload.

## Expected Result

The display shows an interactive widgets interface. Tap or drag controls to try them.

## Troubleshooting

If the compiler cannot find `lv_demo_widgets`, use the bundled LVGL library with its demo sources.
