# MiniMind-in-Depth 🌌

> 🔍 深入浅出，重构理解 —— 基于 [MiniMind](https://github.com/jingyaogong/minimind) 的 LLM 教程拆解系列  
> 🌱 从 tokenizer 到 MoE，从 pretrain 到 distillation，一步步构建属于你的大模型框架

---

本项目是基于开源项目 [jingyaogong/minimind](https://github.com/jingyaogong/minimind) [2025.4.26 最新版本]的深入学习与实战笔记，**致敬原作者的精彩工作！👏**

我在原有代码基础上，进行了**逐行源码解析**，特别补充了：

- 🔬 **细节讲解**：包括公式推导、实现逻辑、训练工程的隐藏细节。
- 🔁 **shape 流程图注释**：每一个模块都标明输入输出尺寸，帮助你直观理解数据流。
- 🧠 **从源码看架构**：不仅知道“怎么做”，更理解“为什么这么做”。

---

## 📚 教程目录

### 🌱 基础构建

| # | 标题 | 链接 |
|--|------|------|
| 1 | 如何从头训练 tokenizer | [查看文档](src/1-如何从头训练tokenizer.md) |
| 2 | 一行代码之差，模型性能提升背后的 RMSNorm 玄机 | [查看文档](src/2-一行代码之差，模型性能提升背后的RMSNorm玄机.md) |
| 3 | 原始 Transformer 的位置编码及其缺陷 | [查看文档](src/3-原始Transformer的位置编码及其缺陷.md) |
| 4 | 旋转位置编码原理与应用全解析 | [查看文档](src/4-旋转位置编码原理与应用全解析.md) |

### 🧱 架构进阶

| # | 标题 | 链接 |
|--|------|------|
| 5 | 魔改的注意力机制：效率优化大盘点 | [查看文档](src/5-魔改的注意力机制，细数当代LLM的效率优化手段.md) |
| 6 | 从稠密到稀疏：详解专家混合模型 MoE | [查看文档](src/6-从稠密到稀疏，详解专家混合模型MOE.md) |
| 7 | 像搭积木一样构建一个大模型 | [查看文档](src/7-像搭积木一样构建一个大模型.md) |

### 🧪 训练与调优

| # | 标题 | 链接 |
|--|------|------|
| 8 | LLM 预训练流程全解 | [查看文档](src/8-LLM预训练流程全解.md) |
| 9 | 指令微调详解：让大模型从“能说”变得“会听” | [查看文档](src/9-指令微调详解-让大模型从“能说”变得“会听”.md) |
| 10 | DPO：大模型对齐训练的新范式 | [查看文档](src/10-DPO-大模型对齐训练的新范式.md) |

### 🧰 模型优化与压缩

| # | 标题 | 链接 |
|--|------|------|
| 11 | LoRA：LLM 轻量化微调的利器 | [查看文档](src/11-LoRA-LLM轻量化微调的利器.md) |
| 12 | 从白盒到黑盒：全面掌握大模型蒸馏技术 | [查看文档](src/12-从白盒到黑盒，全面掌握大模型蒸馏技术.md) |

---


## ❤️ 鸣谢与致敬
本项目基于 jingyaogong/minimind 的源码实现，在此向原作者表示衷心感谢。
如果你希望“读懂一个完整的大模型”，而不仅是“跑通它”，希望这个项目可以帮到你。
