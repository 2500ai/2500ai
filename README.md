English | [简体中文](README.zh-CN.md)
deepseekmd v1.3.6 is the first release. It is still far from complete and is intended for experimental purposes only.
asimarkdown v1.3.6: Initial experimental release, highly incomplete. For further testing, use the DeepSeekMD folder.
★★★★★ JS can be executed within Markdown files. Please test with caution!
20260526
## 🔗 Related Links
- Live Demo: [deepseekmd.com](http://deepseekmd.com)
- More Examples: [asimarkdown.com](http://asimarkdown.com)
- Homepage & Project Hub: [2500.ai](http://2500.ai) and [2500ai.com](http://2500ai.com)
- Author's blog & other projects: same domain as above
---
# DeepSeekMD v1.3.6
> **Rollable & Runnable Markdown** — A creative experiment that fuses Markdown, HTML components, live preview and an AI assistant into one.
[![Version](https://img.shields.io/badge/version-1.3.6-blue)](https://deepseekmd.com)
[![License](https://img.shields.io/badge/license-MIT-green)](#license)
[![Online Demo](https://img.shields.io/badge/demo-live-brightgreen)](http://deepseekmd.com)
---
## ✨ In a Nutshell
**DeepSeekMD** is a **single-file HTML** Markdown editor. You can write articles just like normal Markdown, but at any moment you can insert **"single-character functions"** to generate forms, charts, multimedia, games, and even music – making your document truly *runnable*.
---
## 🚀 Features
- 📝 **3-in-1 Editor**: Code + Preview + AI chat, rendered in real-time split panes
- ⚡ **Single-Character Functions**: 200+ built-in Chinese-character functions (e.g. `入`, `密`, `柱`, `饼`, `音`, `玩`) to produce HTML components with zero code
- 🎵 **HanSound**: Write musical scores using Chinese numerals (一二三四五六七 etc.) and play them in the browser
- 🤖 **AI Extension**: Connect to the DeepSeek API; let the AI help you write documents and even extend new functions right from the chat
- 🎨 **Rich Visualizations**: Bar chart, pie chart, line chart, radar chart, heatmap, funnel chart… all built-in
- 📦 **Pure Frontend**: No build tools – a single HTML file, ready to run
- 🌗 **Dark Theme**: Toggle with `Ctrl+T`
- 🔌 **Local Storage**: Auto-save documents so you never lose your work
---
## 📖 Three Syntax Styles (all valid)
```markdown
1. Standard:  【入】`姓名,请输入,齐庄`
2. Shorthand: 入`姓名,请输入,齐庄`
3. Line-start: 入 姓名,请输入,齐庄
4. Single-character line: 雨           ← just a function name, parsed as line-start
```
The first parameter of every function is the **element ID**; subsequent parameters are separated by commas.
---
## 🧩 Hand-picked Built-in Functions
| Category | Example Functions |
|----------|-------------------|
| **Basic Markdown** | `广`(h1) `文`(h2) `突`(Bold) `斜`(Italic) `引`(Blockquote) |
| **Form Components** | `入`(Input) `密`(Password) `数`(Number) `盼`(Dropdown) `钮`(Button) |
| **Charts** | `柱`(Bar) `饼`(Pie) `线`(Line) `雷`(Radar) `环`(Doughnut) |
| **Media** | `音`(HanSound) `声`(MP3) `影`(Video) `录`(Camera) `签`(Signature) |
| **Utilities** | `钟`(Clock) `骰`(Dice) `算`(Calculator) `编`(Base64) |
| **Games / Interactive** | `玩`(Snake) `五`(Gomoku) `抽`(Wheel) `秒`(Stopwatch) `倒`(Countdown) |
| **Visual Animations** | `渐`(Gradient Text) `跳`(Bounce) `滚`(Marquee) `旋`(Rotate) `闪`(Blink) |
| **Web API** | `通`(Notification) `说`(Speech) `位`(Geolocation) `贴`(Clipboard) `幕`(Fullscreen) |
For the complete list, open the function panel on the left side of the editor or press `F9` to see **all examples**.
---
## 🎵 HanSound (Music Programming)
Control pitch with five numeral systems and write melodies directly in your document:
```
１１５５６６５　４４３３２２１
```
Five scales:
- Extra-high: 壹贰叁肆伍陆柒
- High: 一二三四五六七
- Middle: １２３４５６７
- Low: ①②③④⑤⑥⑦
- Extra-low: ㈠㈡㈢㈣㈤㈥㈦
Click the “Play” button and the browser will perform the melody via the Web Audio API.
---
## 🚦 Quick Start
### Online Use
Visit [http://deepseekmd.com](http://deepseekmd.com) – no installation needed.
### Run Locally
1. Download `deepseekmd.html` from this project (or save the page directly).
2. Open the file with your browser.
3. Start editing and running!
### Embed in Your Project
```html
<script src="https://asiide.com/js/asimarkdown.js"></script>
<script>
  const html = asimarkdown(markdownText);  // Convert single-character syntax to HTML
</script>
```
This lets you render DeepSeekMD content on your own pages.
---
## 🤖 AI Chat
Enter your **DeepSeek API Key** in the upper-right corner of the editor to enable the AI assistant:
- Ask questions directly – the AI will prioritise answering in DeepSeekMD syntax
- Tell the AI “Help me create a new function 【告】” and it will give you the complete JS code
- Click the hint button at the bottom left for quick prompts
---
## 🧰 Advanced Features
- **Extend Functions**: Menu → “Tools” → “Extend New Function”, write a single-character function and it takes effect instantly
- **Draggable Layout**: All panels can be resized by dragging; double-click a divider to collapse
- **Export**: Export as `.md` / `.html`, or print directly
- **Keyboard Shortcuts**: `Ctrl+S` save, `Ctrl+Enter` render, `F9` run all, `Ctrl+T` toggle theme
---
## 📜 License
When using the source code of this project, you **must retain the copyright notice** (including author, links, etc.) that appears in the source code header. Refer to the header comments in the source file for the exact terms.
> Made with ❤️ by Qizhuang · © 2026 DeepSeekMD (unofficial, based on Brain Language 1.3.6)
---
## 🙏 Acknowledgements
Thanks to the creator of Markdown, Yizhiban, cc, DeepSeek, Doubao, and all the partners who provided inspiration for this project.
---
**Roll it up, make your Markdown come alive!**
