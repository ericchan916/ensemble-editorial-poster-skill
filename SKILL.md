---
name: ensemble-editorial-poster
description: 多人物叙事编辑海报：围绕一个主题，设计 4–7 位年龄、身份、性格、姿态与关系各不相同的人物，用一种主图形系统（超大字体 / 分层色带 / 几何切割 / 环形构图 / 自由拼贴 / 不规则肖像网格）生成一张 9:16 高端群像编辑海报。当用户提到"多人物海报 / 群像海报 / 电影群像 / ensemble poster / editorial poster"时使用。Use when the user asks for an ensemble poster, a multi-character editorial or film-style cast poster about a theme — produces one story-driven 9:16 poster with varied figure scales, bold English typography and a single strong graphic system.
license: MIT
---

# 多人物叙事编辑海报 · Ensemble Editorial Poster

不是合影，是一个故事：4–7 个不同的人，为什么出现在同一张海报里。
Not a group photo, but a story: why these 4–7 different people belong in one poster.

## 输入 · Inputs

```
THEME:            (required)
VISUAL STRUCTURE: oversized typography / layered bands / geometric cuts /
                  circular composition / freeform collage / irregular portrait grid
COLOR PALETTE:
TITLE:
```

## 使用规则 · Agent rules
- **不要追问，不输出分析 / Never ask, never show analysis.**
- VISUAL STRUCTURE 缺失 → 选最契合主题的一种。Missing → pick the best fit.
- COLOR PALETTE 缺失 → 由主题与情绪推导一个克制的编辑配色。Missing → derive from theme and mood.
- TITLE 缺失 → 写一个自然的 1–4 词英文标题。Missing → write a natural 1–4 word English title.
- 在内部默默设计人物群像：每人的年龄、身份、性格、姿态，以及彼此关系与把他们连在一起的故事。Silently design the cast and the story that binds them.
- 次要文字必须有意义：类似片头署名的人物名单、宣传语、地点/时间线索，不要 lorem ipsum 或无意义填充。Secondary text must be meaningful (credits-style lines, taglines), never filler.
- 所有可见文字为英文。All visible text in English.
- 只输出一张海报；环境不能生图时，输出已填好的 [prompt.md](prompt.md) 提示词。

示例见 [examples/themes.md](examples/themes.md)。

## 核心规则 · Core rules

### 人物 · Cast
- 4–7 位明显不同的人物：年龄、角色、性格、姿态、关系各异。
- 构建可信的故事，说明他们为何同在一张海报里。

### 图形系统 · Visual structure
以一种结构为主图形系统：oversized typography / layered bands / geometric cuts / circular composition / freeform collage / irregular portrait grid。

### 尺度与裁切 · Scale & cropping
- 大、中、小人物混用：全身、半身、特写、侧脸、局部裁切。
- 避免人物等大、等距排列。

### 人与字形融合 · Integration
人物与字体、图形通过叠压、蒙版、负空间、裁切、前后景关系融为一体。

### 色彩与字体 · Color & type
使用 COLOR PALETTE + 大胆的编辑字体；主标题为 TITLE；所有可见文字为英文。

### 质量 · Quality
构图丰富、大胆、有叙事、高度设计感；缩略图冲击力强；信息密度有意义。

### 风格 · Style
当代文化海报、电影群像海报、独立杂志、韩国编辑设计、欧洲平面设计、写实编辑摄影。

### 避免 · Avoid
普通合影、重复面孔、同龄人物、僵硬卡片、简单图文块、规则网格、无意义填充文字、企业海报风、3D 字体、水印、编号、闪光符号。
