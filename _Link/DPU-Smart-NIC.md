---
layout: page
title: 国产200G智能网卡
description: DPU Smart NIC

order: 3
---
# {{ page.title }}

#### 在数据中心和AI计算场景中，英伟达的ConnectX-7网卡现在真的是一卡难求，而且也是价格不菲。

![layouts](bluefield-connectx-7-2c50-d-2x.jpeg "onnectx-7"){:.ui.image}

> ConnectX-7网卡的核心参数如下：

|  <b>Spec</b> |  <b>说明</b> |
|----------|----------|
| 接口协议  |  支持 Ethernet 和 InfiniBand  |
| 网络端口  |  2 个端口，每个支持最高 200Gb/s，总带宽最高 400Gb/s  |
| 接口技术  |  NRZ (10G, 25G)、PAM4 (50G, 100G)  |
| 主机接口  |  PCIe Gen 5，最多支持 32 条通道（支持 x16 加扩展）  |
| 网卡形态  |  PCIe HHHL (half-height, half-length)  |
| 操作系统支持  |  Linux (RHEL、Ubuntu)、Windows、VMware ESXi、Kubernetes 等  |
{:.ui.collapsing.striped.table}

我们就推荐一个国产的替代卡，DPU-CX7PT网卡，ConnectX-7有的功能，DPU-CX7PT也基本都支持，不仅价格要便宜很多，而且国内拿货也非常方便。
{:.ui.success.message}

---

## 产品规格

![layouts](image2.png "DPU-CX7PT"){:.ui.image}

### DPU-CX7PT 网卡
    - 尺寸：半高半长
    - 网络接口：2x100GbE/2x200GbE
    - 主机接口：PCIe5.0X16

#### DPU-CX7PT 网卡支持 2x200G 网络接口，提供最大 400Gbps 网络吞吐量，时延<10us；支持 IPSEC/TLS，以及AES/SM4 算法和国密算法，大幅提升数据中心的安全性；支持高性能 RDMA，同时还开放了可编程拥塞控制算法平台，帮助客户根据业务类型设计和应用适合的拥塞控制算法，提升网络端到端可靠性。<br>DPU-CX7PT 网卡具有良好的兼容性，支持 Linux、CGSL、欧拉、龙蜥等操作系统，兼容 X86 及 ARM CPU。DPU-CX7PT 为标准 PCIe 插卡，适用于通用、智算服务器。DPU-CX7PT 网卡可广泛用于公有云、私有云、边缘云以及智算中心的云基础设施。在通用及在智算数据中心中， DPU-CX7PT 网卡供高性能 RDMA 网络能力，将 GPU 集群的算力发挥到极致。

## 关键性能

|  <b>IO 接口</b> |  <b>网络</b> | <b>安全</b> | <b>RDMA</b>  |
|----------|----------|----------|----------|
| SRIOV 512VF/2PF<br>(2x200GE)  |  吞吐量 400G<br>时延<10us | IPSEC<br>TLS <br>国密 SM |  QP 数量 512K<br>RDMA 转发性能 100Mpps<br>时延<5us |
{:.ui.collapsing.striped.table}

---

## 规格特性

| <b>型号名称</b> | <b>DPU-CX7PT</b> |
|----------|----------|
| 主要部件 |  软银DPU 1.0 ASIC |
| 尺寸 |  半高半长 |
|----------|----------|
| 网络接口 | 2x100GbE/2x200GbE |
| PCIe 接口 |  PCIe5.0X16 |
|----------|----------|
| 环境 | 存储温度：-40°C ～ +65°C<br>工作温度：5℃～35℃<br>存储湿度：5% RH～95% RH 非凝结<br>工作湿度：8% RH～90% RH 非凝结 |
|----------|----------|
| 功耗 | 26W |
{:.ui.collapsing.striped.table}

---

## 关键功能

| <b>IO 功能</b> | <b>网络功能</b> | <b>RDMA</b> | <b>安全加速</b> | <b>HPC</b> | <b>运维管理</b> |
|----------|----------|----------|----------|----------|----------|
| ▪ SRIOV 1kVF /8PF<br>▪ PF/VF 的流量统计<br>▪ 网口 Bonding | ▪ Checksum 卸载<br>▪ Segmentation 卸载<br>▪ Vlan 卸载<br>▪ QinQ 卸载<br>▪ 数据包头修改卸载<br>▪ Jumbo Frame<br>▪ GSO/GRO<br>▪ RSS 卸载<br>▪ QoS/HQoS<br>▪ 基础带宽和最大带宽<br>▪ 队列动态可配<br>▪ 限速<br>▪ 1588 时钟<br>▪ 组播模式<br>▪ 混杂模式 | ▪ READ/WRITE/SEND<br>▪ SRQ<br>▪ 设备端口包数量及状态统计<br>▪ QP 状态追踪<br>▪ 通信模式 RC<br>▪ 通信模式 UD<br>▪ 重传方式 GO-BACK-N<br>▪ PFC<br>▪ ECN<br>▪ DCQCN<br>▪ 自定义 RTT 算法<br>▪ PCC<br>▪ QOS | ▪ ACL<br>▪ IPSEC 卸载<br>▪ TLS | ▪ GPU Direct RDMA<br>▪ GPU Direct Storage | ▪ 支持网卡自检<br>▪ 支持网卡固件升级<br>▪ 支持预启动执行环境（PXE） |
{:.ui.collapsing.striped.table}
