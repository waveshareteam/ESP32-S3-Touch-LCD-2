# 在 LCD 上显示 QMI8658 数据

[English](README.md) | [简体中文](README_ZH.md)

## 功能

使用 FastIMU 读取板载六轴传感器，并通过 LVGL 显示读数。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线

## 怎么运行

1. 在开发板管理器中安装 [仓库首页](../../../../README_ZH.md) 所列版本的 Arduino-ESP32。
2. 将项目文件夹位置设为 `examples/arduino/`，或将 [随附的库](../../libraries/) 复制到项目文件夹下的 `libraries` 目录。
3. 选择 **ESP32S3 Dev Module**，并按 [产品配置](../../../../.github/product.json) 设置「工具」菜单。
4. 打开本目录中的 `.ino` 文件并上传。

## 预期现象

移动或倾斜开发板，观察 LCD 上三轴加速度和三轴角速度读数的变化。

## 常见问题

暂无。
