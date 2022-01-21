# STM32F401 Bootload

## 一、描述

这个bootload起初是为STM32F401RC设计的bootload，为的是用于为ZNP的设计的主板上，原程序是在IAR上进行编译的，现改造在使用Vscode进行编译下载，并且开源出来。

## 二、主要适配的功能

| 序号 | 功能                      | 相关宏 |
| ---- | ------------------------- | ------ |
| 1    | bootlaoad偏移地址设置     |        |
| 2    | 使用SD卡检测更新          |        |
| 3    | 使用U盘检测更新           |        |
| 4    | 开启/关闭LCD显示进度功能  |        |
| 5    | 开启/关闭UART DEBUG模式   |        |
| 6    | 开启/关闭BOOT Info显示    |        |
| 7    | 开启/关闭LCD Info显示     |        |
| 8    | 开启/关闭蜂鸣器声音       |        |
| 9    | 开启/禁用工厂模式出厂模式 |        |

## 三、该项目在进行中

....