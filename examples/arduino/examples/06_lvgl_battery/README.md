# Battery voltage on the LCD

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Reads the board's battery sensing input and uses LVGL to show the raw ADC reading and estimated voltage.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable
- Compatible 3.7 V lithium battery

## How to Run

1. Install the Arduino-ESP32 board package version listed in the [repository README](../../../../README.md).
2. Set the sketchbook location to `examples/arduino/`, or copy the [bundled libraries](../../libraries/) into the sketchbook's `libraries` folder.
3. Select **ESP32S3 Dev Module** and apply the options in the [product configuration](../../../../.github/product.json).
4. Open the `.ino` file in this folder and upload.

## Expected Result

The LCD refreshes the ADC reading and voltage about once a second.

## Troubleshooting

None yet.
