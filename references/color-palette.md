# Color Palette & Brand Style

**This file defines the visual identity of the diagram skill.**
You can keep multiple brand themes in this file and switch between them per use case.

---

## How to use this file

There are now **three predefined themes**:
1. **Default / Universal** — 原始默认主题，通用、干净、解释型
2. **技术指南针 / Tech Compass** — 冷静、科技、理性，适合技术文章、系统架构图、对比图、教程图
3. **小红书 IP / Warm Creator** — 温馨、亲和、柔和，适合内容配图、科普图、日常分享图、人物/IP 相关内容

### Theme switching rule
When generating a diagram, pick the theme that matches the scene:
- **Default / Universal**
  - 用户没有指定品牌风格
  - 通用解释图
  - 中性流程图 / 架构图 / 教学图
- **技术指南针 / Tech Compass**
  - 技术文档
  - 架构图
  - 流程图
  - 对比图
  - 教程讲解图
- **小红书 IP / Warm Creator**
  - 小红书内容配图
  - 生活化科普
  - 轻内容解释图
  - 温馨人物 / 日常 / 陪伴感内容

If the user does not specify a theme:
- Default to **Default / Universal**
- Only switch to a brand theme when the user explicitly asks, or the context clearly belongs to that brand surface

---

# Theme 0 — Default / Universal

## Brand intent
- **Mood**: 干净、现代、通用、解释性强
- **Use for**: 默认图表、说明图、流程图、系统图、课程图
- **Visual keywords**: 清爽蓝、理性层级、低装饰、高可读性

## Shape Colors (Semantic)

| Semantic Purpose | Fill | Stroke |
|------------------|------|--------|
| Primary/Neutral | `#3b82f6` | `#1e3a5f` |
| Secondary | `#60a5fa` | `#1e3a5f` |
| Tertiary | `#93c5fd` | `#1e3a5f` |
| Start/Trigger | `#fed7aa` | `#c2410c` |
| End/Success | `#a7f3d0` | `#047857` |
| Warning/Reset | `#fee2e2` | `#dc2626` |
| Decision | `#fef3c7` | `#b45309` |
| AI/LLM | `#ddd6fe` | `#6d28d9` |
| Inactive/Disabled | `#dbeafe` | `#1e40af` |
| Error | `#fecaca` | `#b91c1c` |

## Text Colors (Hierarchy)

| Level | Color | Use For |
|-------|-------|---------|
| Title | `#1e40af` | Section headings, major labels |
| Subtitle | `#3b82f6` | Subheadings, secondary labels |
| Body/Detail | `#64748b` | Descriptions, annotations, metadata |
| On light fills | `#374151` | Text inside light-colored shapes |
| On dark fills | `#ffffff` | Text inside dark-colored shapes |

## Evidence Artifact Colors

| Artifact | Background | Text Color |
|----------|-----------|------------|
| Code snippet | `#1e293b` | Syntax-colored |
| JSON/data example | `#1e293b` | `#22c55e` |

## Default Stroke & Line Colors

| Element | Color |
|---------|-------|
| Arrows | `#1e3a5f` |
| Structural lines | `#64748b` |
| Marker dots | `#3b82f6` |

## Background

| Property | Value |
|----------|-------|
| Canvas background | `#ffffff` |

---

# Theme A — 技术指南针 / Tech Compass

## Brand intent
- **Mood**: 冷静、专业、清晰、可信
- **Use for**: 技术文档、系统架构、产品逻辑、教程图、公众号文章配图
- **Visual keywords**: 科技蓝、深海军蓝、理性紫、干净留白

## Shape Colors (Semantic)

| Semantic Purpose | Fill | Stroke |
|------------------|------|--------|
| Primary/Neutral | `#dbeafe` | `#1e3a5f` |
| Secondary | `#bfdbfe` | `#1d4ed8` |
| Tertiary | `#e0e7ff` | `#3730a3` |
| Start/Trigger | `#fed7aa` | `#c2410c` |
| End/Success | `#bbf7d0` | `#047857` |
| Warning/Reset | `#fee2e2` | `#dc2626` |
| Decision | `#fef3c7` | `#b45309` |
| AI/LLM | `#ede9fe` | `#6d28d9` |
| Inactive/Disabled | `#e5e7eb` | `#6b7280` |
| Error | `#fecaca` | `#b91c1c` |

## Text Colors (Hierarchy)

| Level | Color | Use For |
|-------|-------|---------|
| Title | `#1e40af` | Section headings, major labels |
| Subtitle | `#2563eb` | Subheadings, secondary labels |
| Body/Detail | `#64748b` | Descriptions, annotations, metadata |
| On light fills | `#374151` | Text inside light-colored shapes |
| On dark fills | `#ffffff` | Text inside dark-colored shapes |

## Evidence Artifact Colors

| Artifact | Background | Text Color |
|----------|-----------|------------|
| Code snippet | `#0f172a` | Syntax-colored |
| JSON/data example | `#111827` | `#22c55e` |

## Default Stroke & Line Colors

| Element | Color |
|---------|-------|
| Arrows | `#1e3a5f` |
| Structural lines | `#475569` |
| Marker dots | `#2563eb` |

## Background

| Property | Value |
|----------|-------|
| Canvas background | `#ffffff` |

---

# Theme B — 小红书 IP / Warm Creator

## Brand intent
- **Mood**: 温暖、亲和、柔和、治愈
- **Use for**: 小红书 IP、生活方式内容、轻科普、人物/陪伴型内容、故事型图解
- **Visual keywords**: 奶油杏、蜜桃粉、暖金、薄荷绿、柔和线条

## Shape Colors (Semantic)

| Semantic Purpose | Fill | Stroke |
|------------------|------|--------|
| Primary/Neutral | `#fff1e6` | `#b08968` |
| Secondary | `#ffe4e6` | `#c97b84` |
| Tertiary | `#fef3c7` | `#c08a2d` |
| Start/Trigger | `#fde68a` | `#b45309` |
| End/Success | `#dcfce7` | `#2f855a` |
| Warning/Reset | `#fee2e2` | `#d97706` |
| Decision | `#ffedd5` | `#c2410c` |
| AI/LLM | `#f3e8ff` | `#a855f7` |
| Inactive/Disabled | `#f3f4f6` | `#9ca3af` |
| Error | `#fecaca` | `#c2410c` |

## Text Colors (Hierarchy)

| Level | Color | Use For |
|-------|-------|---------|
| Title | `#9d4edd` | Section headings, major labels |
| Subtitle | `#ec4899` | Subheadings, secondary labels |
| Body/Detail | `#7c6f64` | Descriptions, annotations, metadata |
| On light fills | `#5b4b41` | Text inside light-colored shapes |
| On dark fills | `#ffffff` | Text inside dark-colored shapes |

## Evidence Artifact Colors

| Artifact | Background | Text Color |
|----------|-----------|------------|
| Code snippet | `#3f3f46` | Syntax-colored |
| JSON/data example | `#44403c` | `#86efac` |

## Default Stroke & Line Colors

| Element | Color |
|---------|-------|
| Arrows | `#b08968` |
| Structural lines | `#c97b84` |
| Marker dots | `#f59e0b` |

## Background

| Property | Value |
|----------|-------|
| Canvas background | `#fffaf7` |

---

## Implementation note

This file currently stores multiple themes as documented presets.
When generating diagrams, explicitly choose one theme and apply its color values consistently across:
- shape fills
- strokes
- text hierarchy
- arrows
- evidence artifacts
- canvas background

Do not mix themes in a single diagram unless the user explicitly wants a hybrid style.
