---
sort: 2
---

# 开发环境的搭建与配置

常用的开发环境及对比如下表：

|IDE|简介|优势|劣势|
|----------------------|------------------------------------------------------------|------------------------------------------------------|---------------------------------------|
|ArduinoIDE|Arduino官方IDE稳定版，部分代码与Arduino用法相同，如果有使用Arduino的经验，更加容易上手|跨平台集成编译、上传于一体，内置串口查看器、串口绘图器|没有代码补全、目录结构不是特别清晰|
|ArduinoIDE2.0|新版ArduinoIDE，界面符合现代IDE的标准，其余用法大致相同|同上|代码补全不完善、目录结构不是特别清晰|
|VSCode插件+ArduinoIDE|相当于使用VSCode对ArduinoIDE套壳，编译上传等操作全部由ArduinoIDE完成，而VSCode只负责充当编辑器的作用|集成编译、上传于一体|需要配合ArduinoIDE使用，目录结构不清晰|
|ESP-IDF|乐鑫ESP32官方开发框架|官方SDK，更加贴近底层，相比Arduino方式保真度高|上手难度较高、环境配置较复杂|
|PlatformIO(Arduino)|使用基于PlatformIO编写和编译Arduino程序|完善的代码补全|更新可能较慢、库函数版本落后|
|PlatformIO(ESP-IDF)|使用基于PlatformIO编写和编译ESP-IDF程序|官方SDK|更新可能较慢、库函数版本落后|

## 本教程使用的集成开发环境
本教程基于PlatformIO(Arduino)来对ESP32进行编程，整套工作流程方便快捷，同时又能借助Arduino强大的生态，直接使用其他开发者编写的库函数，大大减小了开发所花费的时间和精力。

## 开发环境的搭建与配置
### 1. 下载VSCode
打开[Visual Studio Code官网](https://code.visualstudio.com/)，点击Download按钮，根据您操作系统下载相应的软件，并安装。具体安装方法可以参考[这篇教程](https://blog.csdn.net/weixin_46245846/article/details/113793024)。
### 2. 安装PlatformIO扩展

### 3. 安装ESP32(Arduino)组件
