#  Yushan · 飞书 CLI 画板

50 种配色风格 + 6 种内容版式，让 AI 帮你生成漂亮、可编辑的飞书画板。

##   Preview

**[ 在线预览所有 50 种风格](https://chenyushan0204-bot.github.io/feishu-whiteboard-styles/)**

##   Quick Install

在安装了 Claude Code 的终端中执行：

```bash
npx skills install chenyushan0204-bot/feishu-whiteboard-styles
```

如果你的 Claude Code 不支持 `npx skills`，也可以手动克隆到 skills 目录：

```bash
git clone https://github.com/chenyushan0204-bot/feishu-whiteboard-styles.git \
  ~/.claude/skills/beautiful-feishu-whiteboard/
```

> **前置条件**：需要有飞书/Lark 账号，并安装 `lark-cli`（`npm install -g @larksuite/cli`）。

##   Usage

安装后，在 Claude Code 中直接跟 AI 说：

- "画一个项目架构图，用赛博朋克风格"
- "把这篇文章总结成白板，极简瑞士风"
- "生成一个客户旅程地图，粘土风"

AI 会自动从 50 种风格里选合适的配色，生成可编辑的飞书画板。

##   What's Included

| 内容 | 说明 |
|---|---|
| `SKILL.md` | 技能主文件 |
| `CATALOG.md` | 50 种风格目录（英文名、形式感、氛围） |
| `RULES.md` | 飞书 SVG 白板硬规则 |
| `templates/*/design.md` | 每种风格的色板和使用指南 |
| `index.html` | 50 风格画廊（本地打开即可浏览） |
| `pngs/` | 50 张示例图 |

##   All 50 Styles

Apricot Arc · Avocado Press · BlockFrame · Burst Panel · Cobalt Bloom · Cobalt Glaze · Confetti Wedge · Court Press · Crayon Stack · Cut Bloom · Grove Block · Jade Lens · Lime Slab · Linen Cut · Mint Brut · Neo-Grid Bold · Papier Bleu · Raw Grid · Reading Room · Riptide Cobalt · Riso Brut · Salmon Stamp · Specimen Bold · Violet Marker · Minimal Swiss · Neumorphism · Glassmorphism · Brutalism · Vibrant Block · Dark OLED · Claymorphism · Aurora UI · Retro-Futurism · Flat Design · Neubrutalism · Bento Grid · Y2K Aesthetic · Cyberpunk UI · Organic Biophilic · AI-Native UI · Memphis Design · Vaporwave · Dimensional Layering · Exaggerated Minimalism · Swiss Modernism 2.0 · HUD Sci-Fi · E-Ink Paper · Editorial Magazine · Vintage Analog · Nature Distilled
