# microSD 卡测试

[English](README.md) | [简体中文](README_ZH.md)

## 功能

挂载存储卡，写入和读取文本文件、测试重命名，然后卸载存储卡。

## 硬件需求

- ESP32-S3-Touch-LCD-2 开发板和 USB 数据线
- 用于测试的 FAT32 格式 microSD 卡

## 怎么运行

使用 [仓库首页](../../../README_ZH.md) 所列版本的 ESP-IDF，在本目录中打开 ESP-IDF 终端。

```bash
idf.py set-target esp32s3
idf.py build flash monitor
```

## 预期现象

串口监视器会输出卡信息与文件操作结果。

## 常见问题

请使用测试卡。示例会在卡根目录写入文件，可能替换已有的 `hello.txt` 和 `foo.txt`。
