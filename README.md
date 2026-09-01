# AI Tech Timeline · AI 技术热词时间线

> A timeline of **AI engineering buzzwords** — what emerged, when, and what it actually means. From ChatGPT (2022) to the Agentic Engineering era (2026).

<p align="center">
  <a href="https://awch-d.github.io/AI-Tech-Timeline/"><img src="https://img.shields.io/badge/GitHub%20Pages-live-5b6cff?style=flat-square" alt="pages"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/license-Apache--2.0-34c759?style=flat-square" alt="license"/></a>
  <img src="https://img.shields.io/badge/热词-31-ff9500?style=flat-square" alt="entries"/>
  <img src="https://img.shields.io/badge/手册-5-af52de?style=flat-square" alt="handbooks"/>
  <img src="https://img.shields.io/badge/format-single--html-1d1d1f?style=flat-square" alt="single html"/>
  <img src="https://img.shields.io/badge/lang-中文-ff3b30?style=flat-square" alt="zh-CN"/>
</p>

---

## 📖 简介

2022 年底 ChatGPT 发布后，AI 工程领域的热词以月为单位密集涌现：Prompt Engineering、RAG、Function Calling、Agentic Workflow、MCP、Vibe Coding、Context Engineering、Loop Engineering…… 每个热词都值得一份完整的学习手册，但在此之前，更缺一个**宏观的编年视角**——谁在什么时候冒出来、指什么、因何走红、彼此之间的演进关系如何。

本仓库就是这条时间线：**按时间轴排列的 AI 技术热词编年史**。每个条目记录热词的提出时间、一句话定义与走红背景；已有深度手册的热词可直接点击进入对应的完整学习页（单文件 HTML，结构与内容深度对齐独立手册标准）。

---

## ✨ 特性

- 🕐 **编年视角** — 以"时间"而非"主题"组织，看清热词的先后关系与范式演进
- 📇 **卡片式条目** — 每个热词：时间（精确到月）+ 中英文名称 + 一句话定义 + 类别 + 收录状态
- 🔗 **手册联动** — 已有完整手册的热词一键跳转详情页，与独立 handbook 仓库同等深度
- 🗂 **类别筛选** — 工程范式 / 智能体 / 模型能力 / 架构模式 / 协议标准 / 产品形态 / 基础设施
- 🔍 **全文搜索** — 按热词名、关键词即时过滤
- 🧭 **年份滚动联动** — 侧边栏年份导航随滚动高亮
- 📦 **单文件零依赖** — 全部页面为独立 HTML，无需构建，GitHub Pages 直接托管
- 🍎 **Apple Glass 风格** — 浅色主题 + 毛玻璃质感，图标全部内嵌 SVG，无外部 CDN
- 🇨🇳 **中文优先** — 术语保留英文原文，解释全部中文

---

## 🗓 收录概览（31 个热词）

| 年份 | 热词（按时间顺序） |
|---|---|
| 2022 | ChatGPT、提示词工程 |
| 2023 | 插件机制、自主智能体、函数调用、检索增强生成 📕、向量数据库、多模态大模型、GPTs / Assistants API |
| 2024 | 文生视频、长上下文、智能体工作流、智能体化 RAG、推理模型、电脑操作智能体、模型上下文协议（MCP） |
| 2025 | 开源推理模型（DeepSeek-R1）、氛围编程、深度研究、挽具工程、通用智能体、智能体互联协议（A2A）、智能体编程、上下文工程、子代理编排、规格驱动开发、智能体技能 |
| 2026 | 智能体环境工程 📕、可执行本体 📕、循环工程 📕、AI Native SDLC 📕 |

> 📕 = 已有完整手册详情页；其余条目已收录进时间线，专属详情页按同一标准陆续补齐。

---

## 📕 完整手册（5 份）

以下热词已有完整的中文学习页，内容深度对齐独立 handbook 标准：

