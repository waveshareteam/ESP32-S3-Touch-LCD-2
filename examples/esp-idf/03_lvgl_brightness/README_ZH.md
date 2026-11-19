# 用触摸屏调节背光

[English](README.md) | [简体中文](README_ZH.md)

## 功能

将 LVGL 滑块连接到 LCD 背光的 PWM 控制。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线

## 怎么运行

使用 [仓库首页](../../../README_ZH.md) 所列版本的 ESP-IDF，在本目录中打开 ESP-IDF 终端。

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## 预期现象

拖动滑块，屏幕上的亮度百分比和背光亮度会随之变化。

## 常见问题

暂无。
