---
title: AIGC 图像生成系统学习计划
created: 2026-05-13
updated: 2026-05-13
type: learning-plan
tags: [aigc, gpt-image-2, prompt-engineering, image-generation, learning-plan, bilingual-prompts]
based_on:
  - index.md
  - GPT Image 2.md
  - concepts/prompt-formula-six-dimensions.md
  - concepts/clear-framework.md
  - concepts/portrait-prompt-templates.md
  - concepts/poster-prompt-templates.md
  - concepts/ui-prompt-templates.md
  - concepts/character-prompt-templates.md
  - concepts/ecommerce-prompt-templates.md
  - concepts/style-mixing-strategies.md
  - concepts/commercial-path.md
---

# AIGC 图像生成系统学习计划

> 依据当前 `aigc-wiki` 的知识结构定制：以 [[GPT Image 2]] 为核心工具，以 [[concepts/prompt-formula-six-dimensions.md|提示词六维度万能公式]] 为基础方法，以 [[concepts/clear-framework.md|C.L.E.A.R.框架]] 为进阶方法，覆盖人像、海报、UI截图、角色、电商产品图、风格混合与商业变现。

## 1. 学习目标

完成本计划后，你应该具备以下能力：

1. 理解 GPT Image 2 与扩散模型的差异，知道什么时候该利用其文字渲染、复杂指令遵循、对话式迭代和图像编辑能力。
2. 熟练使用“主体 + 动作/姿态 + 场景 + 光线 + 风格 + 质量/约束”的六维度提示词公式。
3. 建立自己的专业词汇库，能准确描述构图、光线、色调、镜头、胶片、质感和负面约束。
4. 能独立完成五类核心商业场景：人像摄影、海报设计、UI/社交截图、角色设定、电商产品图。
5. 掌握 C.L.E.A.R. 迭代法，能把一次性提示词升级为可复用模板。
6. 能完成一个 12-20 张图的作品集，并从中提炼出可售卖的服务、模板或课程雏形。

## 2. 中英文提示词对照学习指南

本计划中所有提示词示例均提供 **🇨🇳 中文** 和 **🇺🇸 English** 双版本，用于对照学习。

### 为什么需要双版本？

GPT Image 2 的训练数据以英文为主，中英文提示词在以下方面存在系统性差异：

| 维度       | 中文提示词倾向                | 英文提示词倾向                                    |
| -------- | ---------------------- | ------------------------------------------ |
| **文字渲染** | 中文文字准确率较低，但对中文排版风格理解更好 | 文字（含中文）准确率更高，排版遵循更稳定                       |
| **技术术语** | 借用英文术语或翻译术语，理解可能泛化     | 直接使用标准术语，模型识别度高                            |
| **美学风格** | "国风""留白""意境"等自带东方美学语境  | 描述更中性、更可控，但可能缺乏"灵魂"                        |
| **空间描述** | "左侧""右上角"有时不够精确        | "on the left""upper right"定位更稳定            |
| **抽象概念** | "高级感""氛围感"诠释空间大        | "premium""atmospheric"有更明确的视觉对应            |
| **排除约束** | "无水印""无变形"效果可能弱于英文     | "no watermark""no distortion"是训练常见模式，效果更可靠 |
| **对话迭代** | "保持不变"有时构图会偏移          | "keep the same"通常更稳定                       |

### 使用方法

1. **同一提示词两种语言各生成一次**，对比结果差异。
2. **记录哪些维度中文更好**（如意境、中式元素）和**哪些英文更好**（如文字、技术精度）。
3. **实践策略**：复杂场景可以混合使用——用英文写结构化部分（排除词、技术参数），用中文写意境部分（氛围、情绪、文化元素）。
4. 在练习记录中增加一列"语言选择策略"，逐步建立自己的最佳实践。

---

## 3. 建议周期

标准周期：8 周。

节奏安排：

- 每周 5 天学习与练习，每天 60-90 分钟。
- 每周 1 天作品整理与复盘，每次 90-120 分钟。
- 每周 1 天休息或自由探索。

压缩周期：4 周。

- 将每两周内容合并为一周。
- 每天学习 2-3 小时。
- 每周至少完成 2 个作品级练习。

## 4. 学习材料映射

| 模块 | 主要笔记 | 学习重点 |
| --- | --- | --- |
| 工具认知 | [[GPT Image 2]]、[自回归图像生成](concepts/autoregressive-image-generation.md) | 架构差异、能力边界、文字渲染、复杂指令 |
| 基础公式 | [提示词六维度万能公式](concepts/prompt-formula-six-dimensions.md) | 主体、动作、场景、光线、风格、质量约束 |
| 提示词工程 | [C.L.E.A.R.框架](concepts/clear-framework.md) | 语境、分层、排除、调整、精炼 |
| 人像场景 | [人像摄影提示词模板](concepts/portrait-prompt-templates.md) | 七层模型、布光、胶片、五官、风格 |
| 海报场景 | [海报设计提示词模板](concepts/poster-prompt-templates.md) | 海报公式、文字渲染、视觉层级 |
| UI场景 | [UI与社交媒体截图提示词模板](concepts/ui-prompt-templates.md) | 界面结构、平台真实感、分层描述 |
| 角色场景 | [角色设计提示词模板](concepts/character-prompt-templates.md) | IP还原、设定表、多角度转盘、表情包 |
| 电商场景 | [电商产品图提示词模板](concepts/ecommerce-prompt-templates.md) | 白底棚拍、场景图、广告图、材质描述 |
| 创意进阶 | [风格混合策略](concepts/style-mixing-strategies.md) | 介质+画风、时代+风格、文化跨界 |
| 商业落地 | [商业变现路径](concepts/commercial-path.md) | 服务路径、定价、版权伦理、知识库沉淀 |

## 5. 每日固定训练流程

每次练习都按这个闭环执行：

1. 读 1 个知识点：5-10 分钟。
2. 抄写并拆解 1 条优秀提示词：10 分钟。
3. 写 1 条自己的提示词：15-20 分钟。
4. 生成 1-3 张图：10-20 分钟。
5. 用 C.L.E.A.R. 做一轮修改：15 分钟。
6. 记录结果：提示词、图片、问题、下一版修改方向。

建议记录模板：

```markdown
## 练习记录：YYYY-MM-DD

- 练习主题：
- 使用知识点：
- 原始提示词：
- 生成结果观察：
- 问题：
- 使用 C.L.E.A.R. 的修改：
- 第二版提示词：
- 最终可复用经验：
```

## 6. 第 0 周：准备与基线测试

目标：知道自己的起点，建立作品与提示词管理方式。

### Day 1：建立学习档案

任务：

- 在 Obsidian 中建立三个文件夹：`learning/logs`、`learning/prompts`、`learning/portfolio`。
- 新建一篇 `AIGC学习日志.md`，用于记录每天练习。
- 选择一个主攻方向：人像、海报、UI、电商、角色，或先全量学习。

基线练习：

中文版：

```text
生成一张适合作为小红书封面的 AI 学习主题图片，画面要有科技感、清晰标题、干净排版。
```

English Version:

```text
Create a Xiaohongshu-style cover image on the topic of AI learning. The image should have a futuristic tech aesthetic, a clear headline, and clean layout.
```

> 📝 **对照提示**：中文版用"科技感"这样的抽象风格词，模型会自行诠释；英文版用"futuristic tech aesthetic"更具体。注意生成结果在风格理解上的差异。

提交物：

- 1 张基线图。
- 100 字自评：哪里好，哪里不符合预期。

### Day 2：自我诊断

