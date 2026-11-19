# microSD card test

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Mounts the card, writes and reads a text file, renames it, and unmounts the card.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable
- FAT32-formatted microSD test card

## How to Run

Open an ESP-IDF terminal in this directory using a version listed in the [repository README](../../../README.md).

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## Expected Result

The serial monitor reports card information and file operations.

## Troubleshooting

Use a test card. The example writes and may replace files named `hello.txt` and `foo.txt` in the card root.
