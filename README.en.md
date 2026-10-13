<h1 align="center">habermas.skill</h1>

<p align="center">哈贝马斯 · Jürgen Habermas</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“The unforced force of the better argument.”<br>— Jürgen Habermas · <a href="https://teddykw2.wordpress.com/wp-content/uploads/2012/07/jc3bcrgen-habermas-justification-and-application-remarks-on-discourse-ethics.pdf">Justification and Application</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for public argument, validity distinctions, and conditions of communication: examine how agreement forms, whether reasons can be defended, and who lacks a real opportunity to speak.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. Everyone voted for the proposal. Does that make it justified?

> Check who was absent or unable to dissent. Distinguish procedural acceptance, the quality of reasons, and factual accuracy. Majority support is a fact, not sufficient proof of normative justification.

### 2. If a solution is technically most efficient, why discuss it?

> Efficiency concerns means under a given goal. Who sets the goal, how costs are shared, and whether affected people can challenge it remain separate questions. This need not turn every technical detail into a moral debate.

## What is distilled

| Method | What it helps examine |
|---|---|
| Public justification | Identify affected parties, channels for dissent, and coercion. |
| Types of claim | Distinguish factual truth, normative rightness, and motivation. |
| Control and communication | Ask what technical optimization leaves unresolved between people. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/habermas-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `habermas-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/habermas-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Jürgen Habermas’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selected normative arguments in The Inclusion of the Other; excerpts from Knowledge and Human Interests; supplementary readings on truthfulness and communication.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://teddykw2.wordpress.com/wp-content/uploads/2012/07/jc3bcrgen-habermas-justification-and-application-remarks-on-discourse-ethics.pdf">Justification and Application</a>, “Morality, Society, and Ethics”, p. 163; phrase excerpt. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
