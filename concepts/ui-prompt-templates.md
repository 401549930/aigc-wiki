---
title: UI与社交媒体截图提示词模板
created: 2026-05-12
updated: 2026-05-12
type: concept
tags: [text-to-image, prompt-engineering, method, tutorial]
sources: [raw/articles/gpt-image-2-guide.md]
---

# UI与社交媒体截图提示词模板

## 核心思路
生成逼真 UI 截图的关键是**逐元素列举**。不要说"一个直播间截图"，要说出每一个可见的 UI 元素。

## UI 描述清单
- 屏幕比例（9:16 竖屏 / 16:9 横屏 / 1:1 方屏）
- 顶部状态栏（时间、信号、电量）
- 导航栏元素
- 主要内容区域
- 互动元素（点赞数、评论数、分享按钮）
- 底部操作栏
- 浮层元素（弹幕、礼物动画、通知）
- 具体文字内容（使用中文）

## 模板

### 抖音直播截图（@Shinning1010 UI Case 36）
```
A 9:16 vertical, high-detail realistic style Chinese Douyin live screenshot.
[主播描述] is talking to the mobile phone camera in the live broadcast room,
[表情]. There are obvious Douyin interface elements: likes, comments and
share icons arranged vertically on the right, scrolling Chinese bullet
screens and interactive comments below. The live broadcast room shows:
number of online viewers [数字], popularity heat [数字], gifts animation
showing [礼物类型] from user named "[用户名]". The overall picture
simulates the real Douyin live broadcast effect.
```

### 小红书配图
```
Xiaohongshu (RED) social media post, 3:4 vertical ratio. High quality
lifestyle photo: [主体] in [场景], [光线描述], [色调] aesthetic.
Overlaid text in Chinese: "[标题文案]" in bold at top. Clean, aspirational
lifestyle blogger aesthetic, warm tones, natural looking but polished.
```

### Instagram 帖子
```
Instagram post screenshot, 1:1 square ratio. Photo: [内容描述],
[滤镜] filter. Instagram UI overlay: profile icon with username "[用户名]",
heart icon with "[点赞数]" likes, bookmark and comment icons.
Caption: "[文案]". Time posted: [时间].
```

### 电商直播截图
```
Chinese e-commerce livestream screenshot, 9:16 vertical. [主播描述] holding
[商品] in brightly lit studio. Live interface: viewer count [数字],
like animation, shopping cart icon with "[折扣]" tag, pinned product card
showing [商品名] at ¥[价格]. Scrolling comments: "[评论1]", "[评论2]".
Warm high-key lighting, authentic livestream quality. No watermark.
```

### 微信聊天截图
```
WeChat mobile chat screenshot, 9:16 vertical. Chat between "[用户A]"
and "[用户B]". Messages: [对话内容，3-5条消息]. WeChat UI elements:
green send button, voice message button, emoji keyboard hint, time stamps,
read receipts. [用户A] avatar on left, [用户B] on right.
Authentic WeChat iOS dark/light mode interface. No watermark.
```

### App Store 截图
```
iOS App Store marketing screenshot, iPhone 15 Pro frame, [App类型] app.
[主界面描述]. Navigation bar with [菜单项]. Main content: [核心功能展示].
Bottom tab bar with [图标]. [设计风格] design language, [颜色] accent color.
Inter/SF Pro font. Light mode, clean professional UI. 9:19.5 ratio.
No watermark.
```

## 分层流模板设计模式
适用于复杂 UI：
```
[整体规格] 9:16 vertical, mobile app screenshot.
[顶部区域] Navigation bar: logo on left, search icon on right.
[中部区域] Hero card: user avatar, greeting "Hi, Sarah", activity ring 72%.
[图表区域] Weekly bar chart: 7 days of step data, green gradient.
[底部区域] Tab bar: 4 icons — Home, Activity, Social, Profile.
[全局约束] Inter font, SF-style icons, 12px rounded corners, light mode.
```

## 相关页面
- [[提示词六维度万能公式]] — 基础方法论
- [[C.L.E.A.R.框架]] — 分层流设计模式
- [[GPT Image 2]] — 适用模型
- [[角色设计提示词模板]]

## 参考文献
- [GPT Image 2 创作实战指南，第 7 章](../raw/articles/gpt-image-2-guide.md)
