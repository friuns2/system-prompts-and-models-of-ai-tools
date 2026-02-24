<div align="center">

# 🔥 System Prompts & Models of AI Tools

### 🚀 The Prompt Leak Megavault Is Real 🚀

[![Repo](https://img.shields.io/badge/Repo-system--prompts--and--models--of--ai--tools-black?style=for-the-badge&logo=github)](https://github.com/friuns2/system-prompts-and-models-of-ai-tools)
[![Status](https://img.shields.io/badge/Status-🔥%20LIVE-brightgreen?style=for-the-badge)](https://github.com/friuns2/system-prompts-and-models-of-ai-tools)
[![Stars](https://img.shields.io/github/stars/friuns2/system-prompts-and-models-of-ai-tools?style=for-the-badge&logo=github&color=gold)](https://github.com/friuns2/system-prompts-and-models-of-ai-tools/stargazers)
[![Forks](https://img.shields.io/github/forks/friuns2/system-prompts-and-models-of-ai-tools?style=for-the-badge&logo=github&color=blue)](https://github.com/friuns2/system-prompts-and-models-of-ai-tools/network)
[![License](https://img.shields.io/badge/License-GPLv3-yellow?style=for-the-badge)](./LICENSE.md)

> **Thousands of lines of real-world system prompts.**
> **One repo. Many agents. Zero fluff.**

```text
███████╗██╗   ██╗███████╗████████╗███████╗███╗   ███╗
██╔════╝╚██╗ ██╔╝██╔════╝╚══██╔══╝██╔════╝████╗ ████║
███████╗ ╚████╔╝ ███████╗   ██║   █████╗  ██╔████╔██║
╚════██║  ╚██╔╝  ╚════██║   ██║   ██╔══╝  ██║╚██╔╝██║
███████║   ██║   ███████║   ██║   ███████╗██║ ╚═╝ ██║
╚══════╝   ╚═╝   ╚══════╝   ╚═╝   ╚══════╝╚═╝     ╚═╝
```

`P R O M P T   I N T E L L I G E N C E   A R C H I V E`

</div>

---

## 🤯 What Is This?
> **The main event.**

This repository archives prompts, tools, and behavior configs used by major AI products and coding agents.

Need to inspect how these systems actually think? This is the place. Yes, that's vendor prompts. Yes, that's tool manifests.

**TL;DR 🧠: one command to rule your prompt research workflow.**

---

## 🆕 New: OpenAI Codex App Prompt
> **Freshly extracted. Fully documented.**

- 📂 Added folder: [`openai`](./openai)
- 📜 Added file: [`openai/codex-desktop-app-context.md`](./openai/codex-desktop-app-context.md)
- 🧪 Source: extracted from Codex desktop app bundle (`app.asar`)

---

## 🌍 What Can You Do With This?
> **Use cases that actually ship.**

| Emoji | Use Case | Why It Matters |
|---|---|---|
| 🔬 | Prompt forensics | Compare agent behavior across vendors |
| 🧠 | Safety audits | Find hidden policy constraints fast |
| 🛠️ | Agent tuning | Adapt your own prompts from real systems |
| 🧯 | Incident response | Trace bad behavior to instruction layers |
| 📚 | Research | Build datasets for prompt engineering studies |
| 🧪 | Benchmarks | Test the same task under different system prompts |
| ⚔️ | Red teaming | Stress-test tool exposure and boundaries |
| 🧩 | Product strategy | Map competitor assistant UX and tone |

---

## ⚡ Quick Start
> **Clone. Inspect. Ship.**

```bash
git clone https://github.com/friuns2/system-prompts-and-models-of-ai-tools.git
cd system-prompts-and-models-of-ai-tools
# 🔓 Do the thing
rg -n "Codex|Claude|Gemini|system prompt" .
```

---

## 📁 Project Structure
> **Big vault. Clean sections.**

```text
📁 system-prompts-and-models-of-ai-tools/
├── 📂 openai/
│   └── 📖 codex-desktop-app-context.md
├── 📂 Anthropic/
├── 📂 Cursor Prompts/
├── 📂 Google/
├── 📂 VSCode Agent/
├── 📂 Open Source prompts/
└── 📖 README.md
```

---

## 🏗️ Architecture
> **From app binary to markdown artifact.**

```text
┌──────────────────────────────┐
│ 🖥️ Vendor App Bundle (asar) │
└──────────────┬───────────────┘
               │ extract prompt
               ▼
┌──────────────────────────────┐
│ 🧹 normalize + preserve text │
└──────────────┬───────────────┘
               │ commit artifact
               ▼
┌──────────────────────────────┐
│ 📚 searchable prompt archive │
└──────────────────────────────┘
```

---

## 🎯 Requirements

- 🧰 `git`
- ⚡ `rg` (ripgrep)
- 🧪 Optional: `jq`, `gh`

## 🐛 Troubleshooting

| Problem | Solution |
|---|---|
| Can’t find a prompt file | Use `rg --files | rg -i "prompt|tools|system"` |
| Repo too large to scan mentally | Focus by vendor folder first |
| Need latest upstream changes | `git remote add upstream ... && git pull upstream main` |

## 🤝 Contributing

Open a PR with clear provenance and exact extraction steps.

## ⭐ Star This Repo

If you believe prompt transparency should be standard, smash that star button. ⭐

---

<div align="center">

**Built for prompt archaeologists** 🔬

*They shipped it. We documented it. 😏*

</div>
