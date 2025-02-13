---
layout: page
title: 64C+256G软银单板计算机
description: 软银单板计算机 规格简介

order: 10
---

# 软银单板计算机 规格简介

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
|----------|:---------:|
| 尺寸     |  135mm*165mm<br>	背面限高2mm，正面限高4.5mm  |
| 连接器     |  688PIN阵列连接器，配高5mm   |
| cpu     | ARMv9.0-A架构，64 Neoverse N2核，3.0 GHz    |
| 性能指标      | SpecCPU2017 Int_Rate：560（单路）     |
| 内存     | 通道DDR5，最大256GByte，支持ECC    |
| 功耗     |  最小功耗：100W<br>典型功耗：200W<br>最大功耗：250W   |
| AI网络     | 8个物理以太网，支持GE或者XGE，支持RDMA， RoCE协议<br>–	Serdes连接PHY芯片，出电口<br>–	Serdes连光模块，出光纤口<br>–	Serdes通过背板互联<br>支持速率组合一<br>–	2 x 100GE(PFC/Normal)<br>–	2 x 50GE(PFC/Normal)<br>–	2 x 40GE(PFC/Normal)<br>–	2 x 25GE(PFC/Normal)<br>–	2 x 10GE(PFC/Normal)<br>–	2 x GE(Normal)<br>支持速率组合二<br>–	4 x 50GE(PFC/Normal)<br>–	4 x 25GE(PFC/Normal)<br>–	4 x 10GE(PFC/Normal)<br>–	4 x GE(Normal)<br>支持速率组合三<br>–	8 x 25GE(PFC/Normal)<br>–	8 x 10GE(PFC/Normal)<br>–	4 x GE(Normal)+4 x 25GE(Normal)/4 x 10GE(Normal) /4 x GE(Normal)    |
| PCIe     | <br>每个 DIE 支持 4 个 PCIe 控制器<br>支持 1x16，2x8，4x4 模式<br>最大速率支持 32GT/s<br>支持P-N极性翻转<br>最大 128 个 PCIe Gen5 lanes<br>兼容 CCIX2.0，CXL2.0 接口
    |
| PCIe 通道      | 最大 128 个 PCIe Gen5 lanes<br>- 每个 DIE 支持 4 个 PCIe 控制器<br>- 支持 1x16，2x8，4x4 模式<br>- 最大速率支持 32GT/s<br>- 兼容 CCIX2.0，CXL2.0 接     |
| 中断资源     | 全中断虚拟化（GICv4），支持 TrustZone    |
| IO 虚拟化     | SMMUv3.2    |
| <span>{% include icon.liquid id='awesome-cog' %} <b>环境适应性</b></span> |   |
|----------|:---------:|
| 工作结温范围      | 0°C-100°C     |
| 电源工作范围     | 8CPU：0.75～0.95V，DDR5：1.1V，PLL：1.2V，SerDes：0.8V/1.2V    |
| 封装     | 4890-pin 2.5D LGA，56.5mm x 77.5mm    |
| 功耗     | 300W TDP    |
| <span>{% include icon.liquid id='bootstrap-wrench' %} <b>技术特点</b></span> |   |
|----------|:---------:|
| 加速及硬件卸载      | 压缩/解压缩     |
| 加解密及认证     | Snow_3G，ES，ZUC，SM3，SM4，DES，3DES，SHA，MD5    |
| 深度学习加速引擎     | DLA（Deep Learning Accelerator）    |
| 数据搬移加速引擎     | DTE（Data Transformation Engine）    |
| 性能指标     | SpecCPU2017 Int_Rate：560（单路）    |
| <span>{% include icon.liquid id='cart-plus' %} <b>购买信息</b></span> |   |
|----------|:---------:|
| 产品型号      | 128 核（128  核，3.0G）<span><br>64 核  （64 核，3.0G）    |
{:.ui.collapsing.striped.table}