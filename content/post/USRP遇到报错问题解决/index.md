---
title: "USRP遇到报错问题解决"
date: 2022-01-08T12:52:45+08:00
draft: true
categories:
  - USRP
---
这个文章记录一下使用USRP过程中遇到的各种报错以及自己的解决方法，提供的解决方法仅供读者参考。

## usrp tx send error: sequence error in burst

我的解决方案是在设备管理器中查看你的网卡的设置，如果你仅需要在20M的带宽下发送和接收数据，关闭Jumbo Frame(巨形帧)。