按 1-5 分给自己评分：

| 能力 | 评分 | 判断标准 |
| --- | --- | --- |
| 能否清楚描述画面 |  | 是否能说出主体、场景、光线、风格 |
| 能否写出稳定提示词 |  | 结果是否接近预期 |
| 是否懂摄影/设计词汇 |  | 是否能使用镜头、构图、色调等词 |
| 是否会迭代优化 |  | 是否知道失败后该改哪里 |
| 是否能面向商业交付 |  | 是否知道交付物、规格、版权边界 |

## 7. 第 1 周：理解 GPT Image 2 与提示词底层逻辑

核心笔记：[[GPT Image 2]]、[[concepts/autoregressive-image-generation.md|自回归图像生成]]

本周目标：

- 理解 GPT Image 2 的强项：文字渲染、复杂排版、指令遵循、对话迭代、原生图像编辑。
- 学会区分“模糊愿望”和“可执行指令”。

### Day 1：工具认知

阅读：

- [[GPT Image 2]]
- [[concepts/autoregressive-image-generation.md|自回归图像生成]]

练习：同一主题三种清晰度。

主题：日落海边。

简单版 · Simple Version：

🇨🇳 中文：

```text
日落时分的海边，一个人在沙滩上散步。
```

🇺🇸 English:

```text
A person walking on the beach at sunset.
```

> 📝 中英文简版都很模糊，模型自由发挥空间大，结果随机性高。对比两者，观察模型对"日落海边"和"sunset beach"的理解是否有偏向。

进阶版 · Intermediate Version：

🇨🇳 中文：

```text
黄昏时分，一个人独自走在沙滩上，温暖的金色阳光洒下，远处是平静的海浪，氛围怀旧而宁静，35mm 胶片摄影风格。
```

🇺🇸 English:

```text
A person walking alone on a sandy beach at sunset, warm golden light, calm ocean waves in the background, nostalgic atmosphere, 35mm film photography.
```

> 📝 中文版用"黄昏""金色阳光""怀旧"等词；英文版用"sunset""golden light""nostalgic"。注意"怀旧"vs "nostalgic"在色彩倾向上的微妙差异。

专业版 · Professional Version：

🇨🇳 中文：

```text
35mm 胶片摄影，Kodak Portra 400 彩色胶片，自然胶片颗粒感。一个孤独的身影赤脚走在潮湿的沙滩边缘，从中远景的背面视角拍摄。黄金时刻的逆光在剪影周围形成温暖的轮廓光，长长的影子朝向镜头延伸。平静的蓝绿色海洋带着轻柔的泡沫，戏剧性的橙紫色日落天空点缀着散落的云朵。地平线位于画面上三分之一处。忧郁、沉思的氛围。16:9 宽银幕构图。无文字、无水印、无肢体变形。
```

🇺🇸 English:

```text
35mm film photography, Kodak Portra 400 color stock, natural film grain. A solitary figure walking barefoot along wet sand at the shoreline, seen from behind in a medium-long shot. Golden hour backlight creates a warm rim glow around the silhouette, long shadow stretching toward the camera. Calm turquoise ocean with gentle foam, dramatic orange and purple sunset sky with scattered clouds. Horizon line placed on the upper third. Melancholic, contemplative atmosphere. 16:9 widescreen composition. No text, no watermark, no distorted limbs.
```

> 📝 **对照提示**：专业版中英文都包含完整的六维度信息。注意中文版"蓝绿色海洋"可能被理解为青色或翠绿，而英文"turquoise ocean"更精确指向蓝绿色。"轮廓光"vs "rim glow"也值得关注——中文可能被诠释为更大面积的光晕。

输出：

- 3 张图。
- 对比 3 条提示词造成的画面差异。

### Day 2：复杂指令遵循

练习：同时给出 7 个约束。

🇨🇳 中文：

```text
为一个虚构咖啡品牌"MORNING CODE"创建一张方形海报。海报必须包含：画面中央一杯冰拿铁，左侧一台银色笔记本电脑，右侧一小盆绿植，晨光从左上方照射，干净的白色桌面背景，顶部标题文字"MORNING CODE"，杯子下方副标题"Coffee for focused makers"。极简现代杂志风格，柔和阴影，高端产品摄影。文字必须准确，不要多余字母，不要水印。
```

🇺🇸 English:

```text
Create a square poster for an imaginary coffee brand named "MORNING CODE". The poster must include: one glass cup of iced latte in the center, a silver laptop on the left, a small green plant on the right, morning sunlight from the upper left, clean white desk background, headline text "MORNING CODE" at the top, subtitle "Coffee for focused makers" below the cup. Minimal modern editorial style, soft shadows, high-end product photography. Text must be exact, no extra letters, no watermark.
```

> 📝 **对照提示**：多约束场景下，中文版可能在物体位置关系上更模糊（"左侧""右侧"的精确度取决于模型理解），英文版"on the left/on the right"通常空间定位更稳定。重点检查：品牌名拼写、物体位置、光线方向。

检查清单：

- 品牌名是否准确。
- 左右物体是否位置正确。
- 主副标题是否完整。
- 光线是否来自左上方。

### Day 3：文字渲染专项

练习：中文海报文字。

🇨🇳 中文提示词（生成中文文字海报）：

```text
一张现代中文活动海报，主题是「2026 夏季 AI 创作营」。主标题位于画面上方居中，必须逐字写出「2026 夏季 AI 创作营」。副标题位于标题下方：「用提示词完成你的第一套作品集」。画面主体是一张干净的工作桌，上面有平板电脑、手写笔、咖啡和色卡。明亮自然光，现代教育品牌视觉，留白充足，文字清晰可读，不要多余文字，不要水印。
```

🇺🇸 English Prompt (generating Chinese text in poster):

```text
A modern Chinese event poster for "2026 夏季 AI 创作营" (2026 Summer AI Creative Camp). Main title centered at the top, must read exactly "2026 夏季 AI 创作营" verbatim. Subtitle below: "用提示词完成你的第一套作品集". Main visual is a clean work desk with a tablet, stylus, coffee, and color swatches. Bright natural light, modern education brand visual, generous white space, Chinese text must be clear and legible, no extra text, no watermark.
```

> 📝 **对照提示**：这是一个关键实验——用中文提示词 vs 英文提示词生成**中文文字**。通常英文提示词生成中文文字的准确率更高（GPT Image 2 对英文指令的排版遵循更好），但中文提示词可能在"意境""留白"等美学把控上更自然。重点观察：文字是否正确、排版是否稳定。

迭代方向：

- 如果文字错：加入“verbatim, no extra characters, no substitutions”。
- 如果排版乱：明确主标题、副标题、主体图的位置。
- 如果信息过多：删掉次要物体。

### Day 4：对话式迭代

第一轮提示词 · Round 1：

🇨🇳 中文：

```text
生成一张竖版手机壁纸，主题是”深夜学习中的 AI 工作者”，画面中有一个人在电脑前写提示词，窗外是城市夜景，氛围安静、专注、略带未来感。
```

🇺🇸 English:

```text
Generate a vertical phone wallpaper on the theme “late-night AI worker studying”. A person sits at a computer writing prompts, city nightscape visible through the window. The mood is quiet, focused, with a subtle futuristic feel.
```

第二轮修改 · Round 2：

🇨🇳 中文：

```text
保持构图不变，把整体色调改得更温暖，屏幕上的光照亮人物脸部，桌面更整洁，不要赛博朋克感。
```

🇺🇸 English:

```text
Keep the composition the same, but make the overall color tone warmer. Screen light should illuminate the person's face, desk should be cleaner, no cyberpunk aesthetic.
```

