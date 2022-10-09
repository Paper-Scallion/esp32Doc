---
sort: 1
---

# 开始

## 关于 Arduino ESP32

欢迎来到 Arduino ESP32 中文支持文档！本文档基于[官方英文文档](https://docs.espressif.com/projects/arduino-esp32/en/latest/index.html)翻译而来，并加以译者的部分补充，通过阅读此文档，你可以对 Arduino ESP32 有更好的了解。

## 第一件事

```note
在开始之前，要特别感谢[乐鑫科技](https://www.espressif.com/)对本项目和社区的支持，并且欢迎大家为此项目做出贡献！
```

ESP32 是一个由[乐鑫科技](https://www.espressif.com/)设计的2.4GHz Wi-fi和蓝牙SoC（片上系统）。

ESP32 专为移动、可穿戴电子设备和物联网（IoT）应用而设计。它具有低功耗芯片所有最先进特性，包括细粒度时钟门控、多种功耗模式和动态功耗调节。例如，在低功耗物联网传感器集线器应用场景中，ESP32 会定时唤醒，并且仅在检测到指定条件时才被唤醒。用于最大限度地减少芯片功耗。

信号功率放大器的输出也是可调的，因此有助于在通信覆盖范围、数据传输速率和功耗之间达到最佳权衡。

您可以使用 ESP32 芯片或模组，来应用到您的项目当中。

## 支持的SoC

| SoC      | 稳定版    | 开发版 | 数据手册 |
| -------  | --------  | --------  | --------  |
| ESP32    | ✅     | ✅    | [ESP32](https://www.espressif.com.cn/sites/default/files/documentation/esp32_datasheet_cn.pdf) |
| ESP32-S2 | ✅ | ✅ | [ESP32-S2](https://www.espressif.com.cn/sites/default/files/documentation/esp32-s2_datasheet_cn.pdf) |
| ESP32-C3 | ✅ | ✅ | [ESP32-C3](https://www.espressif.com.cn/sites/default/files/documentation/esp32-c3_datasheet_cn.pdf) |
| ESP32-S3 | ❌ | ✅ | [ESP32-S3](https://www.espressif.com.cn/sites/default/files/documentation/esp32-s3_datasheet_cn.pdf) |

查看 开发板 章节来获得关于 ESP32 开发板的更多详细信息。

## Arduino 核心参考

本文档基于 ESP32 构建，不会介绍常见的 Arduino API。要查看 Arduino API 的介绍，请考虑阅读[Arduino官方文档](https://www.arduino.cc/reference/en/)。

## 支持的操作系统

| ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_windows.png) | ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_linux.png) | ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_macos.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Windows                                                      | Linux                                                        | macOS                                                        |

## 支持的IDE

| ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_arduino.png) | ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_pio.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Arduino IDE                                                  | PlatformIO                                                   |

查看 安装指导 章节来获取关于 Arduino ESP32 安装的更多信息。
