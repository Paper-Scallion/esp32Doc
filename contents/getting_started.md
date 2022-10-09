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

本文档只介绍 ESP32 所特有的API等内容，不会介绍常见的 Arduino API。要查看 Arduino API 的介绍，请考虑阅读[Arduino官方文档](https://www.arduino.cc/reference/en/)。

## 支持的操作系统

| ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_windows.png) | ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_linux.png) | ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_macos.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Windows                                                      | Linux                                                        | macOS                                                        |

## 支持的IDE

| ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_arduino.png) | ![](https://docs.espressif.com/projects/arduino-esp32/en/latest/_images/logo_pio.png) |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Arduino IDE                                                  | PlatformIO                                                   |

查看 安装指导 章节来获取关于 Arduino ESP32 安装的更多信息。

## 支持

这是一个开放并且受到 ESP32 社区支持的项目，如果有任何疑惑，可以向以下任何一个社区提问。

## 社区

Arduino 社区相当庞大，你可以在其中找到大量有价值的内容，如果需要的话，可以在以下社区查询相关资料或是提问。

[ESP32 Forum](https://esp32.com/) 乐鑫科技官方论坛
[ESP32 Forum - Arduino](https://esp32.com/viewforum.php?f=19) 乐鑫科技官方论坛 Arduino 板块
[ESP32 Forum - Hardware](https://esp32.com/viewforum.php?f=12) 乐鑫科技官方论坛硬件板块
[Gitter](https://gitter.im/espressif/arduino-esp32)
[Espressif MCUs (Discord)](https://discord.gg/nKxMTnkD)
[ESP32 on Reddit](https://www.reddit.com/r/esp32)

## 问题反馈

在提出新问题之前，请阅读以下内容：
请务必先搜索你要提出的问题，包括但不限于在搜索引擎、ESP32 论坛、GitHub Issues中等。可以很好地避免重复解答、浪费宝贵的资源。我们这里还提供故障排除指南，以便在遇见常见问题时节省您宝贵的时间。
有关提出新问题的更多详细内容，请参阅[反馈模板](https://github.com/espressif/arduino-esp32/blob/master/.github/ISSUE_TEMPLATE/Issue-report.yml)。
如果您有任何新想法，请参阅功能[请求模板](https://github.com/espressif/arduino-esp32/blob/master/.github/ISSUE_TEMPLATE/Feature-request.yml)。

## 第一步

以下是让 Arduino ESP32 支持运行的第一步。

要安装 Arduino-ESP32，请参阅安装指南中的对应部分。我们建议您使用开发板管理器来安装。

## 示例程序

将工具链安装到您的集成开发环境后，您将能够看到 ESP32 的所有[专用示例](https://github.com/espressif/arduino-esp32/tree/master/libraries)。这些示例位于示例菜单中或每个库的文件夹中。

## 数据手册

[ESP32](https://www.espressif.com.cn/sites/default/files/documentation/esp32_datasheet_cn.pdf)
[ESP32-S2](https://www.espressif.com.cn/sites/default/files/documentation/esp32-s2_datasheet_cn.pdf)
[ESP32-C3](https://www.espressif.com.cn/sites/default/files/documentation/esp32-c3_datasheet_cn.pdf)
[ESP32-S3](https://www.espressif.com.cn/sites/default/files/documentation/esp32-s3_datasheet_cn.pdf)