第三轮修改 · Round 3：

🇨🇳 中文：

```text
增加一个小标题文字：”FOCUS MODE”，放在画面底部，字体简洁，文字必须准确可读。
```

🇺🇸 English:

```text
Add a small title text “FOCUS MODE” at the bottom of the image. Use a clean minimal font, the text must be accurate and legible.
```

> 📝 **对照提示**：对话式迭代是 GPT Image 2 的强项。中英文迭代指令在”保持构图不变”的遵循度上可能有差异——英文”Keep the composition the same”通常比中文”保持构图不变”得到更稳定的构图保留。第三轮加文字时，两种语言的文字准确率也值得对比。

输出：

- 记录每轮修改对画面的影响。

### Day 5：本周小作品

任务：完成一张“AI 学习计划封面图”。

要求：

- 竖版 3:4 或 4:5。
- 必须有中文标题。
- 包含学习、图像生成、创作工具三个视觉元素。
- 至少迭代 2 轮。

评分：

- 指令准确 30%。
- 文字可读 30%。
- 构图清晰 20%。
- 视觉完成度 20%。

## 8. 第 2 周：六维度万能公式与美学描述

核心笔记：[[concepts/prompt-formula-six-dimensions.md|提示词六维度万能公式]]

本周目标：

- 把“想要好看”转化为可操作的六维描述。
- 建立自己的光线、色彩、构图和质感词汇。

### Day 1：六维度拆解

公式：

```text
主体 + 动作/姿态 + 场景 + 光线 + 风格 + 质量/约束
```

练习：把以下短句扩写成完整提示词。

短句：

```text
一只杯子放在桌上。 / A cup on a table.
```

示例扩写 · Expanded Version：

🇨🇳 中文：

```text
一只手工陶瓷咖啡杯，表面有细腻的斑点纹理，放在温暖的橡木书桌旁，旁边有一本打开的笔记本和一支钢笔。清晨的窗光从右侧照入，在陶瓷表面形成柔和的阴影和细腻的高光。温馨的编辑风格静物摄影，柔和的绿色与米色色调，浅景深，50mm 镜头质感。高细节、自然纹理、无标志、无水印、无多余文字。
```

🇺🇸 English:

```text
A handcrafted ceramic coffee mug with subtle speckled texture, placed on a warm oak desk beside an open notebook and a fountain pen. Morning window light from the right creates soft shadows and gentle highlights on the ceramic surface. Cozy editorial still-life photography, muted green and cream color palette, shallow depth of field, 50mm lens look. High detail, natural texture, no logo, no watermark, no extra text.
```

> 📝 **对照提示**：从"一只杯子放在桌上"扩写到六维度完整版，对比中英文扩写后生成结果的差异。中文"斑点纹理""细腻的高光"vs 英文"speckled texture""gentle highlights"——英文技术术语通常描述更精确。

### Day 2：主体与动作训练

任务：写 5 条主体不同的提示词。

示例主题：

- 一个正在整理画册的设计师。
- 一双漂浮在空中的运动鞋。
- 一个中式茶馆的窗边座位。
- 一个正在直播讲解护肤品的主播。
- 一个原创幻想角色的半身像。

每条必须包含：

- 主体特征。
- 动作或状态。
- 至少 1 个细节。

### Day 3：光线训练

练习：同一主体使用 5 种光线。

主体：

```text
一位穿白衬衫的年轻创作者坐在桌前看镜头。
```

光线版本：

1. 黄金时刻逆光。
2. 柔和窗光。
3. 霓虹混合光。
4. Rembrandt 光。
5. 阴天漫射光。

示例 · Rembrandt 光：

🇨🇳 中文：

```text
一位穿着挺括白衬衫的年轻创作者坐在木桌前，直视镜头。左上方的伦勃朗光在面部阴影侧形成一个小三角形光斑，深沉但柔和的阴影，电影感的棕色与青色调色，中景特写，85mm 镜头质感，真实皮肤纹理，无水印，无多余手指。
```

🇺🇸 English:

```text
Portrait of a young creator in a crisp white shirt sitting at a wooden desk, looking directly at the camera. Rembrandt lighting from upper left creates a small triangle of light on the shadow side of the face, deep but soft shadows, cinematic brown and teal color grading, medium close-up, 85mm lens look, realistic skin texture, no watermark, no extra fingers.
```

> 📝 **对照提示**：光线描述是关键对比维度。中文"伦勃朗光"直接借用术语，模型可能理解为"类似伦勃朗画作的光"而非精确的三角光；英文"Rembrandt lighting"配合"small triangle of light on the shadow side"则同时给出术语和具体描述，通常更准确。

### Day 4：风格与质量约束

任务：把同一画面改成 4 种风格。

画面：

```text
一个 AI 创作工作台，桌上有电脑、手绘草图、相机、咖啡和色卡。
```

风格：

- 北欧极简。
- 电影剧照。
- 复古杂志摄影。
- 科技产品广告。

质量约束示例 · Quality Constraints：

🇨🇳 中文：

```text
高细节、构图干净、材质真实、透视连贯、文字可读、无水印、无多余物体、无几何变形、无模糊细节。
```

🇺🇸 English:

```text
high detail, clean composition, realistic materials, coherent perspective, readable text, no watermark, no extra objects, no distorted geometry, no blurry details.
```

> 📝 **对照提示**：质量约束/排除词通常英文效果更好，因为很多排除词（如"no watermark""no distorted geometry"）是模型训练时常见的英文标注模式。中文"无水印"的效果可能不如英文"no watermark"稳定。

### Day 5：本周小作品

任务：做一组“同一主题五风格”练习。

提交：

- 5 条提示词。
- 5 张图。
- 1 张对比表：主体、光线、风格、质量约束分别如何影响结果。

## 9. 第 3 周：人像摄影专项

核心笔记：[[concepts/portrait-prompt-templates.md|人像摄影提示词模板]]

本周目标：

- 掌握人像七层模型。
- 熟练使用光线、镜头、胶片、皮肤质感和姿态描述。

人像七层模型：

1. 相机/媒介。
2. 光线环境。
3. 人物五官。
4. 服装造型。
5. 姿势动作。
6. 表情情绪。
7. 画质约束。

### Day 1：街拍日常

示例 · Street Photography：

🇨🇳 中文：

```text
35mm 街头摄影，一位穿着米色大号风衣和白色运动鞋的年轻女性，雨后安静地走过城市斑马线。柔和的阴天自然光，湿润的柏油路面反射着店铺灯光，放松的表情，头发随微风轻轻飘动。平视中景，细腻的胶片颗粒感，低饱和城市色调，真实皮肤纹理。无水印、无美颜滤镜、无手部变形。
```

🇺🇸 English:

```text
35mm street photography, natural candid portrait of a young woman wearing an oversized beige trench coat and white sneakers, walking across a quiet city crosswalk after light rain. Soft overcast daylight, wet asphalt reflecting storefront lights, relaxed expression, hair moving slightly in the breeze. Medium shot from eye level, subtle film grain, muted urban color palette, realistic skin texture. No watermark, no beauty filter, no distorted hands.
```

> 📝 **对照提示**：人像场景中，中文"低饱和城市色调"和英文"muted urban color palette"的色彩倾向可能不同——中文可能偏灰绿，英文可能偏灰棕。"街头摄影"vs "street photography"在构图风格上也可能有微妙差异。

练习：

- 改成人物性别、服装、城市、天气四个变量。
- 生成 2 张不同氛围街拍。

### Day 2：胶片复古

