<h1 align="center">habermas.skill</h1>

<p align="center">哈贝马斯 · Jürgen Habermas</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“较好论证的无强制之强制。”<br>— 哈贝马斯 · <a href="https://teddykw2.wordpress.com/wp-content/uploads/2012/07/jc3bcrgen-habermas-justification-and-application-remarks-on-discourse-ethics.pdf">《辩护与应用》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将公共论证、有效性区分与交往条件整理为思想分析 Skill，让 AI 检查共识如何形成、理由能否公开辩护，以及谁没有真正获得发言机会。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 全员举手通过，是否说明方案合理？

> 先检查缺席者与不敢反对的人，再区分程序认可、理由质量和事实准确性。多数支持可以是一项事实，却不能独自证明方案的规范正当性。

### 2. 技术上效率最高，为什么还需要讨论？

> 效率回答的是给定目标下怎样做。目标由谁决定、代价怎样分担、受影响者能否质疑，属于尚未被技术答案解决的问题；也不必把纯技术细节全部改造成价值辩论。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 理由公开性 | 查明受影响者、异议渠道与强制条件。 |
| 主张分类 | 区分事实真理、规范正当性与行动动机。 |
| 控制与交往 | 检查技术优化是否遗漏了人与人之间的协调问题。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/habermas-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `habermas-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/habermas-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用哈贝马斯的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《包容他者》规范论证选段；《认识与兴趣》选篇；真诚性与交往条件的补读材料。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://teddykw2.wordpress.com/wp-content/uploads/2012/07/jc3bcrgen-habermas-justification-and-application-remarks-on-discourse-ethics.pdf">《辩护与应用》</a>，〈道德、社会与伦理〉，第 163 页（短语节选）。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
