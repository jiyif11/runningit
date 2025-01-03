---
layout: page
title: 总览
description: Programming switch chip

order: 1
---
# {{ page.title }}

> 软银可编程交换芯片是软银信息科技南京有限公司自主研发的 2.4T 可编程交换芯片。国
产无缝替代 intel 公司的 barefoot P4 可编程交换芯片。具有业内领先的网络性能，先进
制程，可编程，高带宽，可扩展，IO 丰富等特点，为企业级应用及数据中心提供出色的基
础设施支撑，可针对云计算，云原生，大数据，大规模计算，云游戏等应用场景提供出色
的总体拥有成本（TCO），轻松应对计算密集型工作负载.
{:.ui.info.message}

## 技术规格

| <span>{% include icon.liquid id='cpu' %} <b>技术规格</b></span> |   |
|----------|:---------:|
| 关键技术     | 支持  2.4T@128B  线速能力<br>支持 2~4 层业务报文的解析和转发处理能力;能根据新增业务场景识别;4层及更深层次的报文内容，并正确进行处理和转发<br>支持多播报文复制<br>支持流量管理和层次化调度控制<br>支持完善的`OAM`保护倒换和`1588`时钟同步功能    |
| <span>{% include icon.liquid id='cpu' %} <b>处理带宽</b></span> |   |
|----------|:---------:|
| 单芯片支持双向  2.8Tbps  以太接人       |      |
| 支持包长范围为  64 Bytes~12KBytes      |     |
| <span>{% include icon.liquid id='memory' %} <b>网络接口</b></span> |   |
|----------|:---------:|
| 100  对  SerDes，其中 96 对用于网络接口，4 对用于侧挂，96 对 Serdes  最高均支持  53.125Gbps      |      |
| <span>{% include icon.liquid id='awesome-cog' %} <b>OAM 性能 </b></span> |   |
|----------|:---------:|
| 工作结温范围      | 0°C-100°C     |
| 电源工作范围     | 8CPU：0.75～0.95V，DDR5：1.1V，PLL：1.2V，SerDes：0.8V/1.2V    |
| 封装     | 4890-pin 2.5D LGA，56.5mm x 77.5mm    |
| 功耗     | 300W TDP    |
| <span>{% include icon.liquid id='bootstrap-wrench' %} <b>OAM 性能</b></span> |   |
|----------|:---------:|
| 支持以太网  OA      |     |
| 支持  MPLS-TP OAM      |     |
| 支持  BFD     |     |
| 支持侧挂  FPGA  扩展  OAM  功能     |     |
| <span>{% include icon.liquid id='cart-plus' %} <b>保护倒换性能</b></span> |   |
|----------|:---------:|
| 支持  12K  保护组       |     |
| 支持线性和环网保护       |     |
| 支持硬件快速切换       |     |
| 支持下一跳分       |     |
| 支持分层保护       |     |
| 支持静态均衡  `LAG`  或  `ECMP`  组       |     |
| <span>{% include icon.liquid id='awesome-cog' %} <b>TM 性能</b></span> |   |
|----------|:---------:|
| 支持  128k  队列       |     |
| 支持整形范围为  0/64kbps~400Gbps       |     |
| 支持  CIR/PIR  的颗粒度最小为  16kbps，最大为  2Mbps       |     |
| 支持  CBS/PBS  的颗粒度为最小  256B，最大为  32KB       |     |
| 支持  128k  队列的  WRED  拥塞策略       |     |
| 最大支持 3 组 DDR4/DDR5 缓存报文，支持外挂 TM       |     |
{:.ui.collapsing.striped.table}