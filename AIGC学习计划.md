---
title: AIGC 图像生成系统学习计划
created: 2026-05-13
updated: 2026-05-13
type: learning-plan
tags: [aigc, gpt-image-2, prompt-engineering, image-generation, learning-plan]
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

> 依据当前 `aigc-wiki` 的知识结构定制：以 [[GPT Image 2]] 为核心工具，以 [[提示词六维度万能公式]] 为基础方法，以 [[C.L.E.A.R.框架]] 为进阶方法，覆盖人像、海报、UI截图、角色、电商产品图、风格混合与商业变现。

## 1. 学习目标

完成本计划后，你应该具备以下能力：

1. 理解 GPT Image 2 与扩散模型的差异，知道什么时候该利用其文字渲染、复杂指令遵循、对话式迭代和图像编辑能力。
2. 熟练使用“主体 + 动作/姿态 + 场景 + 光线 + 风格 + 质量/约束”的六维度提示词公式。
3. 建立自己的专业词汇库，能准确描述构图、光线、色调、镜头、胶片、质感和负面约束。
4. 能独立完成五类核心商业场景：人像摄影、海报设计、UI/社交截图、角色设定、电商产品图。
5. 掌握 C.L.E.A.R. 迭代法，能把一次性提示词升级为可复用模板。
6. 能完成一个 12-20 张图的作品集，并从中提炼出可售卖的服务、模板或课程雏形。

## 2. 建议周期

标准周期：8 周。

节奏安排：

- 每周 5 天学习与练习，每天 60-90 分钟。
- 每周 1 天作品整理与复盘，每次 90-120 分钟。
- 每周 1 天休息或自由探索。

压缩周期：4 周。

- 将每两周内容合并为一周。
- 每天学习 2-3 小时。
- 每周至少完成 2 个作品级练习。

## 3. 学习材料映射

| 模块 | 主要笔记 | 学习重点 |
| --- | --- | --- |
| 工具认知 | [[GPT Image 2]]、[[自回归图像生成]] | 架构差异、能力边界、文字渲染、复杂指令 |
| 基础公式 | [[提示词六维度万能公式]] | 主体、动作、场景、光线、风格、质量约束 |
| 提示词工程 | [[C.L.E.A.R.框架]] | 语境、分层、排除、调整、精炼 |
| 人像场景 | [[人像摄影提示词模板]] | 七层模型、布光、胶片、五官、风格 |
| 海报场景 | [[海报设计提示词模板]] | 海报公式、文字渲染、视觉层级 |
| UI场景 | [[UI与社交媒体截图提示词模板]] | 界面结构、平台真实感、分层描述 |
| 角色场景 | [[角色设计提示词模板]] | IP还原、设定表、多角度转盘、表情包 |
| 电商场景 | [[电商产品图提示词模板]] | 白底棚拍、场景图、广告图、材质描述 |
| 创意进阶 | [[风格混合策略]] | 介质+画风、时代+风格、文化跨界 |
| 商业落地 | [[商业变现路径]] | 服务路径、定价、版权伦理、知识库沉淀 |

## 4. 每日固定训练流程

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

## 5. 第 0 周：准备与基线测试

目标：知道自己的起点，建立作品与提示词管理方式。

### Day 1：建立学习档案

任务：

- 在 Obsidian 中建立三个文件夹：`learning/logs`、`learning/prompts`、`learning/portfolio`。
- 新建一篇 `AIGC学习日志.md`，用于记录每天练习。
- 选择一个主攻方向：人像、海报、UI、电商、角色，或先全量学习。

基线练习：

```text
生成一张适合作为小红书封面的 AI 学习主题图片，画面要有科技感、清晰标题、干净排版。
```

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

## 6. 第 1 周：理解 GPT Image 2 与提示词底层逻辑

核心笔记：[[GPT Image 2]]、[[自回归图像生成]]

本周目标：

- 理解 GPT Image 2 的强项：文字渲染、复杂排版、指令遵循、对话迭代、原生图像编辑。
- 学会区分“模糊愿望”和“可执行指令”。

### Day 1：工具认知

阅读：

- [[GPT Image 2]]
- [[自回归图像生成]]

