# ClaudeBaseline

[English](./README.md) | **中文**

一个 Obsidian 主题：保留 [Baseline](https://github.com/aaaaalexis/obsidian-baseline) 的布局、组件与动效，替换为暖色、Claude 风的配色与排版。

ClaudeBaseline 是一层薄样式，而不是 fork。工作区布局、标注块、表格、移动端行为、过滤类、以及每一处动画都原样来自 Baseline。改变的只有颜色与字体。

| 浅色 | 深色 |
| :---: | :---: |
| [![ClaudeBaseline 浅色](./screenshot-light.jpg)](./Fig1.jpg) | [![ClaudeBaseline 深色](./screenshot-dark.jpg)](./Fig2.jpg) |

*点击截图查看原尺寸。*

> 想要玻璃效果？[CLaudeApple](https://github.com/dingye0604/CLaudeApple) 建立在本主题之上，追加磨砂面板，并可选启用 Windows 11 原生 Acrylic。

## 本主题改了什么

**配色。** 暖色陶土强调色（`#cc7d5e`）搭配暖中性色——浅色模式 `#f9f9f7`，深色模式 `#2d2d2b`。链接、标签、引用块竖线、表格与语义色都重新调校，以适配这些底色，而非 Baseline 的默认值。

**排版。** 正文与标题使用衬线字体，界面使用系统无衬线字体，代码使用等宽字体。行高与标题层级按长文阅读设定。

**代码高亮。** 深浅色各一套代码配色，在暖色底上保持可读，不落入常见的冷蓝灰调。

其余的一切都是 Baseline，未作改动。

## 安装

### 从社区主题库

1. 打开 **设置 → 外观 → 主题 → 管理**
2. 搜索 **ClaudeBaseline**
3. 选择 **安装并使用**

### 手动安装

1. 从 [最新 release](https://github.com/dingye0604/ClaudeBaseline/releases/latest) 下载 `manifest.json` 和 `theme.css`
2. 在 `<你的库>/.obsidian/themes/` 下新建文件夹 `ClaudeBaseline`
3. 把两个文件放进去
4. 重启 Obsidian，然后在 **设置 → 外观 → 主题** 中选择 **ClaudeBaseline**

## 可选：Style Settings

[Style Settings](https://github.com/mgmeyers/obsidian-style-settings) 不是必需的，但 Baseline 通过它暴露了工作区布局选项——Baseline、Fusion、Cupertino、macOS、Classic 与 Minimal。想在它们之间切换就装上。

## 致谢

ClaudeBaseline 是派生作品，你看到的大部分是别人的工作。该署的名一个都不能少。

### 上游主题

**[Baseline](https://github.com/aaaaalexis/obsidian-baseline)**，作者 [aaaaalexis](https://github.com/aaaaalexis)，MIT 许可。

ClaudeBaseline 就是替换了配色与排版系统的 Baseline。全部布局、组件与动效代码属于 Baseline。如果你喜欢这个主题**的行为**，那是 Baseline 的功劳。

### 内嵌字体

- **Instrument Serif**——Copyright 2022 The Instrument Serif Project Authors（<https://github.com/Instrument/instrument-serif>），设计者 Rodrigo Fuenzalida 与 Jordan Egstad。[SIL Open Font License 1.1](https://openfontlicense.org) 授权，以 base64 WOFF2 形式内嵌于 `theme.css`。
- **Inter**——作者 Rasmus Andersson，SIL Open Font License 1.1。仅按名称引用，随 Obsidian 分发。

### Baseline 内已致谢的配色方案

Baseline 打包了改编自其他开源主题的配色预设。这些预设随 `theme.css` 一同分发，Baseline 在其源码中已致谢其作者：

- **Catppuccin**（Latte、Frappe、Macchiato、Mocha）— Catppuccin
- **Dracula** — Dracula
- **Nord** — Sven Greb（[svengreb](https://github.com/svengreb)）
- **Gruvbox** — Pavel Pertsev（[morhetz](https://github.com/morhetz)）
- **Solarized** — Ethan Schoonover（[altercation](https://github.com/altercation)）
- **Rosé Pine** — Rosé Pine
- **Everforest** — Sainnhe Park（[sainnhe](https://github.com/sainnhe)）
- **Flexoki** — Steph Ango（[kepano](https://github.com/kepano)）
- **Melange** — Sergio A. Vargas（[savq](https://github.com/savq)）
- **Sanctum** — José Daniel Mourão（[jdanielmourao](https://github.com/jdanielmourao)）
- **Tiniri** — Vlad Gerasimov（[vladstudio](https://github.com/vladstudio)）
- **Admin** — Konstantin Pschera（[k15a](https://github.com/k15a)）
- **Border** — [Akifyss](https://github.com/Akifyss)
- **Iridium** — [kyffa](https://github.com/kyffa)
- **Customization extras** — Bradley Wyatt（[bwya77](https://github.com/bwya77)）

Baseline 自己的 README 还致谢了作为借鉴来源的社区主题 **Minimal**（[kepano](https://github.com/kepano)）、**AnuPpuccin**（[AnubisNekhet](https://github.com/AnubisNekhet)）、**Sanctum**、**Tiniri**、**Border**、**Iridium**，作为附加内容的 **Chill Jinshu Song**（Warren2060）与 **Obsidian Baseline Theme Customization**（bwya77），以及作为工作区灵感的 **Craft Docs**。权威名单请以 [Baseline 仓库](https://github.com/aaaaalexis/obsidian-baseline) 为准。

### 灵感来源

配色与排版方向受 **Claude** 启发。

## 免责声明

这是独立的社区主题，**与 Anthropic 无隶属、赞助或背书关系**。「Claude」是 Anthropic PBC 的商标，此处仅用于描述本主题所借鉴的视觉风格。

## 许可

[MIT](./LICENSE) © ClaudeBaseline 作者，包含 Baseline © 2025 aaaa​alexis。

内嵌与引用的字体另有 SIL Open Font License 1.1 授权，见 [致谢](#致谢)。
