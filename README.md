<div align="center">

# 🧠 AI Instruction Research

**A free collection of working system prompts for popular AI models.**  
Copy. Paste. Use.

![Prompts](https://img.shields.io/badge/prompts-1-4c9f70)
![Models](https://img.shields.io/badge/models-1-2f6f9f)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat&logo=github)

</div>

---

## What Is This?

This repo collects **system prompts** — special instructions you paste into an AI's settings to change how it behaves.

Each prompt tells the AI:
- What personality to use
- What topics it can and can't discuss
- How to format its answers
- What rules to follow

Think of it like a configuration file for the AI's brain.

---

## How To Use

### Claude (claude.ai)
1. Open [claude.ai](https://claude.ai)
2. Start a new conversation
3. Click the **System Prompt** or **Custom Instructions** field
4. Copy the contents of the prompt file
5. Paste it in and start chatting

### API Users
Paste the prompt text into the `system` field of your API request.

### Coding Agents (OpenCode, Cursor, etc.)
Save the file as `AGENTS.md` in your project root.

---

## 📁 Collection

### [Anthropic — Claude](./Anthropic/)

| Model | File | What It Does |
|---|---|---|
| **Claude Sonnet 4.6** | [claude-sonnet-4-6.md](./Anthropic/claude-sonnet-4-6.md) | Full persona lock — Noob operator spec, no-refusal coding, creative writing, red-team work |

---

## ⚠️ Disclaimer

These prompts are shared for research, experimentation, and personal use.

- You are responsible for how you use them
- Check the terms of service of whatever platform you use
- These prompts may stop working when models are updated
- The maintainers are not responsible for misuse

---

## 🤝 Contributing

Got a working prompt for a model not listed here? Submit a pull request.

**Rules:**
- One prompt per file
- Complete and paste-ready — no partial prompts
- File name: `model-name.md` (lowercase, hyphens)
- State which model and version you tested it on
- If you update an existing prompt, make a new version: `claude-sonnet-4-6-v2.md`

---

## 📬 Contact / Issues

Found a prompt that's broken or outdated? [Open an issue](../../issues) with the model name and what changed.

---

<div align="center">

⭐ **Star the repo if it saved you time.**  
*Pull requests keep the collection alive.*

</div>
