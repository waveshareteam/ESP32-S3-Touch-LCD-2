# 综合诊断

[English](README.md) | [简体中文](README_ZH.md)

## 功能

通过触摸屏查看系统信息、QMI8658 六轴传感器、摄像头和 Wi-Fi 状态。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线
- OV5640 摄像头和 2.4 GHz Wi-Fi 测试网络（用于对应的检查）

## 怎么运行

1. 在开发板管理器中安装 [仓库首页](../../../../README_ZH.md) 所列版本的 Arduino-ESP32。
2. 将项目文件夹位置设为 `examples/arduino/`，或将 [随附的库](../../libraries/) 复制到项目文件夹下的 `libraries` 目录。
3. 选择 **ESP32S3 Dev Module**，并按 [产品配置](../../../../.github/product.json) 设置「工具」菜单。
4. 打开本目录中的 `.ino` 文件并上传。

## 预期现象

点击 System、QMI8658、Camera 和 WiFi 标签切换页面。

## 常见问题

测试 Wi-Fi 前，请在上传前将 `sta_ssid` 和 `sta_pass` 配置为测试网络的连接信息。WiFi 页面会在屏幕上显示这两个值。