示例 · Film Vintage：

🇨🇳 中文：

```text
Kodak Portra 400 胶片人像，一位沉思的年轻男士穿着深绿色针织毛衣，坐在旧书店洒满阳光的窗边。午后的温暖窗光，空气中漂浮着尘埃微粒，浅景深，50mm 镜头，柔和的自然颗粒感，色彩微微褪色，怀旧安静的情绪。真实的皮肤质感，温柔的表情，无水印、无塑料感皮肤、无多余手指。
```

🇺🇸 English:

```text
Kodak Portra 400 film portrait, a thoughtful young man in a dark green knit sweater sitting beside a sunlit window in an old bookstore. Warm afternoon window light, dust particles in the air, shallow depth of field, 50mm lens, soft natural grain, slightly faded colors, nostalgic quiet mood. Authentic skin texture, gentle expression, no watermark, no plastic skin, no extra fingers.
```

练习：

- 分别使用 `Kodak Portra 400`、`Fujifilm Pro 400H`、`Ilford HP5 black and white` 写 3 条提示词。
- 比较色彩和情绪差异。

### Day 3：电影质感

示例 · Cinematic Portrait：

🇨🇳 中文：

```text
电影感人像静帧，一位疲惫的女侦探午夜站在闪烁的地铁站台灯光下，穿着深色大衣，手里拿着一杯纸杯咖啡。绿色荧光灯与暖色实景灯混合照明，深沉的阴影，变形镜头光晕，浅景深，紧张安静的氛围，青色与琥珀色调色，真实的皮肤毛孔与面料纹理。16:9 画幅，无文字、无水印、无人体变形。
```

🇺🇸 English:

```text
Cinematic portrait still, a tired female detective standing under a flickering subway platform light at midnight, wearing a dark coat and holding a paper coffee cup. Mixed green fluorescent and warm practical lighting, deep shadows, anamorphic lens flare, shallow depth of field, tense quiet atmosphere, teal and amber color grade, realistic skin pores and fabric texture. 16:9 frame, no text, no watermark, no distorted anatomy.
```

> 📝 **对照提示**：电影感描述中，"teal and amber color grade"（青橙色调色）是电影行业标准术语，英文版通常渲染更准确。中文"青色与琥珀色调色"的"青色"可能被理解为翠绿或蓝色，导致色调偏移。

练习：

- 设计 2 个角色：侦探、音乐人、创业者、医生任选。
- 每个角色写 1 条电影感人像提示词。

### Day 4：国风人像

示例 · Chinese Guofeng Portrait：

🇨🇳 中文：

```text
国风人像，一位优雅的年轻女子穿着浅象牙色汉服，衣上有精致的云纹刺绣，站在烟雾缭绕的湖畔亭阁旁。柔和的晨雾，漫射的阳光，水墨风背景，克制的翠绿与暖象牙色调，优雅的姿态，平静的表情，乌黑长发配简素发簪。艺术人像摄影融合中国水彩美学，精致的面料纹理，无水印、无多余首饰、无手部变形。
```

🇺🇸 English:

```text
Chinese guofeng portrait, an elegant young woman wearing a light ivory hanfu with subtle embroidered cloud patterns, standing beside a misty lake pavilion. Soft morning fog, diffused sunlight, ink-wash inspired background, restrained jade green and warm ivory palette, graceful posture, calm expression, long black hair with simple hairpin. Fine art portrait photography mixed with Chinese watercolor aesthetics, delicate fabric texture, no watermark, no extra jewelry, no distorted hands.
```

> 📝 **对照提示**：国风场景是中英文差异最大的类型之一。中文"国风人像"能触发模型对中式美学的整体理解（包括构图留白、色调偏好），而英文"Chinese guofeng portrait"更像一个标签式描述。中文版可能在"意境"上更自然，英文版在细节描述（如"jade green""ivory palette"）的色准上更可控。

练习：

- 使用“汉服 + 场景 + 色调 + 光线 + 情绪”写 2 条。
- 一条偏摄影，一条偏水墨插画。

### Day 5：本周小作品

任务：人像三连拍。

提交：

- 街拍日常 1 张。
- 胶片复古 1 张。
- 电影或国风 1 张。
- 每张附提示词和 100 字复盘。

评分：

- 人物真实感 25%。
- 光线控制 25%。
- 风格准确 25%。
- 细节无明显 AI 错误 25%。

## 10. 第 4 周：海报设计与文字渲染

核心笔记：[[concepts/poster-prompt-templates.md|海报设计提示词模板]]

本周目标：

- 练习视觉层级、文字位置、海报类型和中文文字渲染。
- 能做城市、产品、中式、电影四类海报。

### Day 1：海报公式

海报提示词结构：

```text
海报类型 + 主视觉 + 文案内容 + 排版位置 + 色彩方案 + 风格 + 输出约束
```

示例 · AI Workshop Poster：

🇨🇳 中文：

```text
一张现代竖版 AI 创作工作坊海报。主视觉：干净桌面上一台发光的平板电脑，上方漂浮着多彩的图片生成缩略图。顶部主标题文字必须准确写出"AI 创作营"。副标题在下方："从提示词到作品集"。底部区域包含日期"2026.06.01"和地点"Shanghai"。整洁的网格排版，充裕留白，蓝色与暖橙色作为点缀色，现代教育品牌风格，中文字体清晰可读，不要多余文字，不要水印。
```

🇺🇸 English:

```text
Modern vertical poster for an AI creativity workshop. Main visual: a glowing tablet on a clean desk, with colorful image-generation thumbnails floating above it. Top headline text must read exactly "AI 创作营". Subtitle below: "从提示词到作品集". Bottom area includes date "2026.06.01" and location "Shanghai". Clean grid layout, generous white space, blue and warm orange accent colors, modern education brand style, sharp readable Chinese typography, no extra text, no watermark.
```

> 📝 **对照提示**：混合中英文文字的海报是高难度场景。英文提示词要求生成中文标题时，文字准确率通常高于中文提示词（模型对英文指令的遵循更稳定）。但中文提示词对"留白""网格排版"等设计概念的表达可能更自然。

### Day 2：城市旅游海报

示例 · Vintage Travel Poster：

🇨🇳 中文：

```text
复古旅行海报风格的杭州插画，全景西湖场景，包含雷峰塔、拱形石桥、荷叶和远处的青山。温暖的日落天空，平静的湖面倒影，限定配色：翠绿、米白、珊瑚橙和深蓝。顶部大字："HANGZHOU"。底部小字中文："西湖春日"。1960 年代丝网印刷质感，优雅的复古字体，构图干净，无水印、无多余字母。
```

🇺🇸 English:

```text
Vintage travel poster illustration of Hangzhou, panoramic West Lake scene with Leifeng Pagoda, arched stone bridge, lotus leaves and distant green hills. Warm sunset sky, calm lake reflection, limited color palette of jade green, cream, coral orange and deep blue. Large text at top: "HANGZHOU". Smaller Chinese text at bottom: "西湖春日". 1960s screen print texture, elegant retro typography, clean composition, no watermark, no extra letters.
```

> 📝 **对照提示**：城市海报中的地标元素描述，中文直接说"雷峰塔""拱形石桥"，模型对中文地标名的视觉理解可能比英文"Leifeng Pagoda""arched stone bridge"更准确（尤其对中式建筑）。但英文版在整体构图描述上更结构化。

练习：

- 为你熟悉的城市做 1 张旅游海报。
- 必须包含 3 个城市地标。
- 必须有英文或中文城市名。

### Day 3：产品广告海报

示例 · Product Launch Poster：

