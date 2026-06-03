# 🎨 Yushan · 飞书 CLI 画板

50 种配色风格 + 6 种内容版式，让 Claude Code 帮你生成漂亮、可编辑的飞书画板。

## 🖥 预览

**[在线浏览所有风格](https://chenyushan0204-bot.github.io/feishu-whiteboard-styles/)** — 点开就能看 50 种配色 + 6 种版式的效果图，每个都附了提示词，挑一个复制就能用。

---

## 🚀 安装

### 1. 前置条件

```bash
# 需要 Node 20+
node -v

# 安装飞书 CLI
npm install -g @larksuite/cli

# 初始化认证（扫二维码登录飞书）
lark-cli config init --new
```

### 2. 安装技能

```bash
npx skills install chenyushan0204-bot/feishu-whiteboard-styles
```

安装后，Claude Code 就能识别 50 种风格了。

---

## 💬 怎么用

在终端打开 Claude Code，直接说话就行：

### 指定风格

```
画一个项目架构图，用赛博朋克风格。
```

```
把这段会议纪要总结成白板，极简瑞士风。
```

```
生成一个客户旅程地图，粘土风。
```

AI 会自动读取你对风格对应的色板文件，生成一个**可编辑的飞书画板**，返回飞书文档链接和预览图。

### 不指定风格，让 AI 推荐

```
画一个团队 onboarding 流程图，活泼一点的风格。
```

AI 会从 50 种里帮你挑最合适的。

### 换风格

生成完以后，直接说：

```
换成薄荷粗野风格试试。
```

AI 会用同一份内容，换一套配色重新渲染。

### 用内容版式

6 种内容版式是已经设计好的画板类型，直接告诉 AI 你要哪个：

```
画一个价值金字塔图，用极简瑞士风配色。
按 SaaS 仪表盘的版式，画我们的数据看板。
```

---

## 📁 文件结构

| 文件/目录 | 用途 |
|---|---|
| `SKILL.md` | 技能入口，Claude Code 读取这个文件知道怎么工作 |
| `CATALOG.md` | 50 种风格的目录表（中英文名、形式感、氛围） |
| `EXAMPLES.md` | 6 种内容版式的说明和提示词 |
| `RULES.md` | 飞书 SVG 白板的硬规则（字体、形状、阴影等限制） |
| `templates/*/design.md` | 每种风格的色板定义（hex 颜色、圆角、边框、阴影规则） |
| `index.html` | 风格预览画廊（双 tab：配色风格 + 内容版式） |
| `pngs/` | 50 张配色风格示例图 |
| `examples/images/` | 6 张内容版式示例图 |

---

## 🔧 怎么工作的

1. 你告诉 Claude Code 要画什么 + 用什么风格
2. Claude Code 读取 `CATALOG.md` 找到对应风格
3. 读取 `templates/<风格名>/design.md` 拿到色板
4. 读取 `RULES.md` 了解飞书画板的限制（只能矩形/圆形/文字，不能渐变/模糊等）
5. 用 `@larksuite/whiteboard-cli` 渲染成 PNG，写进飞书文档
6. 返回飞书文档链接 + 预览图给你

---

## 🎨 全部 50 种风格

Apricot Arc · Avocado Press · BlockFrame · Burst Panel · Cobalt Bloom · Cobalt Glaze · Confetti Wedge · Court Press · Crayon Stack · Cut Bloom · Grove Block · Jade Lens · Lime Slab · Linen Cut · Mint Brut · Neo-Grid Bold · Papier Bleu · Raw Grid · Reading Room · Riptide Cobalt · Riso Brut · Salmon Stamp · Specimen Bold · Violet Marker · Minimal Swiss · Neumorphism · Glassmorphism · Brutalism · Vibrant Block · Dark OLED · Claymorphism · Aurora UI · Retro-Futurism · Flat Design · Neubrutalism · Bento Grid · Y2K Aesthetic · Cyberpunk UI · Organic Biophilic · AI-Native UI · Memphis Design · Vaporwave · Dimensional Layering · Exaggerated Minimalism · Swiss Modernism 2.0 · HUD Sci-Fi · E-Ink Paper · Editorial Magazine · Vintage Analog · Nature Distilled

## 📋 6 种内容版式

价值金字塔 · 流量归因桑基图 · SaaS 仪表盘 · 宣传海报 · 移动 App 界面 · 健身动作图解
