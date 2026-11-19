# 在 LCD 上预览摄像头画面

[English](README.md) | [简体中文](README_ZH.md)

## 功能

在 ESP-IDF 任务中采集摄像头图像，并通过 LVGL 显示。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线
- 连接至板载 24 针摄像头接口的 OV5640 摄像头

## 怎么运行

使用 [仓库首页](../../../README_ZH.md) 所列版本的 ESP-IDF，在本目录中打开 ESP-IDF 终端。

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## 预期现象

摄像头初始化后，LCD 显示实时预览。

## 常见问题

若摄像头初始化失败，请断电后检查排线连接。
