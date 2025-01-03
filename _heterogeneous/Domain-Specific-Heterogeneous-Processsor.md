---
layout: page
title: 总览
description: Domain Specific Heterogeneous Processsor

order: 1
---

# {{ page.title }}

> 软银 ARM 多核处理器是软银信息科技南京有限公司自主研发的基于  ARMv9.0-A  架构
的领域定制异构处理器（Domain Specific Heterogeneous Processsor），具有业内领先
的计算性能，高核数，高主频，高带宽，高算力，IO 丰富等特点，为企业级应用及数据中
心提供出色的基础设施支撑，可针对云计算，云原生，大数据，大规模计算，云游戏等应
用场景提供出色的总体拥有成本（TCO），轻松应对计算密集型工作负载.
{:.ui.info.message}

## 技术规格

| <span>{% include icon.liquid id='cpu' %} <b>计算单元</b></span> |   |
|----------|:---------:|
| 架构     | ARMv9.0-A    |
| 平台     | Neoverse N2    |
| 最大核心数     | 128    |
| 最大基频     | 3.0GHz    |
| L1-Cache     | 64KB L1-I Cache/Core,64 L1-D Cache/Core    |
| L2-Cache     | 1MB/Core    |
| L2-Cache     | 最大 128M    |
| <span>{% include icon.liquid id='awesome-television' %} <b>系统资源</b></span> |   |
|----------|:---------:|
| 内存类型      | DDR5 80-bit ECC RDIMM     |
| 最大内存通道数     | 8    |
| 最大速率     | 5200MT/s @1DPC，4800MT/s @2DPC    |
| 最大内存槽数     | 3.0GHz    |
| 最大容量     | 8TB    |
| <span>{% include icon.liquid id='memory' %} <b>存储单元</b></span> |   |
|----------|:---------:|
| PCIe 通道      | 最大 128 个 PCIe Gen5 lanes<br>* 每个 DIE 支持 4 个 PCIe 控制器<br>* 支持 1x16，2x8，4x4 模式<br>* 最大速率支持 32GT/s<br>* 兼容 CCIX2.0，CXL2.0 接     |
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
| 产品型号      | 128 核（128  核，3.0G）<br>64 核  （64 核，3.0G）    |
{:.ui.collapsing.striped.table}