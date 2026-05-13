# Wiki Schema — AIGC 图片视频生成

## Domain
此知识库专注于 AI 驱动的图片和视频生成领域，涵盖以下方向：
- **图像生成模型**：Stable Diffusion, DALL-E, Midjourney, FLUX, Imagen 等
- **视频生成模型**：Sora, Runway Gen, Pika, Kling, VASA-1 等
- **扩散模型理论与优化**：DDPM, DDIM, Consistency Models, Flow Matching 等
- **控制与引导**：ControlNet, IP-Adapter, T2I-Adapter, LoRA, Textual Inversion
- **编辑与修复**：Inpainting, Outpainting, Image-to-Image, 视频编辑
- **3D/Avatar 生成**：Instant NGP, Gaussian Splatting, DreamFusion, 数字人
- **评估与数据**：FID/CLIP Score 评测、数据集、安全合规
- **工具与应用**：ComfyUI, A1111, Diffusers, 商业平台

## Convention
- 文件名：小写、连字符、无空格（如 `stable-diffusion-v3.md`）
- 每个页面必须有 YAML frontmatter
- 使用 `[[wikilinks]]` 链接相关页面（每页至少 2 个出链）
- 更新页面时必须更新 `updated` 日期
- 新页面必须添加到 `index.md` 对应分区
- 所有操作必须记录到 `log.md`

## Frontmatter
```yaml
---
title: 页面标题
created: YYYY-MM-DD
updated: YYYY-MM-DD
type: entity | concept | comparison | query | paper | tool
tags: [从下方分类选取]
sources: [raw/articles/source-name.md]
---
```

## Tag Taxonomy

### 模型架构
- `diffusion` - 扩散模型 (DDPM/DDIM/SDE)
- `flow-matching` - 流匹配模型
- `transformer` - Transformer 架构
- `vae` - 变分自编码器 (VAE/VQ-VAE)
- `gan` - 生成对抗网络 (StyleGAN/BigGAN)
- `autoregressive` - 自回归生成 (DALL-E/Parti)
- `nerf` - NeRF 系列
- `gaussian-splatting` - 3D Gaussian Splatting
- `mamba` - Mamba/状态空间模型

### 图像生成
- `text-to-image` - 文生图
- `image-to-image` - 图生图
- `inpainting` - 图像修补
- `outpainting` - 图像扩展
- `super-resolution` - 超分辨率
- `personalization` - 个性化生成 (DreamBooth/LoRA)
- `controlnet` - 可控生成

### 视频生成
- `text-to-video` - 文生视频
- `image-to-video` - 图生视频
- `video-editing` - 视频编辑
- `video-motion` - 运动控制
- `long-video` - 长视频生成
- `temporal-consistency` - 时序一致性
- `video-diffusion` - 视频扩散模型

### 3D 与 Avatar
- `text-to-3d` - 文生 3D
- `image-to-3d` - 图生 3D
- `avatar` - 数字人/Avatar
- `3d-reconstruction` - 三维重建
- `human-modeling` - 人体建模
- `face-generation` - 人脸生成
- `motion-generation` - 动作生成

### 训练与优化
- `scheduling` - 采样调度 (DDIM/DPM-Solver)
- `guidance` - 引导方法 (CFG/Classifier Guidance)
- `distillation` - 蒸馏 (Consistency Models/LCM)
- `quantization` - 量化
- `finetuning` - 微调策略
- `data-augmentation` - 数据增强
- `efficient-inference` - 高效推理

### 评估与数据
- `evaluation` - 评测指标 (FID/CLIP/IS)
- `dataset` - 数据集
- `safety` - 安全合规 (NSFW/C2PA)
- `benchmark` - 基准评测
- `human-evaluation` - 人工评测

### 工具与框架
- `comfyui` - ComfyUI
- `diffusers` - HuggingFace Diffusers
- `a1111` - Automatic1111 WebUI
- `invokeai` - InvokeAI
- `kohya` - Kohya's GUI
- `sdnext` - SD.Next

### 公司与平台
- `openai` - OpenAI (DALL-E/Sora)
- `stability-ai` - Stability AI (SD系列)
- `midjourney` - Midjourney
- `runway` - Runway
- `meta` - Meta (Emu/Make-A-Video)
- `google` - Google (Imagen/VideoPoet)
- `black-forest-labs` - Black Forest Labs (FLUX)
- `kling` - 快手可灵
- `pika` - Pika Labs

### 内容类型
- `paper` - 论文笔记
- `method` - 方法详解
- `tool` - 工具/框架使用
- `comparison` - 对比分析
- `tutorial` - 教程指南
- `review` - 综述/趋势

## Page Thresholds
- **创建页面**：一个实体/概念在 2+ 来源中出现，或是某一来源的核心主题
- **并入现有页面**：来源中提及的内容已有对应页面
- **不创建页面**：仅出现一次的次要提及、无关领域的边缘话题
- **拆分页面**：超过 200 行的页面，拆分为子主题并互相链接
- **归档页面**：内容被完全取代时，移至 `_archive/` 并从 index.md 删除

## Entity Pages
每个重要实体一页，包括：
- 概述 / 核心功能
- 关键事实与日期
- 与其他实体的关系（[[wikilinks]]）
- 来源引用

## Concept Pages
每个概念一页，包括：
- 定义 / 原理解释
- 当前发展状态
- 开放问题或争议
- 相关概念（[[wikilinks]]）

## Comparison Pages
对比分析，包括：
- 对比对象与目的
- 对比维度（优先使用表格）
- 结论或综合分析
- 来源

## Update Policy
- 新信息与已有内容冲突时，优先采信更新时间更新的来源
- 确实存在矛盾的，标注两方观点及其时间与来源
- 在 frontmatter 标注 `contradictions: [page-name]`
- 在 lint 报告中标注，等待用户裁决
