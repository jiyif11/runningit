---
layout: page
title: 专家诊疗系统（多模态智能体）
description: Expert diagnosis and treatment system

order: 2
---

# {{ page.title }}

<iframe
    src="https://chatbot.opendc.cn:8087/chatbot/a6jyHz3QPhC15TFk"
    style="width: 100%; height: 100%; min-height: 800px"
    frameborder="0"
    allow="microphone">  
</iframe>

## 面向医疗的多模态 AI 模型

### 功能与用途

> 专门为医学领域打造的模型，患者问诊摘要、病历三分、诊断建议、临床决策支持等。用于加速医学文本与图像类 AI 应用的开发。
{:.ui.info.message}

> 使用场景

1. 🖼 医学图像分类<br>

- 适用于：X 光、病理切片、眼底图像、皮肤病图像等；

2. 🔍 医学图像解读<br>

- 任务包括图像问答、图像报告生成；
- 能生成自然语言报告，回答“图像中发生了什么”；
- 强于同尺寸模型，但仍需专业适配以满足临床应用需求。

3. 📖 医学文本理解与临床推理<br>

- 适用于：患者问诊摘要、病历三分、诊断建议、临床决策支持等；
- 基线表现良好，适合作为构建智能问诊与摘要工具的底座。

<span><b>多模态模型</b></span><br>能处理图像与文本的组合任务。采用SigLIP图像编码器,针对医疗数据进行预训练,包括胸部X光片、皮肤科图像、眼科图像和病理切片等。
{:.ui.success.message}
