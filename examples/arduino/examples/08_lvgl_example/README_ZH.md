# LVGL 控件演示

[English](README.md) | [简体中文](README_ZH.md)

## 功能

在板载触摸屏上运行 LVGL 控件演示。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线

## 怎么运行

1. 在开发板管理器中安装 [仓库首页](../../../../README_ZH.md) 所列版本的 Arduino-ESP32。
2. 将项目文件夹位置设为 `examples/arduino/`，或将 [随附的库](../../libraries/) 复制到项目文件夹下的 `libraries` 目录。
3. 选择 **ESP32S3 Dev Module**，并按 [产品配置](../../../../.github/product.json) 设置「工具」菜单。
4. 打开本目录中的 `.ino` 文件并上传。

## 预期现象

屏幕显示可交互的控件界面，可点击或拖动其中的控件。

## 常见问题

如果编译器找不到 `lv_demo_widgets`，请使用仓库中带有演示源码的 LVGL 库。
