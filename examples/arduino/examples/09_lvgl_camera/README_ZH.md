# 在 LCD 上预览摄像头画面

[English](README.md) | [简体中文](README_ZH.md)

## 功能

采集摄像头图像，由 LVGL 图像控件显示在屏幕上。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线
- 连接至板载 24 针摄像头接口的 OV5640 摄像头

## 怎么运行

1. 在开发板管理器中安装 [仓库首页](../../../../README_ZH.md) 所列版本的 Arduino-ESP32。
2. 将项目文件夹位置设为 `examples/arduino/`，或将 [随附的库](../../libraries/) 复制到项目文件夹下的 `libraries` 目录。
3. 选择 **ESP32S3 Dev Module**，并按 [产品配置](../../../../.github/product.json) 设置「工具」菜单。
4. 打开本目录中的 `.ino` 文件并上传。

## 预期现象

摄像头初始化后，LCD 显示实时预览。

## 常见问题

若摄像头初始化失败，请断电后检查排线连接。
