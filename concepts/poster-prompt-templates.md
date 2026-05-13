---
title: 海报设计提示词模板
created: 2026-05-12
updated: 2026-05-12
type: concept
tags: [text-to-image, prompt-engineering, method, tutorial]
sources: [raw/articles/gpt-image-2-guide.md]
---

# 海报设计提示词模板

## 海报万能公式
```
海报 = 主题概念 + 视觉风格 + 排版布局 + 色彩方案 + 文字元素 + 材质效果
```

海报与人像最大的差异：需要处理文字和排版。GPT Image 2 的文字渲染能力（>95%准确率）使其在海报场景具有独特优势。

## 四大热门海报类型

### 类型一：城市/旅游海报
核心挑战：用一张图传递一个城市的"灵魂"。方案：用视觉隐喻。

**模板**：
```
A striking [季节] city poster for [城市名] with a bold contemporary design.
On a clean [底色] textured background with large areas of negative space,
[核心视觉元素] sweeping across the composition in a dynamic curve,
gradually transforming into a dreamlike panorama of [城市名].
Inside this flowing composition are iconic elements: [地标1], [地标2],
[地标3], [地标4]. Neutral [色调] dominant palette with [强调色] accents.
Modern typography for "[城市名]" in clean sans-serif styling.
High detail, screen print texture.
```

**完整案例 - 波士顿海报（@BubbleBrain Poster Case 1）**：
```
A striking autumn city poster for Boston with a bold contemporary design.
On a clean muted ivory textured paper background with large areas of negative space,
the Charles River sweeping across the composition like a watercolor ribbon curling gracefully,
gradually transforming into a dreamlike panorama of the city. Inside this flowing river
composition are iconic elements: the Charles River Esplanade, the iconic Boston Light lighthouse
standing proud, the iconic skyline of Back Bay with Prudential Tower and Hancock Building,
sailboats drifting on the water, autumn foliage along the banks with red and orange leaves.
A beautiful contemporary composition. Neutral warm beige and cream dominant palette with
autumn burnt orange and deep navy accent colors. Modern typography for "BOSTON" in a
clean slab-serif font styled boldly in all caps, balanced in the upper left area.
High detail, screen print texture.
```

### 类型二：产品广告海报
关键：让产品成为绝对主角，用光线和材质让它"值钱"。

**模板**：
```
Minimalist product poster, [产品名] centered on [背景] background.
Dramatic single light source from [方向], [材质] texture with subtle
reflections. Product name "[品牌名]" in [字体] typography at [位置],
tagline "[广告语]" in smaller text below. Clean composition with ample
negative space. High-end commercial photography, 8K detail.
```

### 类型三：中式美学海报
精髓：留白。东方美学的核心不是"填满画面"，而是"让空白说话"。

**模板**：
```
New Chinese style minimalist poster, S-curve composition flowing from
top-right to bottom-left. [主体] at the focal point of the curve.
Rice paper texture background, ink wash [元素] along the curve,
large negative space occupying 60% of the composition. Ancient Chinese
calligraphy aesthetics with modern graphic design principles.
Vertical Chinese typography, vermillion seal stamp.
Ink black and [点缀色] color palette.
```

### 类型四：电影海报
**模板**：
```
Cinematic movie poster, "[电影标题]" in bold [字体] typography centered.
[主角] in [姿势], dramatic [光线] lighting, [场景] background with
atmospheric [天气] effects. Supporting characters silhouetted in background.
Credits block at bottom. [色调] color grading, vintage film texture.
27x40 poster ratio.
```

## 海报文字渲染最佳实践

1. **引号包裹**：将文字用引号标出，如 `"SUMMER COLLECTION"`
2. **逐字拼出**：复杂品牌名逐字母拼：`S-U-M-M-E-R`
3. **指定排版**：字体风格（sans-serif/serif/handwritten）、大小、颜色和位置
4. **添加约束**：补充 `verbatim, no extra characters, no substitutions`
5. **限制文字量**：文字越多越易出错，建议分区域指定

## 相关页面
- [[提示词六维度万能公式]] — 基础方法论
- [[GPT Image 2]] — 适用模型
- [[人像摄影提示词模板]]
- [[UI与社交媒体截图提示词模板]]

## 参考文献
- [GPT Image 2 创作实战指南，第 6 章](../raw/articles/gpt-image-2-guide.md)