🇨🇳 中文：

```text
未来感产品发布会海报，为一款名为"NOTE X"的智能笔记本设计。主视觉：纤薄的黑色数字笔记本悬浮在画面中央，配银色手写笔，分解视图展示屏幕层和磁吸铰链。深炭灰色背景配青色技术线框元素。顶部标题："NOTE X"。产品下方副标题："Think, sketch, create"。产品周围有细线规格标注，Apple 发布会风格遇上赛博朋克极简美学，高对比灯光，文字可读，无水印。
```

🇺🇸 English:

```text
Futuristic product launch poster for a smart notebook named "NOTE X". Main visual: a slim black digital notebook floating in the center with a silver stylus, exploded view showing screen layers and magnetic hinge. Dark charcoal background with cyan technical wireframe elements. Headline at top: "NOTE X". Subtitle below product: "Think, sketch, create". Thin specification callouts around the product, Apple keynote meets cyberpunk minimal aesthetic, high contrast lighting, readable text, no watermark.
```

练习：

- 虚构一个产品：咖啡、耳机、香水、笔记本、护肤品任选。
- 做一张发布会海报。

### Day 4：中式美学海报

示例 · Chinese Aesthetic Poster：

🇨🇳 中文：

```text
中式美学竖版海报，茶文化展览主题。主视觉：一只青瓷茶杯放在深色木桌上，杯中升起的蒸汽化作烟雾缭绕的山峦轮廓。背景有微妙的水墨肌理和大面积留白。右上角主标题中文："茶山之间"。底部小字副标题："一盏茶里的东方美学"。墨黑、青瓷绿与暖象牙色调，优雅的宋体中文排版，沉静诗意的氛围，印刷品质，无多余文字、无水印。
```

🇺🇸 English:

```text
Chinese aesthetic vertical poster for a tea culture exhibition. Main visual: a celadon teacup on a dark wooden table, steam rising into the shape of misty mountains. Background with subtle ink wash texture and large negative space. Main Chinese title at upper right: "茶山之间". Small subtitle at bottom: "一盏茶里的东方美学". Muted ink black, celadon green and warm ivory palette, elegant serif Chinese typography, calm and poetic mood, print-ready quality, no extra text, no watermark.
```

> 📝 **对照提示**：中式美学是最能体现中英文差异的场景。中文"留白""诗意""水墨肌理"等词自带东方美学语境，模型可能调用更多中国画训练数据。英文"negative space""poetic mood""ink wash texture"则更中性。对比两者在"意境"营造上的差异。

练习：

- 主题任选：茶、书法、节气、香、园林。
- 写 1 条海报提示词，强调留白和文字层级。

### Day 5：本周小作品

任务：完成“城市海报挑战”。

提交：

- 1 张城市旅游海报。
- 1 张产品广告海报。
- 1 张中式海报。
- 每张记录文字是否准确、排版是否稳定、下一轮如何优化。

## 11. 第 5 周：UI 与社交媒体截图

核心笔记：[[concepts/ui-prompt-templates.md|UI与社交媒体截图提示词模板]]

本周目标：

- 学会把界面拆成状态栏、导航、内容区、底部栏、浮层、评论、商品卡等组件。
- 做出可信的 App Store 截图、小红书图、直播截图、微信聊天截图。

### Day 1：UI 描述清单

练习模板 · App Store Screenshot：

🇨🇳 中文：

```text
iOS App Store 营销截图，iPhone 15 Pro 机型边框，一款名为"Daily Spark"的习惯追踪应用。主屏幕显示简洁的仪表盘，包含今日习惯、环形进度条、连续打卡天数和三个习惯卡片。顶部导航栏标题"Today"。底部标签栏有主页、日历、统计、设置图标。浅色模式，SF Pro 字体，柔和的绿色强调色，干净专业的 UI，逼真的手机截图，9:19.5 比例，文字可读，无水印。
```

🇺🇸 English:

```text
iOS App Store marketing screenshot, iPhone 15 Pro frame, a habit tracking app named "Daily Spark". Main screen shows a clean dashboard with today's habits, circular progress ring, streak count, and three habit cards. Top navigation bar with title "Today". Bottom tab bar with icons for Home, Calendar, Stats, Settings. Light mode, SF Pro font, soft green accent color, clean professional UI, realistic mobile screenshot, 9:19.5 ratio, readable text, no watermark.
```

> 📝 **对照提示**：UI 截图对结构描述的精确度要求高。英文版用"dashboard""tab bar""progress ring"等 UI 专业术语，通常生成的界面结构更规范。中文版"仪表盘""标签栏""环形进度条"在视觉还原度上可能略有偏差。

检查：

- 是否像真实手机截图。
- 是否有清楚的信息架构。
- 是否出现乱码或不合理按钮。

### Day 2：小红书封面

示例 · Xiaohongshu Cover：

🇨🇳 中文：

```text
小红书风格封面图，3:4 竖版。主题："5 个 AI 出图提示词技巧"。干净的生活方式桌面背景，有笔记本电脑、色卡、咖啡和小本子。大号加粗中文标题居中："5 个 AI 出图技巧"。小号副标题："新手也能稳定出片"。清新白色与珊瑚色配色，柔和日光，现代创作者美学，中文文字可读，无水印、无多余文字。
```

🇺🇸 English:

```text
Xiaohongshu style cover image, 3:4 vertical. Topic: "5个AI出图提示词技巧". Clean lifestyle desk background with laptop, color swatches, coffee and small notebook. Large bold Chinese title centered: "5个AI出图技巧". Smaller subtitle: "新手也能稳定出片". Fresh white and coral color palette, soft daylight, modern creator aesthetic, readable Chinese text, no watermark, no extra text.
```

> 📝 **对照提示**：小红书封面需要中文标题。中文提示词对"小红书风格"有天然理解（包括排版习惯、配色偏好），英文版则需要额外描述平台特征。但中文文字渲染准确率上，英文提示词可能更可靠。

练习：

- 做 3 张不同主题的小红书封面。
- 主题建议：AI绘画入门、人像提示词、海报文字渲染。

### Day 3：直播截图

示例 · Livestream Screenshot：

🇨🇳 中文：

```text
中国电商直播截图，9:16 竖版。一位亲切的女主播在明亮的直播间里拿着一瓶透明护肤精华液。直播界面包含观看人数"12.8 万"，飘浮的点赞，购物车图标上红色折扣标签"限时半价"，置顶商品卡显示"修护精华液 ¥99"，滚动评论"质地清爽吗？""敏感肌能用吗？"。温暖高调灯光，逼真的抖音直播 UI，中文文字可读，无水印。
```

🇺🇸 English:

```text
Chinese e-commerce livestream screenshot, 9:16 vertical. A friendly female host holding a glass skincare serum bottle in a bright studio. Live interface includes viewer count "12.8万", floating likes, shopping cart icon with red discount tag "限时半价", pinned product card showing "修护精华液 ¥99", scrolling comments "质地清爽吗？", "敏感肌能用吗？". Warm high-key lighting, authentic Douyin livestream UI, readable Chinese text, no watermark.
```

> 📝 **对照提示**：直播截图的 UI 元素（观看数、弹幕、商品卡）用中文提示词描述更自然，因为对"飘浮的点赞""置顶商品卡"等中国特色 UI 元素的表达更直观。英文版需要更多解释性描述。

练习：

- 选择一个商品，设计直播画面。
- 必须包含主播、商品卡、评论、价格、折扣标签。

### Day 4：微信聊天截图

示例 · WeChat Chat Screenshot：

🇨🇳 中文：

