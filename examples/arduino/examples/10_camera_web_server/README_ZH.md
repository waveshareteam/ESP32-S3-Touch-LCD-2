# 摄像头网页服务器

[English](README.md) | [简体中文](README_ZH.md)

## 功能

通过 Wi-Fi 将摄像头画面传输到浏览器。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线
- OV5640 摄像头、2.4 GHz Wi-Fi 测试网络及同网段的浏览器设备

## 怎么运行

1. 在开发板管理器中安装 [仓库首页](../../../../README_ZH.md) 所列版本的 Arduino-ESP32。
2. 将项目文件夹位置设为 `examples/arduino/`，或将 [随附的库](../../libraries/) 复制到项目文件夹下的 `libraries` 目录。
3. 选择 **ESP32S3 Dev Module**，并按 [产品配置](../../../../.github/product.json) 设置「工具」菜单。
4. 打开本目录中的 `.ino` 文件并上传。

## 预期现象

以 115200 波特率打开串口监视器，在浏览器中访问输出的地址并点击 **Start Stream**。

## 常见问题

上传前请将 `ssid` 和 `password` 改为测试网络的连接信息。若无法访问，请检查浏览器设备与开发板在该网络上能否互通。
