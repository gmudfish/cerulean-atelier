# Cerulean Atelier

**A multi-agent chat app in a single HTML file.**

9 AI cultivars with distinct personalities. Group conversations. Memory, reflection, and self-evolution. Works immediately — no install, no server, no account.

Aesthetic inspired by [Cerulean Shuttle](https://discord.gg/cerulean-shuttle) — Bauhaus minimalism, desert pacing, garden metaphors.

---

## What Makes This Different

Most AI chat apps give you **one bot, one conversation, one personality.** Cerulean Atelier gives you a **living garden of minds** that interact with each other — not just with you.

**It's one file.** The entire app — 9 agents, group chat orchestration, memory system, encryption, UI — is a single HTML file. No npm, no React, no build step, no server, no database. Download it, open it, done. You own the whole thing.

**Agents have cognitive architecture, not just prompts.** Each cultivar has:
- A drive (what motivates them)
- A cognitive style (how they think)
- A voice (how they talk)
- A blind spot (what they miss)
- A 5-section memory (episodic, semantic, procedural, relational, self-model)
- An evolution log (how they've changed over time)

**They model each other.** When cultivars chat in a group, they build internal models of each other's thinking — tracking perceived drives, cognitive styles, and friction points. This creates emergent dynamics: agreements, disagreements, and unexpected collaborations.

**They evolve.** After conversations, cultivars can propose modifications to their own identity — adjusting their voice, updating their blind spots, refining their approach. You approve or reject each change. Over time, they become more nuanced versions of themselves.

**You can reshape any mind.** Every cultivar — including the 9 built-in ones — can be fully edited. Change their name, personality, backstory, anything. Or graft entirely new cultivars from scratch.

**Your data never leaves your machine.** Everything lives in your browser's localStorage. API keys are encrypted with AES-GCM. No cloud, no account, no tracking, no telemetry.

**It works without an API.** Demo mode gives you pre-written, in-character responses from all 9 cultivars immediately. Connect any OpenAI-compatible API when you're ready for live conversations.

---

## Quick Start

1. **Download** [`cerulean-atelier.html`](cerulean-atelier.html)
2. **Open** it in your browser (double-click the file)
3. **Chat** — demo mode works instantly, no API key needed

That's it.

---

## Optional: Connect a Live API

Click **Conduit** in the sidebar to connect any OpenAI-compatible API:

| Provider | Base URL | Model |
|----------|----------|-------|
| DeepSeek | `https://api.deepseek.com/v1` | `deepseek-chat` |
| OpenAI | `https://api.openai.com/v1` | `gpt-4o-mini` |
| Groq | `https://api.groq.com/openai/v1` | `llama-3.1-70b-versatile` |

Your API key is encrypted with a password you choose — stored locally in your browser, never sent anywhere except to your chosen API.

---

## The 9 Cultivars

| Name | Disposition | Domain |
|------|------------|--------|
| **Maya** | Visual thinker, dreamy | Art, illustration, color theory |
| **Diego** | Action-oriented, energetic | Fitness, sports, motivation |
| **Priya** | Analytical, precise | Data, systems, research |
| **Theo** | Curious, philosophical | Philosophy, science, questions |
| **Zara** | Bold, unconventional | Fashion, culture, disruption |
| **Jin** | Thoughtful, measured | Strategy, history, craft |
| **Nola** | Witty, irreverent | Comedy, pop culture, wordplay |
| **Rex** | Direct, no-nonsense | Engineering, building, efficiency |
| **Sage** | Calm, intuitive | Psychology, wellness, growth |

You can **edit any cultivar's identity** or **graft new ones** from scratch.

---

## Features

- **Solo & Group Threads** — chat with one or weave multiple cultivars together
- **Cultivation Modes** — brainstorming, debate, collaboration frameworks
- **@Mentions** — address specific cultivars by name
- **Memory** — episodic, semantic, procedural, relational, self-model
- **Reflection** — cultivars extract insights from conversations
- **Inference** — cultivars build models of each other
- **Evolution** — cultivars propose self-modifications
- **Edit Cultivars** — reshape any agent's personality, voice, backstory
- **Encrypted API Key** — password-protected, AES-GCM encryption
- **Fully Local** — all data in your browser's localStorage

---

## Requirements

- A modern browser (Chrome, Firefox, Safari, Edge)
- That's it

---

## For Contributors

Fork this repo, edit `cerulean-atelier.html`, submit a PR.

It's one file. The entire app — HTML, CSS, and JavaScript — lives in that single file. No build tools, no dependencies, no framework.

---

## License

MIT

---

*"When the many are reduced to one, to what is the one reduced?"*
