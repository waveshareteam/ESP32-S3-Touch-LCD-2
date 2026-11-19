# 在 LCD 上显示电池电压

[English](README.md) | [简体中文](README_ZH.md)

## 功能

使用 ADC 和 LVGL 显示电池检测输入的原始读数和估算电压。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线
- 兼容的 3.7 V 锂电池

## 怎么运行

使用 [仓库首页](../../../README_ZH.md) 所列版本的 ESP-IDF，在本目录中打开 ESP-IDF 终端。

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## 预期现象

LCD 约每秒刷新一次 ADC 读数和电压。

## 常见问题

暂无。
