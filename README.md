# Grounding-DINO-Colab-Fixed

A working Grounding DINO Colab notebook with fixed installation dependencies and environment setup (Dec 2025).

## 🚀 Quick Start

点击下方图标即可在 Google Colab 中直接打开并运行该实例：

[![Open In Colab](https://colab.research.google.com/drive/15hMm1fA5Dyo6mRmQmFwpYUN9-DI6ALxz?usp=sharing)]

## 🛠️ 项目说明

本项目修复了 Grounding DINO 官方示例在当前 Colab 环境下无法运行的问题，主要改进包括：
- **依赖修复**：解决了 `torch` 与 `cuda` 版本不匹配导致的编译失败。
- **环境配置**：优化了 `GroundingDINO` 的安装步骤，确保依赖库正确加载。
- **模型权重**：更新了权重下载链接及路径配置。

## 📝 使用指南

1. 点击上方的 **Open In Colab** 按钮。
2. 在 Colab 中确保运行格类型已设置为 **GPU** (推荐使用 T4 或以上)。
3. 按顺序运行所有代码单元格。

## 🔗 参考
- [IDEA-Research/GroundingDINO](https://github.com/IDEA-Research/GroundingDINO)
