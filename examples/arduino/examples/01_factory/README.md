# Board diagnostics

[English](README.md) | [简体中文](README_ZH.md)

## What It Does

Uses the touchscreen to inspect system information, the QMI8658 IMU, the camera and Wi-Fi.

## Hardware Required

- ESP32-S3-Touch-LCD-2 development board and USB data cable
- OV5640 camera and 2.4 GHz Wi-Fi test network (for the corresponding checks)

## How to Run

1. Install the Arduino-ESP32 board package version listed in the [repository README](../../../../README.md).
2. Set the sketchbook location to `examples/arduino/`, or copy the [bundled libraries](../../libraries/) into the sketchbook's `libraries` folder.
3. Select **ESP32S3 Dev Module** and apply the options in the [product configuration](../../../../.github/product.json).
4. Open the `.ino` file in this folder and upload.

## Expected Result

Tap the System, QMI8658, Camera and WiFi tabs to switch views.

## Troubleshooting

For the Wi-Fi check, configure `sta_ssid` and `sta_pass` for a test network before uploading. The WiFi tab shows both values on screen.