练习：同一主题三种清晰度。

主题：日落海边。

简单版：

```text
日落时分的海边，一个人在沙滩上散步。
```

进阶版：

```text
A person walking alone on a sandy beach at sunset, warm golden light, calm ocean waves in the background, nostalgic atmosphere, 35mm film photography.
```

专业版：

```text
35mm film photography, Kodak Portra 400 color stock, natural film grain. A solitary figure walking barefoot along wet sand at the shoreline, seen from behind in a medium-long shot. Golden hour backlight creates a warm rim glow around the silhouette, long shadow stretching toward the camera. Calm turquoise ocean with gentle foam, dramatic orange and purple sunset sky with scattered clouds. Horizon line placed on the upper third. Melancholic, contemplative atmosphere. 16:9 widescreen composition. No text, no watermark, no distorted limbs.
```

输出：

- 3 张图。
- 对比 3 条提示词造成的画面差异。

### Day 2：复杂指令遵循

练习：同时给出 7 个约束。

```text
Create a square poster for an imaginary coffee brand named "MORNING CODE". The poster must include: one glass cup of iced latte in the center, a silver laptop on the left, a small green plant on the right, morning sunlight from the upper left, clean white desk background, headline text "MORNING CODE" at the top, subtitle "Coffee for focused makers" below the cup. Minimal modern editorial style, soft shadows, high-end product photography. Text must be exact, no extra letters, no watermark.
```

检查清单：

- 品牌名是否准确。
- 左右物体是否位置正确。
- 主副标题是否完整。
- 光线是否来自左上方。

### Day 3：文字渲染专项

练习：中文海报文字。

```text
一张现代中文活动海报，主题是「2026 夏季 AI 创作营」。主标题位于画面上方居中，必须逐字写出「2026 夏季 AI 创作营」。副标题位于标题下方：「用提示词完成你的第一套作品集」。画面主体是一张干净的工作桌，上面有平板电脑、手写笔、咖啡和色卡。明亮自然光，现代教育品牌视觉，留白充足，文字清晰可读，不要多余文字，不要水印。
```

迭代方向：

- 如果文字错：加入“verbatim, no extra characters, no substitutions”。
- 如果排版乱：明确主标题、副标题、主体图的位置。
- 如果信息过多：删掉次要物体。

### Day 4：对话式迭代

第一轮提示词：

```text
生成一张竖版手机壁纸，主题是“深夜学习中的 AI 工作者”，画面中有一个人在电脑前写提示词，窗外是城市夜景，氛围安静、专注、略带未来感。
```

第二轮修改：

```text
保持构图不变，把整体色调改得更温暖，屏幕上的光照亮人物脸部，桌面更整洁，不要赛博朋克感。
```

第三轮修改：

```text
增加一个小标题文字：“FOCUS MODE”，放在画面底部，字体简洁，文字必须准确可读。
```

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

## 7. 第 2 周：六维度万能公式与美学描述

