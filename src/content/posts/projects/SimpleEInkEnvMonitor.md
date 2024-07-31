---
title: 小气象喵温湿度监测仪
published: 2024-07-31
description: ''
image: './SimpleEInkEnvMonitor.jpg'
tags: ['Hardware']
category: 'Projects'
draft: false 
---

![SimpleEInkEnvMonitor](https://image.lceda.cn/pullimage/K0EeVsrXQP3DfGwQLachQURisxiBrE7BQpEHVpgk.png)


欢迎来到SimpleEInkEnvMonitor项目的介绍！这个项目是一个基于ESP32和e-ink屏幕的环境监测器，专门设计用于测量温度和湿度。

::github{repo="MeowKJ/SimpleEInkEnvMonitor"}

## 项目背景

SimpleEInkEnvMonitor是来自立创EDA温湿度传感器训练营，要求使用盛思锐传感器完成一个温湿度检测的小项目。

## 主要特点

- **ESP32C3微控制器**：提供稳定的性能和Wi-Fi连接能力。
- **e-ink屏幕**：低功耗、高对比度，适合长时间显示数据。
- **温度和湿度传感器**：采用盛思锐SHT40数字传感器，精确测量环境参数。

## 软件架构

项目的软件部分采用PlatformIO框架和Arduino核心库进行开发，墨水屏使用GxEPD2库。

## 开源许可

SimpleEInkEnvMonitor采用GPL3.0许可。
