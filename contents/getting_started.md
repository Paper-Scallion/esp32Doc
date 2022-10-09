---
sort: 1
---

# 开始

## 关于 Arduino ESP32

欢迎来到Arduino ESP32中文支持文档！本文档基于[官方英文文档](https://docs.espressif.com/projects/arduino-esp32/en/latest/index.html)翻译而来，并加以译者的部分补充，通过阅读此文档，你可以对Arduino ESP32有更好的了解。

## 第一件事

```note
在开始之前，要特别感谢[乐鑫科技](https://www.espressif.com/)对本项目和社区的支持，并且欢迎大家为此项目做出贡献！
```

ESP32是一个由[乐鑫科技](https://www.espressif.com/)设计的2.4GHz Wi-fi和蓝牙SoC（片上系统）。

ESP32专为移动、可穿戴电子设备和物联网（IoT）应用而设计。它具有低功耗芯片所有最先进特性，包括细粒度时钟门控、多种功耗模式和动态功耗调节。例如，在低功耗物联网传感器集线器应用场景中，ESP32 会定时唤醒，并且仅在检测到指定条件时才被唤醒。用于最大限度地减少芯片功耗。

信号功率放大器的输出也是可调的，因此有助于在通信覆盖范围、数据传输速率和功耗之间达到最佳权衡。

ESP32拥有芯片或模组，来应用到您的项目当中。

## 支持的SoC's

| SoC      | 稳定版    | 开发版 | 数据手册 |
| -------  | --------  | --------  | --------  |
| ESP32    | ✅     | ✅    | [ESP32](https://www.espressif.com.cn/sites/default/files/documentation/esp32_datasheet_cn.pdf) |
| ESP32-S2 | ✅ | ✅ | [ESP32-S2](https://www.espressif.com.cn/sites/default/files/documentation/esp32-s2_datasheet_cn.pdf) |
| ESP32-C3 | ✅ | ✅ | [ESP32-C3](https://www.espressif.com.cn/sites/default/files/documentation/esp32-c3_datasheet_cn.pdf) |
| ESP32-S3 | ❌ | ✅ | [ESP32-S3](https://www.espressif.com.cn/sites/default/files/documentation/esp32-s3_datasheet_cn.pdf) |

查看 开发板 章节来获得关于ESP32开发板的更多详细信息。