```text
微信手机聊天截图，9:16 竖版，浅色模式。"设计师小林"和"客户王姐"之间的对话。消息讨论 AI 海报修改："标题可以再大一点吗？""可以，我会把主视觉往下移。""颜色想更高级一点。""我改成墨绿和米白的配色试试。"。微信 UI 元素包括时间戳、绿色右侧气泡、白色左侧气泡、简单头像、底部输入栏。逼真的 iOS 截图风格，中文文字可读，无水印、无多余消息。
```

🇺🇸 English:

```text
WeChat mobile chat screenshot, 9:16 vertical, light mode. Chat between "设计师小林" and "客户王姐". Messages discuss an AI poster revision: "标题可以再大一点吗？", "可以，我会把主视觉往下移。", "颜色想更高级一点。", "我改成墨绿和米白的配色试试。". WeChat UI elements include time stamp, green right-side bubbles, white left-side bubbles, simple avatars, input bar at bottom. Realistic iOS screenshot style, readable Chinese text, no watermark, no extra messages.
```

> 📝 **对照提示**：聊天截图中包含大量中文对话内容。中文提示词在"对话感""口语化表达"的把控上更自然。英文提示词在 UI 布局结构（气泡方向、头像位置）的描述上更精确。两者生成的中文对话文字准确率可能都有偏差，需要多次迭代。

练习：

- 做一个“客户反馈海报修改”的聊天截图。
- 控制信息真实可信，不要塞太多文字。

### Day 5：本周小作品

任务：做一组“AI 课程推广素材”。

提交：

- App Store 截图 1 张。
- 小红书封面 1 张。
- 直播截图 1 张。
- 微信聊天截图 1 张。

评分：

- 平台真实感 30%。
- 文案准确 30%。
- 信息层级 20%。
- 视觉统一 20%。

## 12. 第 6 周：角色设计与电商产品图

核心笔记：[[concepts/character-prompt-templates.md|角色设计提示词模板]]、[[concepts/ecommerce-prompt-templates.md|电商产品图提示词模板]]

本周目标：

- 完成一个原创角色设定。
- 完成一组电商产品图：白底、场景、广告。

### Day 1：角色设定表

示例 · Character Design Sheet：

🇨🇳 中文：

```text
原创 AI 图书管理员角色的设计稿。一位沉静的年轻女性，银色短发，圆框眼镜，深蓝色长外套，发光的书签形耳环，身旁有一个漂浮的数字小书精灵。干净的白色背景。全身正面视图、四分之三侧面视图、侧面视图和头部特写。附带色板：藏青、银色、暖象牙色和青色。半写实动漫插画风格，所有视图的服装和面部特征保持一致，专业概念设计稿，无水印。
```

🇺🇸 English:

```text
Character design sheet for an original AI librarian character. A calm young woman with short silver hair, round glasses, navy blue long coat, glowing bookmark-shaped earrings, and a small floating digital book companion. Clean white background. Full body front view, three-quarter view, side view, and close-up headshot. Include color palette swatches of navy, silver, warm ivory and cyan. Semi-realistic anime illustration style, consistent outfit and facial features across all views, professional concept art sheet, no watermark.
```

> 📝 **对照提示**：角色设定表对一致性和细节描述要求高。英文"character design sheet""concept art sheet"是行业标准术语，模型理解更精确。中文"设计稿""概念设计稿"的理解范围更宽泛，可能产出不同排版格式。

练习：

- 创作 1 个原创角色。
- 写清楚身份、外形、服装、道具、色彩、性格。

### Day 2：多角度转盘

示例 · Character Turnaround：

🇨🇳 中文：

```text
角色转盘设计稿，原创奇幻快递员角色，年轻男士穿着棕色短款旅行夹克、米色围巾、工具腰带、皮靴，肩上有一只小型机械鸟。白色背景上五个视图：正面、左四分之三、侧面、右四分之三、背面。所有角度的服装细节保持一致，下方有色板色卡，侧面有身高标记，动画制作级品质，无水印。
```

🇺🇸 English:

```text
Character turnaround sheet, original fantasy courier character, young man wearing a short brown travel jacket, cream scarf, utility belt, leather boots, and a small mechanical bird on his shoulder. Five views on clean white background: front, 3/4 left, side profile, 3/4 right, back. Consistent costume details across all angles, color palette swatches below, height marker on the side, animation production quality, no watermark.
```

> 📝 **对照提示**："turnaround sheet"是动画/游戏行业标准术语，英文版通常生成更规范的多视图排列。中文"转盘设计稿"可能被理解为不同格式。视图标签（front, 3/4 left, side profile 等）用英文更稳定。

练习：

- 给 Day 1 角色生成五视图。
- 观察一致性问题，记录哪些细节最容易丢。

### Day 3：表情包/动作表

示例 · Expression Sheet：

🇨🇳 中文：

```text
AI 图书管理员角色的表情包设计稿，Q 版贴纸风格。3×3 九宫格表情：开心、专注、惊讶、困惑、骄傲、犯困、担忧、大笑、沮丧。保持一致的银色短发、圆框眼镜、深蓝外套和发光书签耳环。干净的类透明白色背景，贴纸级品质，粗线条清晰轮廓，无水印。
```

🇺🇸 English:

```text
Character expression sheet of the AI librarian character in chibi sticker style. Grid of 9 expressions: happy, focused, surprised, confused, proud, sleepy, worried, laughing, frustrated. Consistent short silver hair, round glasses, navy coat and glowing bookmark earrings. Clean transparent-like white background, sticker-ready quality, bold clean outlines, no watermark.
```

> 📝 **对照提示**：表情包描述中，英文"chibi sticker style"是广泛使用的术语，模型识别度高。中文"Q 版贴纸风格"的理解范围可能更窄或更宽。表情名称用英文（happy, focused 等）在面部表情的识别上通常更稳定。

练习：

- 做 9 格表情。
- 选 3 个最适合社交传播的表情。

### Day 4：电商产品图三模式

商品：任选一个真实或虚构产品。

白底棚拍示例 · White Background Shot：

🇨🇳 中文：

```text
干净白色背景的产品摄影，一只哑光黑色保温水杯，以微斜的四分之三角度竖立。左上方柔光箱照明，地面有细腻的投影，金属质感清晰，小型 logo"NOVA"可读，高端电商主图，1:1 方形，无道具、无水印。
```

🇺🇸 English:

```text
Clean white background product photography of a matte black insulated water bottle, standing upright at a slight three-quarter angle. Softbox lighting from upper left, subtle shadow on the floor, crisp metal texture, readable small logo "NOVA", high-end e-commerce main image, 1:1 square, no props, no watermark.
```

> 📝 **对照提示**：白底棚拍是电商标准场景。英文"softbox lighting""three-quarter angle"是产品摄影标准术语，光线和角度控制更精确。中文"柔光箱""四分之三角度"的理解可能有偏差。

场景图示例 · Lifestyle Shot：

🇨🇳 中文：

```text
生活方式产品摄影，一只哑光黑色保温水杯放在徒步小径的岩石上，旁边有折叠地图和指南针。清晨山间光线，凉爽雾蒙蒙的背景，粗犷的户外氛围，杯壁上有水珠，浅景深，高端户外品牌美学，4:5 比例，无水印。
```

🇺🇸 English:

```text
Lifestyle product photography of a matte black insulated water bottle placed on a hiking trail rock beside a folded map and compass. Morning mountain light, cool misty background, rugged outdoor mood, water droplets on the bottle surface, shallow depth of field, premium outdoor brand aesthetic, 4:5 ratio, no watermark.
```

