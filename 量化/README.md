# 量化

量化投资方向的学习资料与研究笔记。

## 经典文献拆解

| 文件 | 内容 | 参考 |
| --- | --- | --- |
| `Alpha101从零开始的深度拆解与通俗化研究报告.pdf` | 对 101 个公式化 Alpha 的逐条核对与九环节拆解，94 页。含 20 个基础概念、八类思想地图、生活化迁移与独立研究指南 | Zura Kakushadze, *101 Formulaic Alphas*, arXiv:1601.00991；Wilmott Magazine 2016(84): 72–80 |

原文（公开论文）：https://arxiv.org/abs/1601.00991

> 101 个公式的版权归 WorldQuant LLC；回测数据为 WorldQuant 专有数据（2010.01–2013.12）。
> 本目录内容仅供个人学习与研究，不构成投资建议。

## 自己动手复现

配套的工程实现见仓库 [`alpha-miner-framework`](https://github.com/12star12/alpha-miner-framework)：
在 WorldQuant BRAIN 上批量生成表达式、回测、落库，
并在本地做退化表达式识别、失败三分归因与相关性门槛。
