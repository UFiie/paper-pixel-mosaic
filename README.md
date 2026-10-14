# 🎨 Paper Pixel Mosaic

**Photography × Watercolor Square Collage**

将普通照片转化为清新、明亮、富有手工纸张质感的水彩方格拼贴艺术海报。

*Transform your photographs into elegant watercolor paper mosaics, combining authentic photography with handcrafted square-tile collage art.*

---

## ✨ About / 项目介绍

**Paper Pixel Mosaic** 是一个基于自然语言提示词的 AI 图片生成 Skill，专门用于将输入照片重新演绎为 **3:4 竖版「摄影 × 水彩方格拼贴」艺术海报**。

海报分为上下两部分：

- **上半部分：真实摄影** — 保留原始照片的主体、构图、色彩和真实摄影质感。
- **下半部分：水彩方格重构** — 将照片主体重新绘制为数百枚手工水彩纸片组成的艺术拼贴。

通过柔和的水彩晕染、纸张纤维、细微色差与自然的边缘消散，让照片呈现出介于真实摄影与手工艺术之间的独特视觉效果。

## 🖼️ Gallery / 效果展示

以下为使用 Paper Pixel Mosaic 风格制作的视觉效果示例。

### Example 01

![Paper Pixel Mosaic Example 01](assets/p1%20%281%29.png)

---

## 🌿 Core Features / 核心特色

**01 — Photography Preservation / 摄影保留**

上半部分保留原照片的真实视觉信息，仅进行必要裁切，延续照片原有的光线、构图与色彩氛围。

**02 — Watercolor Square Reconstruction / 水彩方格重构**

通过约 30–45 格横向排列的水彩纸片重构原始照片主体。每枚方格具有独立的颜色与水彩纹理。

**03 — Handmade Paper Texture / 手工纸张质感**

采用暖白色水彩纸背景，模拟颜料沉积、纸张纤维、轻微折痕与自然晕染，避免机械化的数码像素效果。

**04 — Dissolving Mosaic Edges / 方格边缘消散**

主体内部保持完整，外围方格逐渐疏散，形成自然、轻盈且富有呼吸感的拼贴边界。

**05 — Minimal Typography / 极简文字排版**

支持用户指定短句、自动生成简短英文文案或不添加文字。默认采用灰蓝色细线手写体，让文字自然融入留白区域。

---

## 🚀 How to Use / 使用方法

### 1. 使用 ChatGPT

上传一张照片，并提供以下指令：

> 请读取并参考以下 GitHub Skill：
>
> https://github.com/SwaggyU/paper-pixel-mosaic
>
> 按照 `SKILL.md` 中的设计规范，将我上传的照片转换为 3:4 竖版摄影与水彩方格拼贴艺术海报。

也可以进一步指定文字内容：

> 按照 paper-pixel-mosaic Skill 处理这张照片，文案使用 "Where memories become colors."

或者：

> 按照 paper-pixel-mosaic Skill 处理这张照片，不添加任何文字。

**注意：** GitHub 仓库用于保存和分享设计规范。能否直接读取仓库、自动加载 Skill，取决于所使用的 AI 工具与运行环境。请确保生成工具能够访问 `SKILL.md`，必要时手动提供文件内容。

### 2. 通过 SKILL.md 使用

本项目的完整生成规范保存在：

**[SKILL.md](SKILL.md)**

可以在支持自定义提示词或 Skill 的 AI 图片生成工作流中参考使用。

---

## 📐 Design Specifications / 设计规范

| 项目 | 规范 |
|---|---|
| Aspect Ratio / 画面比例 | 3:4 Portrait |
| Layout / 版式 | 50% Photography + 50% Mosaic |
| Grid / 方格结构 | Approximately 30–45 squares across the subject |
| Material / 材质 | Transparent watercolor on handmade paper |
| Background / 背景 | Warm off-white watercolor paper |
| Edges / 边缘 | Irregular, softly dissolving square fragments |
| Typography / 文字 | Optional gray-blue handwriting |
| Overall Mood / 整体风格 | Fresh, bright, delicate, handcrafted |

---

## 📁 Repository Structure / 仓库结构

```text
paper-pixel-mosaic/
├── SKILL.md
├── README.md
└── assets/
    ├── p1 (1).png
    ├── p1 (2).jpg
    ├── p1 (3).jpg
    ├── p1 (4).jpg
    └── p1 (5).jpg
```

- `SKILL.md` — 完整的设计和图片生成规范
- `README.md` — 项目介绍、效果展示及使用说明
- `assets/` — 视觉效果参考图片

---

## 🎯 Design Philosophy / 设计理念

**Keep the photograph real. Let the colors become paper.**

保留摄影的真实，让色彩化作纸片。

Paper Pixel Mosaic 不追求简单的照片像素化，而是尝试通过数百枚独立的水彩纸片，将照片重新转化为富有温度的手工艺术作品。

每一枚方格都是色彩的片段，每一处留白都是画面的呼吸。

---

## 📄 License / 许可说明

本项目的提示词规范及示例图片版权归各自权利人所有。使用与转载前请确认相应授权。
