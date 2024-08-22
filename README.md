# 华硕chromebox3 黑苹果OpenCore引导

## 配置
CPU：i7-8550u

Wifi：原装 Intel 网卡

内存：DDR4

硬盘：m2 NVME

## OC 与 kext 版本
* **OpenCore**: 1.0.1
* AppleALC: 1.9.1
* FakePCIID: 1.3.15
* HibernationFixup: 1.5.1
* IntelBluetoothFirmware: 2.4.0
* Lilu: 1.6.8
* RealtekRTL8111: 2.4.2
* VirtualSMC: 1.3.3
* WhateverGreen: 1.6.7
* itlwm: 2.3.0

## 说明

改自国光提供的 EFI 版本，升级了 opencore 版本
* 支持 MacOS 13.6.9  
* 支持原装 Intel 网卡

## 已知问题

* ✅ 已解决：boot 第二阶段卡 1 分钟八苹果（2K 显示器），等待1分钟后即可进入系统 -> 通过禁用FakePCIID可避免卡8苹果

* ❌ 新问题，HDMI显示器无法输出声音，只能通过蓝牙输出声音

