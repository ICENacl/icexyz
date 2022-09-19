---
title: "Windows10+GNURadio+USRP x310 环境搭建"
date: 2022-03-01T15:28:27+08:00
draft: true
categories:
  - USRP
  - GNURadio
---

## 主要内容

因为Matlab的USRP开发包有着诸多限制，因此现在考虑使用GNURadio的开发环境。本文主要记录一下配置过程中踩下的坑，供后来者借鉴。

## 坑1：Ettus官网的教程问题

本人在一开始借鉴的是官网的安装教程，参考这个[链接](https://kb.ettus.com/Building_and_Installing_the_USRP_Open_Source_Toolchain_(UHD_and_GNU_Radio)_on_Windows)，但是很不幸的是，这个里面有很多坑（fuck ettus!）。本人是在windows 10下进行配置的，这个教程里面需要你对UHD（USRP Hardware Driver）进行编译以及安装，但是在windows下其实不需要进行编译，官网有编译好的文件，可以直接下载进行安装，参考这个[链接](https://files.ettus.com/binaries/uhd/)。
