# UCSD🔱 ECE285：视觉学习导论（2025 春季学期）

[English Version](README.md) | [中文版](README_CN.md)

欢迎来到 **ECE285 – Intro to Visual Learning** 课程仓库！
本仓库包含 4 次编程作业与 1 个期末创意项目，内容覆盖经典 CNN、语义分割、CAM 可视化以及神经风格迁移等视觉领域核心技术。


## 📚 作业一：NumPy 手写神经网络
- 纯 NumPy 实现两层全连接网络  
- 编写 **Linear / ReLU / Softmax / Cross-Entropy** 等模块  
- 强制向量化实现，培养数学与代码并重的思维  
- 需提交 4 个 Python 文件、2 个 Notebook

## 🖼️ 作业二：PyTorch 卷积神经网络
- 从张量计算 → `nn.Module` → `nn.Sequential` 逐级上手  
- 在 **CIFAR-100** 上训练多种 CNN，并手写 **ResNet-10**  
- 开放挑战：自定义网络结构刷新基准精度

## 🚦 作业三：语义分割 + CAM
- 实现 **FCN-32s / FCN-8s**，分别从零训练与微调  
- 集成 **CAM**，可视化类别关注区域  
- 兼顾定量指标与定性掩膜效果

## 🧪 作业四：前沿视觉挑战
- 自选主题（如 ViT、目标检测、自监督等）深入探索  
- 提交代码与简短报告，展示实验发现

## 🎨 期末项目：神经风格迁移
- 基于极简 **PyTorch Neural Style Transfer** 代码库  
- 系统实验风格/内容权重、TV loss 与不同初始化策略  
- 提供脚本与 Notebook，轻松生成艺术化作品