核心笔记：[[提示词六维度万能公式]]

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
一只杯子放在桌上。
```

示例扩写：

```text
A handcrafted ceramic coffee mug with subtle speckled texture, placed on a warm oak desk beside an open notebook and a fountain pen. Morning window light from the right creates soft shadows and gentle highlights on the ceramic surface. Cozy editorial still-life photography, muted green and cream color palette, shallow depth of field, 50mm lens look. High detail, natural texture, no logo, no watermark, no extra text.
```

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

示例：

```text
Portrait of a young creator in a crisp white shirt sitting at a wooden desk, looking directly at the camera. Rembrandt lighting from upper left creates a small triangle of light on the shadow side of the face, deep but soft shadows, cinematic brown and teal color grading, medium close-up, 85mm lens look, realistic skin texture, no watermark, no extra fingers.
```

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

质量约束示例：

```text
high detail, clean composition, realistic materials, coherent perspective, readable text, no watermark, no extra objects, no distorted geometry, no blurry details.
```

### Day 5：本周小作品

任务：做一组“同一主题五风格”练习。

提交：

- 5 条提示词。
- 5 张图。
- 1 张对比表：主体、光线、风格、质量约束分别如何影响结果。

## 8. 第 3 周：人像摄影专项

核心笔记：[[人像摄影提示词模板]]

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

示例：

```text
35mm street photography, natural candid portrait of a young woman wearing an oversized beige trench coat and white sneakers, walking across a quiet city crosswalk after light rain. Soft overcast daylight, wet asphalt reflecting storefront lights, relaxed expression, hair moving slightly in the breeze. Medium shot from eye level, subtle film grain, muted urban color palette, realistic skin texture. No watermark, no beauty filter, no distorted hands.
```

练习：

- 改成人物性别、服装、城市、天气四个变量。
- 生成 2 张不同氛围街拍。

### Day 2：胶片复古

示例：

```text
Kodak Portra 400 film portrait, a thoughtful young man in a dark green knit sweater sitting beside a sunlit window in an old bookstore. Warm afternoon window light, dust particles in the air, shallow depth of field, 50mm lens, soft natural grain, slightly faded colors, nostalgic quiet mood. Authentic skin texture, gentle expression, no watermark, no plastic skin, no extra fingers.
```

练习：

- 分别使用 `Kodak Portra 400`、`Fujifilm Pro 400H`、`Ilford HP5 black and white` 写 3 条提示词。
- 比较色彩和情绪差异。

### Day 3：电影质感

示例：

```text
Cinematic portrait still, a tired female detective standing under a flickering subway platform light at midnight, wearing a dark coat and holding a paper coffee cup. Mixed green fluorescent and warm practical lighting, deep shadows, anamorphic lens flare, shallow depth of field, tense quiet atmosphere, teal and amber color grade, realistic skin pores and fabric texture. 16:9 frame, no text, no watermark, no distorted anatomy.
```

练习：

- 设计 2 个角色：侦探、音乐人、创业者、医生任选。
- 每个角色写 1 条电影感人像提示词。

### Day 4：国风人像

示例：

```text
Chinese guofeng portrait, an elegant young woman wearing a light ivory hanfu with subtle embroidered cloud patterns, standing beside a misty lake pavilion. Soft morning fog, diffused sunlight, ink-wash inspired background, restrained jade green and warm ivory palette, graceful posture, calm expression, long black hair with simple hairpin. Fine art portrait photography mixed with Chinese watercolor aesthetics, delicate fabric texture, no watermark, no extra jewelry, no distorted hands.
```

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

## 9. 第 4 周：海报设计与文字渲染

核心笔记：[[海报设计提示词模板]]

本周目标：

- 练习视觉层级、文字位置、海报类型和中文文字渲染。
- 能做城市、产品、中式、电影四类海报。

### Day 1：海报公式

海报提示词结构：

```text
海报类型 + 主视觉 + 文案内容 + 排版位置 + 色彩方案 + 风格 + 输出约束
```

示例：

```text
Modern vertical poster for an AI creativity workshop. Main visual: a glowing tablet on a clean desk, with colorful image-generation thumbnails floating above it. Top headline text must read exactly "AI 创作营". Subtitle below: "从提示词到作品集". Bottom area includes date "2026.06.01" and location "Shanghai". Clean grid layout, generous white space, blue and warm orange accent colors, modern education brand style, sharp readable Chinese typography, no extra text, no watermark.
```

### Day 2：城市旅游海报

示例：

```text
Vintage travel poster illustration of Hangzhou, panoramic West Lake scene with Leifeng Pagoda, arched stone bridge, lotus leaves and distant green hills. Warm sunset sky, calm lake reflection, limited color palette of jade green, cream, coral orange and deep blue. Large text at top: "HANGZHOU". Smaller Chinese text at bottom: "西湖春日". 1960s screen print texture, elegant retro typography, clean composition, no watermark, no extra letters.
```

练习：

- 为你熟悉的城市做 1 张旅游海报。
- 必须包含 3 个城市地标。
- 必须有英文或中文城市名。

### Day 3：产品广告海报

示例：

```text
Futuristic product launch poster for a smart notebook named "NOTE X". Main visual: a slim black digital notebook floating in the center with a silver stylus, exploded view showing screen layers and magnetic hinge. Dark charcoal background with cyan technical wireframe elements. Headline at top: "NOTE X". Subtitle below product: "Think, sketch, create". Thin specification callouts around the product, Apple keynote meets cyberpunk minimal aesthetic, high contrast lighting, readable text, no watermark.
```

练习：

- 虚构一个产品：咖啡、耳机、香水、笔记本、护肤品任选。
- 做一张发布会海报。

### Day 4：中式美学海报

示例：

```text
Chinese aesthetic vertical poster for a tea culture exhibition. Main visual: a celadon teacup on a dark wooden table, steam rising into the shape of misty mountains. Background with subtle ink wash texture and large negative space. Main Chinese title at upper right: "茶山之间". Small subtitle at bottom: "一盏茶里的东方美学". Muted ink black, celadon green and warm ivory palette, elegant serif Chinese typography, calm and poetic mood, print-ready quality, no extra text, no watermark.
```

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

## 10. 第 5 周：UI 与社交媒体截图

核心笔记：[[UI与社交媒体截图提示词模板]]

本周目标：

- 学会把界面拆成状态栏、导航、内容区、底部栏、浮层、评论、商品卡等组件。
- 做出可信的 App Store 截图、小红书图、直播截图、微信聊天截图。

### Day 1：UI 描述清单

练习模板：

```text
iOS App Store marketing screenshot, iPhone 15 Pro frame, a habit tracking app named "Daily Spark". Main screen shows a clean dashboard with today's habits, circular progress ring, streak count, and three habit cards. Top navigation bar with title "Today". Bottom tab bar with icons for Home, Calendar, Stats, Settings. Light mode, SF Pro font, soft green accent color, clean professional UI, realistic mobile screenshot, 9:19.5 ratio, readable text, no watermark.
```

检查：

- 是否像真实手机截图。
- 是否有清楚的信息架构。
- 是否出现乱码或不合理按钮。

### Day 2：小红书封面

示例：

```text
Xiaohongshu style cover image, 3:4 vertical. Topic: "5个AI出图提示词技巧". Clean lifestyle desk background with laptop, color swatches, coffee and small notebook. Large bold Chinese title centered: "5个AI出图技巧". Smaller subtitle: "新手也能稳定出片". Fresh white and coral color palette, soft daylight, modern creator aesthetic, readable Chinese text, no watermark, no extra text.
```

练习：

- 做 3 张不同主题的小红书封面。
- 主题建议：AI绘画入门、人像提示词、海报文字渲染。

### Day 3：直播截图

示例：

```text
Chinese e-commerce livestream screenshot, 9:16 vertical. A friendly female host holding a glass skincare serum bottle in a bright studio. Live interface includes viewer count "12.8万", floating likes, shopping cart icon with red discount tag "限时半价", pinned product card showing "修护精华液 ¥99", scrolling comments "质地清爽吗？", "敏感肌能用吗？". Warm high-key lighting, authentic Douyin livestream UI, readable Chinese text, no watermark.
```

练习：

- 选择一个商品，设计直播画面。
- 必须包含主播、商品卡、评论、价格、折扣标签。

### Day 4：微信聊天截图

示例：

```text
WeChat mobile chat screenshot, 9:16 vertical, light mode. Chat between "设计师小林" and "客户王姐". Messages discuss an AI poster revision: "标题可以再大一点吗？", "可以，我会把主视觉往下移。", "颜色想更高级一点。", "我改成墨绿和米白的配色试试。". WeChat UI elements include time stamp, green right-side bubbles, white left-side bubbles, simple avatars, input bar at bottom. Realistic iOS screenshot style, readable Chinese text, no watermark, no extra messages.
```

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

## 11. 第 6 周：角色设计与电商产品图

核心笔记：[[角色设计提示词模板]]、[[电商产品图提示词模板]]

本周目标：

- 完成一个原创角色设定。
- 完成一组电商产品图：白底、场景、广告。

### Day 1：角色设定表

示例：

```text
Character design sheet for an original AI librarian character. A calm young woman with short silver hair, round glasses, navy blue long coat, glowing bookmark-shaped earrings, and a small floating digital book companion. Clean white background. Full body front view, three-quarter view, side view, and close-up headshot. Include color palette swatches of navy, silver, warm ivory and cyan. Semi-realistic anime illustration style, consistent outfit and facial features across all views, professional concept art sheet, no watermark.
```

练习：

- 创作 1 个原创角色。
- 写清楚身份、外形、服装、道具、色彩、性格。

### Day 2：多角度转盘

示例：

```text
Character turnaround sheet, original fantasy courier character, young man wearing a short brown travel jacket, cream scarf, utility belt, leather boots, and a small mechanical bird on his shoulder. Five views on clean white background: front, 3/4 left, side profile, 3/4 right, back. Consistent costume details across all angles, color palette swatches below, height marker on the side, animation production quality, no watermark.
```

练习：

- 给 Day 1 角色生成五视图。
- 观察一致性问题，记录哪些细节最容易丢。

### Day 3：表情包/动作表

示例：

```text
Character expression sheet of the AI librarian character in chibi sticker style. Grid of 9 expressions: happy, focused, surprised, confused, proud, sleepy, worried, laughing, frustrated. Consistent short silver hair, round glasses, navy coat and glowing bookmark earrings. Clean transparent-like white background, sticker-ready quality, bold clean outlines, no watermark.
```

练习：

- 做 9 格表情。
- 选 3 个最适合社交传播的表情。

### Day 4：电商产品图三模式

商品：任选一个真实或虚构产品。

白底棚拍示例：

```text
Clean white background product photography of a matte black insulated water bottle, standing upright at a slight three-quarter angle. Softbox lighting from upper left, subtle shadow on the floor, crisp metal texture, readable small logo "NOVA", high-end e-commerce main image, 1:1 square, no props, no watermark.
```

场景图示例：

```text
Lifestyle product photography of a matte black insulated water bottle placed on a hiking trail rock beside a folded map and compass. Morning mountain light, cool misty background, rugged outdoor mood, water droplets on the bottle surface, shallow depth of field, premium outdoor brand aesthetic, 4:5 ratio, no watermark.
```

广告图示例：

```text
Dynamic advertising poster for a matte black insulated water bottle named "NOVA". The bottle floats in the center with splashing water and ice fragments around it, dark blue gradient background, dramatic rim light, bold headline text "STAY COLD" at top, small subtitle "24H insulated bottle" below, high contrast commercial photography, readable text, no watermark.
```

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

## 12. 第 7 周：C.L.E.A.R. 提示词工程与风格混合

核心笔记：[[C.L.E.A.R.框架]]、[[风格混合策略]]

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

第 1 版：

```text
一张咖啡豆包装产品图，高级、好看、有品牌感。
```

第 2 版：

```text
Premium product photography of a kraft paper coffee bean bag named "ROAST LAB", placed on a dark walnut table with roasted coffee beans scattered around. Warm side light from the left, soft shadow, clean dark background, readable label text, high-end cafe brand aesthetic, no watermark, no extra text.
```

第 3 版：

```text
Premium product photography for a specialty coffee brand. Main subject: a matte kraft paper coffee bean bag labeled exactly "ROAST LAB" and "ETHIOPIA YIRGACHEFFE", standing upright at the center on a dark walnut table. Supporting props: a small ceramic cup on the right and a few roasted beans in the foreground. Warm side light from upper left creates a golden rim on the bag edge, background falls into soft shadow. Minimal editorial composition, 4:5 ratio, readable label, no extra letters, no watermark, no messy props.
```

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

示例：中式水墨 × 赛博朋克。

```text
A futuristic Chinese ink-wash cityscape, 65% traditional ink painting and 35% cyberpunk. Medium and composition come from Chinese shanshui painting: layered misty mountains, flowing river, large negative space, expressive ink brush texture. Cyberpunk elements appear only in the city details: neon signs, holographic bridges, glowing windows and subtle magenta-cyan reflections on water. Restrained black ink, jade green and small neon accents. Poetic, atmospheric, not cluttered, no watermark, no extra text.
```

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

## 13. 第 8 周：商业路径与毕业作品集

核心笔记：[[商业变现路径]]

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

## 14. 练习库

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

## 15. 作品评分表

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

## 16. 推荐学习节奏清单

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

## 17. 下一步知识库建设建议

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

