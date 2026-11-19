# 在 LCD 上显示 QMI8658 数据

[English](README.md) | [简体中文](README_ZH.md)

## 功能

读取板载 QMI8658 加速度计和陀螺仪，并通过 LVGL 显示读数。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线

## 怎么运行

使用 [仓库首页](../../../README_ZH.md) 所列版本的 ESP-IDF，在本目录中打开 ESP-IDF 终端。

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## 预期现象

移动或倾斜开发板，观察 LCD 上六个轴的读数变化。

## 常见问题

暂无。
