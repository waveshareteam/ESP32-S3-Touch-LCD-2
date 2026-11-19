# microSD card test

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Uses the Arduino SD library over SPI to list directories, write and read files, and measure file I/O time.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable
- FAT32-formatted microSD test card

## How to Run

1. Install the Arduino-ESP32 board package version listed in the [repository README](../../../../README.md).
2. Set the sketchbook location to `examples/arduino/`, or copy the [bundled libraries](../../libraries/) into the sketchbook's `libraries` folder.
3. Select **ESP32S3 Dev Module** and apply the options in the [product configuration](../../../../.github/product.json).
4. Open the `.ino` file in this folder and upload.

## Expected Result

Open Serial Monitor at 115200 baud to see the card capacity, file-operation results and I/O timings.

## Troubleshooting

Use a test card. The sketch creates files and replaces any existing `foo.txt` in the card root.
