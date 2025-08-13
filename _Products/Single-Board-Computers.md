---
layout: page
title: 64核400G模块
description: 软银单板计算机 规格简介

order: 10
---

# 软银64核400G模块 规格简介

> “Single Board Computers (SBC)”指的是单板计算机，是一种将计算机的处理器、存储器、输入输出接口等主要功能部件集成在一块电路板上的计算机系统。军事、国防、航天、工业、网络、安全场景面临着严峻的挑战，对高效和高性能计算解决方案有着强烈的需求。单板计算机尤其适用于上述场景，因为在这些应用中，小巧、低功耗、高性能的设备是必不可少的。单板计算机行业内首款支持国密的64核、DDR5的SBC现已面世，欢迎订购。
{:.ui.info.message}

![sample image](cpu.jpg "展示图")

* 搭载高性能ARM v9处理器，64个 Neoverse N2 Core。
* 支持国密 SM 200G。
* 支持RDMA AI智算网络。
* 8组80bit DDR5（含ECC）、5200MT/s @1DPC，最大256GB。
* 128 个 PCIe Gen5 高速lanes高速，支持HCCS、PCIe、SAS、网络协议。

> ARM V9 模组技术规格

| 指标项 | 规格  |
|----------|---------|
| 尺寸     |  135mm*165mm<br>	背面限高2mm，正面限高4.5mm  |
| 连接器     |  688PIN阵列连接器，配高5mm   |
| cpu     | ARMv9.0-A架构，64 Neoverse N2核，3.0 GHz    |
| 性能指标      | SpecCPU2017 Int_Rate：560（单路）     |
| 内存     | 通道DDR5，最大256GByte，支持ECC    |
| 功耗     |  最小功耗：100W<br>典型功耗：200W<br>最大功耗：250W   |
| AI网络     | 8个物理以太网，支持GE或者XGE，支持RDMA， RoCE协议<br>–	Serdes连接PHY芯片，出电口<br>–	Serdes连光模块，出光纤口<br>–	Serdes通过背板互联<br>支持速率组合一<br>–	2 x 100GE(PFC/Normal)<br>–	2 x 50GE(PFC/Normal)<br>–	2 x 40GE(PFC/Normal)<br>–	2 x 25GE(PFC/Normal)<br>–	2 x 10GE(PFC/Normal)<br>–	2 x GE(Normal)<br>支持速率组合二<br>–	4 x 50GE(PFC/Normal)<br>–	4 x 25GE(PFC/Normal)<br>–	4 x 10GE(PFC/Normal)<br>–	4 x GE(Normal)<br>支持速率组合三<br>–	8 x 25GE(PFC/Normal)<br>–	8 x 10GE(PFC/Normal)<br>–	4 x GE(Normal)+4 x 25GE(Normal)/4 x 10GE(Normal) /4 x GE(Normal)    |
| PCIe     | <br>每个 DIE 支持 4 个 PCIe 控制器<br>支持 1x16，2x8，4x4 模式<br>最大速率支持 32GT/s<br>支持P-N极性翻转<br>最大 128 个 PCIe Gen5 lanes<br>兼容 CCIX2.0，CXL2.0 接口   |
| 存储    | 提供1个X8 SAS3.0控制器，向下兼容SAS2.0和SAS1.0<br>–	支持SAS 3.0，向下兼容SAS2.0 和SAS1.0<br>–	支持SATA3.0，向下兼容SATA2.0 和SATA1.0<br>SAS支持12G/6G/3G/1.5G 四种速率，SATA 支持6G/3G/1.5G 速率，同时可以实现速率的自协商<br>支持连接SAS Expander 扩展更多磁盘<br>提供1 个X2 SATA 控制器<br>–	支持SATA 3.0，向下兼容SATA 2.5<br>–	支持AHCI 1.3，向下兼容 AHCI 1.2<br>–	支持6G/3G/1.5G 速率自协商<br>–	支持直连两个SATA 盘<br>支持NOR Flash控制器（BIOS）支持单线、双线和四线模式，最大频率50MHz     |
| USB     |  `1*USB3.0+2*USB2.0`   |
| 串口     | `2*UART`（两线模式）   |
| 其他接口      | 	`6*I2C`（1个支持IPMB)<br>`2*MDIO`<br>`1*LPC`<br>`1*SGPIO`<br>`11*GPIO`<br>`1*JTAG`（可复用为GPIO）     |
| 管理维护    |  提供IMU管理单元<br>–	支持状态收集，平台健康监测<br>–	工作频率800MHz<br>–	支持BootRom安全启动<br>提供CPLD管理模块<br>–	支持看门狗，支持电压监测<br>–	支持CPU内部温度，板载温度监测<br>–	支持过温告警指示，错误指示等<br>–	支持带外升级固件  |
|  加速功能    | 集成多个硬件加速器，提供比软件方式更高的性能，同时降低PCU负载<br>支持ZIP 进行压缩和加压缩加速<br>支持加解密及认证引擎<br>数据搬移加速引擎<br>深度学习加速引擎    |
|  推荐工作环境    | 存储温度：25℃<br>工作温度：0℃~55℃<br>温度变化每小时小于20℃<br>相对湿度：40% RH~60% RH非凝结<br>湿度变化每小时小于20% RH   |
|   极限工作环境    | 存储温度：-40~125℃<br>相对湿度：5% RH~95% RH非凝结<br>最大节温：0℃~105℃   |
| 海拔    | ≤3050m，高出900m时，工作温度按照每300m降低1℃计算。   |
| 腐蚀性气体污染物    | 腐蚀产物厚度最大增长速率：<br>铜测试片：300 Å/月（满足ANSI/ISA-71.04-2013定义的气体腐蚀等级G1）<br>银测试片：200 Å/月    |
| 颗粒污染物    |	符合数据中心清洁标准ISO14664-1 Class8<br>机房无爆炸性、导电性、导磁性及腐蚀性尘埃   |
| 供电    |  12V±5%，最大20A<br>3.3V_STB (-1%+3%)，最大2A  |
{:.ui.collapsing.striped.table}