| 热词 | 在线阅读 | 说明 |
|---|---|---|
| 检索增强生成 RAG | [rag.html](https://awch-d.github.io/AI-Tech-Timeline/rag.html) | 由独立仓库 RAG-Handbook 合并而来 |
| 循环工程 Loop Engineering | [loop-engineering.html](https://awch-d.github.io/AI-Tech-Timeline/loop-engineering.html) | 由 Loop-Engineering-Handbook 合并而来 |
| 可执行本体 Executable Ontology | [executable-ontology.html](https://awch-d.github.io/AI-Tech-Timeline/executable-ontology.html) | 由 Executable-Ontology-Handbook 合并而来 |
| 智能体环境工程 | [agentic-environment-engineering.html](https://awch-d.github.io/AI-Tech-Timeline/agentic-environment-engineering.html) | 由同名 handbook 仓库合并而来 |
| AI Native SDLC | [ai-native-sdlc.html](https://awch-d.github.io/AI-Tech-Timeline/ai-native-sdlc.html) | Claude Academy《The AI-Native SDLC Playbook》14 课完整中文转述，含 67 条术语对照表 |

---

## 📂 项目结构

```
AI-Tech-Timeline/
├── index.html                          # 时间线主页（数据内嵌于页面 DATA 数组）
├── ai-native-sdlc.html                 # AI Native SDLC 手册（Claude Academy 课程中文转述）
├── rag.html                            # 检索增强生成（RAG）手册
├── executable-ontology.html            # 可执行本体手册
├── loop-engineering.html               # 循环工程手册
├── agentic-environment-engineering.html # 智能体环境工程手册
├── LICENSE                             # Apache-2.0
└── README.md
```

---

## ✅ 收录标准

一个热词被收录进时间线，需要满足：

1. **有明确的提出时间点** — 能定位到具体论文、官方博客、发布会或社区事件（精确到月）
2. **产生了真实的工程影响** — 改变了一线开发者的工作方式或技术选型，而非纯营销话术
3. **定义可一句话说清** — 条目描述需区分可验证事实与营销用语

条目时间均标注到月。**按一手来源（论文 / 官方博客 / 发布日）逐条核实是持续进行的工作，目前尚未全部完成**——部分条目的时间取自公开报道或社区共识的初稿判断，存在多个候选时间节点的词条会在核实后于详情页说明考据过程。欢迎通过 issue 指出时间偏差并附一手来源。

---

## 🛠 如何新增条目

时间线数据内嵌在 `index.html` 底部的 `DATA` 数组中，每个条目一个对象：

```js
{y:2026, m:"2026-06", term:"循环工程", en:"Loop Engineering",
 cat:"工程范式", status:"handbook", link:"loop-engineering.html",
 desc:"一句话定义与走红背景。"}
```

- `status: "handbook"` — 已有完整手册，`link` 指向同目录下的详情页 HTML（文件名使用热词的英文 slug）
- `status: "pending"` — 已收录但详情页待补齐，主页点击时显示提示

新增手册页时的几条约定：

- 复制任一并存手册的 HTML 骨架，替换内容，文件名与 `link` 对应，无需任何构建步骤
- 页面顶部保留「← 返回技术热词时间线」链接指向 `index.html`
- **零外部资源**：图标一律内嵌 SVG，不引用任何 CDN 上的 CSS、JS、字体或图片
- **示例代码块的汉化取舍**：自然语言类内容（需求文档、实施计划、提示词、评审指令、给 AI 读的项目约定）译为中文；机器读取类内容（配置文件、CI 定义、shell 脚本、skill 与子代理的 YAML frontmatter）保持英文原样。汉化块内的命令、文件路径、目录名、技术名，以及需要被字面匹配的输出串，同样保留英文

---

## 🚀 在线预览

**👉 [awch-d.github.io/AI-Tech-Timeline](https://awch-d.github.io/AI-Tech-Timeline/)**

本地预览：直接用浏览器打开 `index.html` 即可。

---

## 📄 License

[Apache-2.0](LICENSE)