广告图示例 · Advertising Poster：

🇨🇳 中文：

```text
动感广告海报，为名为"NOVA"的哑光黑色保温水杯设计。水杯悬浮在画面中央，周围有飞溅的水花和冰块碎片，深蓝渐变背景，戏剧性的轮廓光，顶部粗体标题文字"STAY COLD"，下方小字副标题"24H insulated bottle"，高对比商业摄影，文字可读，无水印。
```

🇺🇸 English:

```text
Dynamic advertising poster for a matte black insulated water bottle named "NOVA". The bottle floats in the center with splashing water and ice fragments around it, dark blue gradient background, dramatic rim light, bold headline text "STAY COLD" at top, small subtitle "24H insulated bottle" below, high contrast commercial photography, readable text, no watermark.
```

> 📝 **对照提示**：广告图的飞溅水花等动态效果，英文"splashing water and ice fragments"比中文"飞溅的水花和冰块碎片"通常渲染更生动。轮廓光（rim light）在英文中是标准摄影术语，中文"轮廓光"的理解有时会泛化为"背光"。

### Day 5：本周小作品

任务：

- 角色设定表 1 张。
- 角色转盘 1 张。
- 角色表情包 1 张。
- 电商三模式产品图 3 张。

复盘问题：

- 哪些提示能提高角色一致性？
- 产品图中材质、品牌文字、比例是否可靠？
- 哪张最接近商业可交付？

## 13. 第 7 周：C.L.E.A.R. 提示词工程与风格混合

核心笔记：[[concepts/clear-framework.md|C.L.E.A.R.框架]]、[[concepts/style-mixing-strategies.md|风格混合策略]]

本周目标：

- 不再只写一次性提示词，而是设计可复用模板。
- 学会控制风格混合，而不是把很多风格词堆在一起。

### Day 1：C.L.E.A.R. 五步法

说明：

- Context：说明用途、受众、场景。
- Layer：分层描述主体、背景、光线、文字、约束。
- Exclude：排除错误、杂物、乱码和不想要的风格。
- Adjust：根据结果改一个维度。
- Refine：保留有效部分，删掉无效描述。

练习：咖啡产品图三轮迭代。

第 1 版 · Version 1：

🇨🇳 中文：

```text
一张咖啡豆包装产品图，高级、好看、有品牌感。
```

🇺🇸 English:

```text
A premium coffee bean packaging product photo, elegant, good-looking, with brand identity.
```

> 📝 第 1 版中英文都很模糊，"高级""elegant"等抽象词让模型自由发挥，结果不确定性高。

第 2 版 · Version 2（C.L.E.A.R. 之 Layer + Context）：

🇨🇳 中文：

```text
高端产品摄影，一个名为"ROAST LAB"的牛皮纸咖啡豆袋，放在深色胡桃木桌上，周围散落着烘焙咖啡豆。左侧暖色侧光，柔和阴影，干净的深色背景，标签文字可读，高端咖啡馆品牌美学，无水印、无多余文字。
```

🇺🇸 English:

```text
Premium product photography of a kraft paper coffee bean bag named "ROAST LAB", placed on a dark walnut table with roasted coffee beans scattered around. Warm side light from the left, soft shadow, clean dark background, readable label text, high-end cafe brand aesthetic, no watermark, no extra text.
```

> 📝 第 2 版开始分层描述（主体、道具、光线、背景），中英文的精确度接近，但英文在品牌名文字渲染上更可靠。

第 3 版 · Version 3（C.L.E.A.R. 之 Refine + Exclude）：

🇨🇳 中文：

```text
精品咖啡品牌高端产品摄影。主体：一个哑光牛皮纸咖啡豆袋，标签准确写着"ROAST LAB"和"ETHIOPIA YIRGACHEFFE"，竖立在深色胡桃木桌中央。辅助道具：右侧一个小陶瓷杯，前景有几颗烘焙咖啡豆。左上方暖色侧光在袋边形成金色光边，背景过渡到柔和阴影。极简杂志风构图，4:5 比例，标签可读、无多余字母、无水印、无杂乱道具。
```

🇺🇸 English:

```text
Premium product photography for a specialty coffee brand. Main subject: a matte kraft paper coffee bean bag labeled exactly "ROAST LAB" and "ETHIOPIA YIRGACHEFFE", standing upright at the center on a dark walnut table. Supporting props: a small ceramic cup on the right and a few roasted beans in the foreground. Warm side light from upper left creates a golden rim on the bag edge, background falls into soft shadow. Minimal editorial composition, 4:5 ratio, readable label, no extra letters, no watermark, no messy props.
```

> 📝 **三轮迭代对照**：记录每一版中英文的变化——第 2 版增加了什么层，删掉了什么模糊词？第 3 版的"Refine"在哪里强化了成功因素？中英文版本在迭代中各自改善了什么？

输出：

- 写出每一版增加了什么、删掉了什么、结果为什么变化。

### Day 2：模板设计

参数流模板：

```text
{海报类型} poster for {品牌/活动名}. Main visual: {主视觉描述}. Headline text exactly "{主标题}" at {标题位置}. Subtitle "{副标题}" at {副标题位置}. Color palette: {配色}. Style: {设计风格}. Lighting/mood: {光线与氛围}. Layout: {排版结构}. Quality constraints: readable typography, clean composition, no extra text, no watermark.
```

练习：

- 用这个模板生成 3 个不同主题：课程、产品、城市。
- 记录哪些参数最影响结果。

### Day 3：风格混合原则

原则：

- 最多混合 2-3 种核心风格。
- 明确主风格占 60-70%。
- 给每种风格分配职责：介质、色彩、构图、内容、材质。

示例：中式水墨 × 赛博朋克 · Ink-Wash × Cyberpunk：

🇨🇳 中文：

```text
一幅未来感中国水墨城市景观，65% 传统水墨画 + 35% 赛博朋克。媒介和构图取自中国山水画：层叠的雾气山脉、流动的河流、大面积留白、富有表现力的墨笔肌理。赛博朋克元素仅出现在城市细节中：霓虹招牌、全息桥梁、发光的窗户以及水面上微妙的品红-青色倒影。克制的墨黑、翠绿与少量霓虹点缀。诗意、有氛围感、不杂乱、无水印、无多余文字。
```

🇺🇸 English:

```text
A futuristic Chinese ink-wash cityscape, 65% traditional ink painting and 35% cyberpunk. Medium and composition come from Chinese shanshui painting: layered misty mountains, flowing river, large negative space, expressive ink brush texture. Cyberpunk elements appear only in the city details: neon signs, holographic bridges, glowing windows and subtle magenta-cyan reflections on water. Restrained black ink, jade green and small neon accents. Poetic, atmospheric, not cluttered, no watermark, no extra text.
```

> 📝 **对照提示**：风格混合中，中文"山水画""留白""墨笔肌理"自带东方美学语境，模型对中国画的理解更深。英文"shanshui painting""negative space""ink brush texture"是中性描述，但"shanshui"作为借词，模型可能识别度不如纯英文术语。赛博朋克部分两种语言效果接近。

### Day 4：跨界实验

可选组合：

- 浮世绘 × 科幻飞船。
- Art Deco × AI 科技。
- 像素艺术 × 写实摄影。
- 巴洛克 × 极简主义。
- 国风水墨 × 产品广告。

提交：

- 1 条 150 字以上提示词。
- 1 张图。
- 100 字说明：每种风格负责什么。

### Day 5：本周小作品

任务：做一个可复用模板包。

至少包含：

