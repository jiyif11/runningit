---
layout: page
title: DPU智能网卡
description: DPU Smart NIC

order: 3
---
# {{ page.title }}

> 5G、人工智能、云计算等业务快速发展，对数据中心网络带宽、时延、转发速率提出更高的要求。推出基于自主研发定海 1.0 ASIC芯片的 NX 系列标卡，提供高带宽、低时延，高转发，高性价比的网络解决方案。
NX 系列标卡全面提升网络性能，实现 100Mpps 网络转发，最大 `400Gbps` 网络吞吐量，`时延<10us`；支持 IPSEC/TLS，以及 AES/SM4 算法和国密算法，大幅提升数据中心的安全性；支持高性能 RDMA，通过自研可编程拥塞控制算法平台，帮助客户根据业务类型设计和应用适合的拥塞控制算法，提升网络端到端可靠性。NX 系列标卡可提供 `25G/100G/200G` 多种规格，满足大中小网络规模需求。 NX 系列标卡具有良好的兼容性，支持 Linux、CGSL、欧拉、龙蜥等操作系统，兼容 X86 及 ARM CPU。NX 系列标卡为标准 PCIe 插卡，适用于通用服务器。
NX 标卡可广泛用于公有云、私有云、边缘云以及智算中心的云基础设施。在通用及在智算数据中心中，NX 标卡提供高性能 RDMA 网络能力，将 GPU 集群的算力发挥到极致。
{:.ui.info.message}

## 产品规格

![layouts](image1.png "NX E310"){:.ui.image}

### NX E310 网卡
    - 尺寸：半高半长
    - 网络接口：2x25GbE
    - 主机接口：PCIe4.0X16

![layouts](image2.png "NX E312"){:.ui.image}

### NX E312 网卡
    - 尺寸：半高半长
    - 网络接口：2x100GbE/2x200GbE
    - 主机接口：PCIe5.0X16


## 关键性能

|  <b>IO 接口</b> |  <b>网络</b> | <b>安全</b> | <b>RDMA</b>  |
|----------|----------|----------|----------|
| SRIOV 512VF/2PF  |  吞吐量 400G<br>DPDK 转发性能 100Mpps<br>时延<10us | IPSEC 200G<br>TLS 200Gb<r>国密 SM 200G |  QP 数量 512K<br>RDMA 转发性能 100Mpps  |
{:.ui.collapsing.striped.table}

---

## 规格特性

| <b>型号名称</b> | <b>NX E310</b> |    | <b>NX E312</b> |
|----------|----------|:----------:|----------|
| 主要部件 |    |  定海 1.0 ASIC |   |
| 尺寸 |    | 半高半长 | |
|----------|----------|----------|
| 网络接口 |  2x25GbE | |  2x100GbE/2x200GbE |
| PCIe 接口 |  PCIe4.0X16 | |  PCIe5.0X16 |
|----------|----------|:----------:|----------|
| 环境 |    | 存储温度：-40°C ～ +65°C<br>工作温度：5℃～35℃<br>存储湿度：5% RH～95% RH 非凝结<br>工作湿度：8% RH～90% RH 非凝结 |    |
|----------|----------|----------|----------|
| 功耗 | 21W |  | 26W |
{:.ui.collapsing.striped.table}

---

## 关键功能

| <b>IO 功能</b> | <b>网络功能</b> | <b>RDMA</b> | <b>安全加速</b> | <b>HPC</b> | <b>运维管理</b> |
|----------|----------|----------|----------|----------|----------|
| SRIOV<br>PF/VF 的流量统计<br>网口 Bonding | Checksum 卸载<br>egmentation 卸载<br>Vlan 卸载<br>QinQ 卸载<br>数据包头修改卸载<br>Jumbo Frame<br>GSO/GRO<br>RSS 卸载<br>QoS/HQoS<br>基础带宽和最大带宽<br>队列动态可配<br>限速1588 时钟<br>组播模式<br>混杂模式 | READ/WRITE/SEND<br>SRQ<br>设备端口包数量及状态统计<br>QP 状态追踪<br>通信模式 RC<br>通信模式 UD<br>重传方式 GO-BACK-N<br>PFC<br>ECN<br>DCQCN<br>自定义 RTT 算法<br>PCC<br>QOS | ACL<br>IPSEC 卸载<br>TLS | GPU Direct RDMA<br>PU Direct Storage | 支持网卡自检<br>支持网卡固件升级<br>支持预启动执行环境（PXE） |
{:.ui.collapsing.striped.table}
