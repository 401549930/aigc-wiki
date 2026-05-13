---
title: 提示词六维度万能公式
created: 2026-05-12
updated: 2026-05-12
type: concept
tags: [text-to-image, prompt-engineering, method]
sources: [raw/articles/gpt-image-2-guide.md]
---

# 提示词六维度万能公式

## 公式

```
提示词 = 主体 + 动作 + 场景 + 光线 + 风格 + 质量
```

这是 GPT Image 2 提示词工程的核心方法论，由 EvoLinkAI 社区沉淀，覆盖一张图片的全部核心要素。适用于人像、海报、产品图、UI 截图等所有场景。

## 六维度详解

### 维度一：主体（Subject）
画面的核心元素。描述要像给一个没见过的人描述长相一样具体。

**要素清单**：年龄 / 性别 / 民族 / 面部特征 / 发型 / 体型 / 材质（物品）

❌ 模糊：`一个漂亮的女孩`
✅ 精确：`20岁出头的东亚女孩，杏仁形的狐狸眼，高挺的鼻梁，V型下颌线，冷色调象牙瓷肌`

### 维度二：动作/姿态（Action/Pose）
画面的叙事感来源。三个层次：整体姿态 → 身体各部分 → 微动态。

✅ `慵懒地倚靠在便利店的玻璃门上，身体微弓，一腿弯曲、脚踩在门框上，另一腿直立`

### 维度三：场景（Scene）
故事发生的"舞台"。四个层次：地点类型 → 时间线索 → 环境细节 → 氛围暗示。

✅ `深夜的东京街头，霓虹灯闪烁，湿润的柏油路面反射着粉蓝色的灯光`

### 维度四：光线（Lighting）
影响画面质量最关键的维度（占 80% 以上）。三要素：光源类型、光线方向、光线质感。

**五种经典光线组合**：

| 光线类型 | 关键词 | 效果 |
|----------|--------|------|
| 霓虹混合光 | fluorescent + neon glow | 都市街头感、冷暖对比 |
| 柔光窗光 | soft diffused window light | 日系温柔感、自然通透 |
| 机顶直闪 | harsh on-camera flash | Y2K复古感、高对比 |
| 暖色环境光 | soft ambient lantern light | 和风温暖感、氛围浓郁 |
| 强对比轮廓光 | silhouette lighting, deep shadow | 电影质感、戏剧冲突 |

### 维度五：风格（Style）
图片的整体"调性"。三种描述方式：

1. **指定媒介/相机**：`35mm film photography, Kodak Portra 400`
2. **指定艺术流派**：`cyberpunk, Chinese ink wash painting`
3. **指定导演风格**：`Wes Anderson style, Wong Kar-wai style`

### 维度六：质量/约束（Quality/Constraints）
正向质量 + 负向排除词。

正向：`ultra-realistic, photorealistic, high detail, 8K resolution`
负向：`no watermark, no plastic skin, no extra text, no blur`

## 最佳长度
50-200 词，太短信息不足，太长可能产生指令冲突。

## 语言建议
核心描述用英文（摄影术语、风格名），中文内容（海报文字、UI文案）用中文。

## 人像七层模型（场景细化版）
```
[相机/媒介] → [光线环境] → [人物五官] → [服装造型] → [姿势动作] → [表情眼神] → [画质排除词]
```

## C.L.E.A.R.框架（进阶版）
详见 [[C.L.E.A.R.框架]]

## 新手十大常见错误
1. 提示词太短（<20 词）
2. 堆砌模糊赞美词（stunning/beautiful）
3. 忘记光线描述
4. 不加排除词
5. 一次提出太多修改（应每轮只改一个变量）
6. 该用英文时用了中文
7. 不指定画面比例
8. 忽视构图和镜头描述
9. 风格词堆砌且互相矛盾
10. 编辑时不指定保留项

## 相关页面
- [[GPT Image 2]] - 适用此提示词方法的模型
- [[自回归图像生成]] - 底层架构
- [[C.L.E.A.R.框架]] - 进阶提示词方法论

## 参考文献
- [GPT Image 2 创作实战指南，第 2 章](../raw/articles/gpt-image-2-guide.md)