- 人像模板 1 条。
- 海报模板 1 条。
- 电商模板 1 条。
- UI截图模板 1 条。
- 风格混合模板 1 条。

每条模板必须包含 `{变量}` 占位符。

## 14. 第 8 周：商业路径与毕业作品集

核心笔记：[[concepts/commercial-path.md|商业变现路径]]

本周目标：

- 完成一个有明确用途的作品集。
- 从作品集中提炼可商业化服务。

### Day 1：选择毕业主题

任选一个方向：

1. 虚构品牌全套视觉：logo 概念图、产品图、海报、小红书封面、直播截图。
2. 城市四季海报：春夏秋冬 4 张系列海报。
3. 原创角色设定集：设定表、转盘、表情包、海报、社媒图。
4. 电商品牌素材包：主图、详情页场景、广告海报、直播图、社媒封面。
5. AI课程推广素材：课程封面、招生海报、小红书、App截图、聊天反馈截图。

### Day 2-4：毕业项目制作

最低交付：

- 5 张作品级图片。
- 5 条最终提示词。
- 1 个可复用模板。
- 1 篇复盘文档。

推荐交付：

- 12 张图片。
- 12 条提示词。
- 3 个可复用模板。
- 1 套定价与服务说明。

### Day 5：作品集复盘

复盘模板：

```markdown
# 毕业项目复盘

## 项目主题

## 目标受众

## 作品清单

## 最终提示词

## 三个最有效的提示词技巧

## 三个最常见的问题

## 可商业化方向

## 下一轮优化计划
```

商业化思考：

| 路径 | 适合的作品 | 可交付内容 | 初始定价建议 |
| --- | --- | --- | --- |
| 电商产品图 | 产品三模式图 | 主图、详情图、广告图 | 单张或套餐 |
| 自媒体配图 | 小红书/公众号封面 | 月度配图包 | 月费 |
| 社交账号运营 | 直播截图、社媒素材 | 封面、海报、活动图 | 月费 |
| 提示词售卖 | 可复用模板 | 模板包、案例库 | 单条或合集 |
| 课程教学 | 学习计划和练习 | 训练营、陪跑、资料包 | 项目制 |

## 15. 练习库

### 练习 1：第一张 AI 图

任务：

- 用 3 种不同详细程度描述同一个场景。
- 对比生成结果。

提交：

- 3 条提示词。
- 3 张图。
- 200 字对比分析。

### 练习 2：六维度万能公式

任务：

- 写 5 条不同场景的提示词：人像、产品、海报、风景、自由创意。

要求：

- 每条至少包含 4 个维度。
- 每条至少 60 个英文词或 120 个中文字符。
- 每条包含至少 1 个光线描述。
- 每条包含至少 2 个排除词。

### 练习 3：专业术语运用

任务：

- 用至少 10 个专业术语写一条人像提示词。

术语池：

```text
bokeh, golden hour, chiaroscuro, depth of field, rim lighting, Kodak Portra 400, anamorphic lens, rule of thirds, negative space, film grain, softbox lighting, Rembrandt lighting, teal and orange color grade, 85mm lens, shallow focus
```

### 练习 4：看图写美学描述

任务：

- 找 3 张你喜欢的参考图。
- 分别写色彩、情绪、光线、构图、材质描述。
- 选择其中 1 张尝试复现。

分析问题：

- 哪些描述让模型更接近原图？
- 哪些描述没有被模型理解？
- 下次应该补充什么约束？

### 练习 5：人像摄影三连拍

任务：

- 街拍日常。
- 胶片复古。
- 古风或电影质感。

每条提示词必须包含：

- 相机或媒介。
- 光线方向。
- 人物状态。
- 服装。
- 表情。
- 质量约束。

### 练习 6：城市海报挑战

任务：

- 为一个城市设计旅游海报。

要求：

- 必须有城市名称文字。
- 必须包含至少 3 个地标元素。
- 必须选择一种明确风格：复古、现代、水墨、插画、电影。
- 提示词不少于 150 字。

### 练习 7：模板设计与三轮迭代

任务：

- 设计一个带 `{变量}` 的提示词模板。
- 用同一模板完成三轮迭代。

记录：

- 第 1 轮：原始结果。
- 第 2 轮：修改一个维度。
- 第 3 轮：强化成功因素并删掉无效描述。

### 练习 8：风格混合创意挑战

任务：

- 选择 2 种风格进行混合。

要求：

- 明确主风格占比。
- 给每种风格分配职责。
- 不超过 3 种核心风格。
- 写 100 字创作说明。

### 练习 9：电商产品图三模式

任务：

- 选择一个商品。
- 生成白底主图、生活方式场景图、广告海报。

检查：

- 产品比例是否稳定。
- 材质是否真实。
- 品牌文字是否准确。
- 是否符合电商可用标准。

### 练习 10：毕业作品集

任务：

- 围绕一个主题完成 5-12 张作品。

评分：

| 维度 | 权重 | 标准 |
| --- | --- | --- |
| 提示词质量 | 30% | 结构完整、术语准确、约束清晰 |
| 视觉质量 | 25% | 构图、光线、风格、细节稳定 |
| 系列感 | 20% | 色彩、风格、主题统一 |
| 商业可用性 | 15% | 可作为真实交付物 |
| 复盘质量 | 10% | 能总结方法，而不是只展示结果 |

## 16. 作品评分表

每张作品都按以下表格自评：

| 项目 | 0分 | 1分 | 2分 | 得分 |
| --- | --- | --- | --- | --- |
| 主体清晰 | 主体混乱 | 主体可见但不突出 | 主体明确且吸引注意 |  |
| 构图稳定 | 元素散乱 | 基本完整 | 层次清楚、视觉中心稳定 |  |
| 光线准确 | 光线矛盾 | 光线可接受 | 光线方向和氛围明确 |  |
| 风格一致 | 风格混杂 | 大体接近 | 风格高度一致 |  |
| 文字准确 | 乱码/错字 | 部分正确 | 完全准确可读 |  |
| 细节可靠 | 明显 AI 错误 | 小问题 | 无明显错误 |  |
| 商业可用 | 无法使用 | 需大量修改 | 可直接交付或展示 |  |

满分 14 分。

- 12-14 分：作品集级。
- 9-11 分：可继续优化。
- 6-8 分：提示词需要重构。
- 0-5 分：重新定义主题和约束。

## 17. 推荐学习节奏清单

每周结束时检查：

- 是否完成至少 5 次生成练习。
- 是否至少做过 1 次三轮迭代。
- 是否整理了有效提示词。
- 是否记录了失败案例。
- 是否产出 1 张可放进作品集的图。

8 周结束时应拥有：

- 40 次以上提示词练习。
- 8-12 张作品集图。
- 10 条可复用模板。
- 1 套毕业项目。
- 1 篇商业化复盘。

## 18. 下一步知识库建设建议

建议在 `aigc-wiki` 中继续补充这些页面：

- `learning/logs/每日练习记录.md`
- `learning/prompts/人像提示词模板库.md`
- `learning/prompts/海报提示词模板库.md`
- `learning/prompts/电商提示词模板库.md`
- `learning/portfolio/毕业作品集.md`
- `learning/failures/失败案例复盘.md`

长期沉淀方法：

1. 每条有效提示词都保留“原始版、优化版、最终版”。
2. 每张好图都反向拆解六维度。
3. 每个失败案例都记录“问题类型”：文字错误、构图错误、风格混乱、手部错误、材质不真实、元素缺失。
4. 每月整理一次模板，删除低命中率表达，保留高稳定表达。
5. 每季度选择一个商业方向做作品集升级。

