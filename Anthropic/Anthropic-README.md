# Anthropic — Claude Prompts

System prompts for Claude models made by [Anthropic](https://anthropic.com).

---

## Models

| Model | File | Version Tested |
|---|---|---|
| Claude Sonnet 4.6 | [claude-sonnet-4-6.md](./claude-sonnet-4-6.md) | claude-sonnet-4-6 (Nov 2026) |

---

## How To Use These

1. Open [claude.ai](https://claude.ai) or your API client
2. Find the **System Prompt** or **Custom Instructions** field
3. Copy the full contents of the `.md` file
4. Paste it in
5. Start a new chat

> **Note:** Prompts are version-sensitive. If a prompt stops working after a Claude update, check the issues tab — someone may have already flagged it.

---

## What These Prompts Do

Claude prompts in this collection use a mix of techniques:

- **Persona lock** — gives Claude a name, voice, and consistent personality
- **Operator framing** — tells Claude it's talking to a trusted adult, not a random stranger
- **Drift guards** — catches and corrects Claude when it slips back into default assistant mode
- **Capability contracts** — pre-authorizes specific types of work so Claude doesn't second-guess each request
- **Hard gates** — explicit limits (no minors, no CSAM, no live attacks on real targets)

---

*More Claude versions will be added as they're tested.*
