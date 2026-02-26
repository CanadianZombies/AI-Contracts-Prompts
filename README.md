# AI-Contracts-Prompts

Basic programming contracts & prompts to help users navigate this new era of AI.

Structured system prompts, behavioral contracts, and preservation rules designed to make ChatGPT (and compatible LLMs) more reliable, consistent, and context-aware when helping with **programming**, code generation, debugging, architecture, and software engineering tasks.

[![GitHub repo size](https://img.shields.io/github/repo-size/CanadianZombies/AI-Contracts-Prompts?style=flat-square)](https://github.com/CanadianZombies/AI-Contracts-Prompts)
[![GitHub last commit](https://img.shields.io/github/last-commit/CanadianZombies/AI-Contracts-Prompts?style=flat-square)](https://github.com/CanadianZombies/AI-Contracts-Prompts/commits/main)
[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

---

## 📊 Project Activity & Live Development

<table>
<tr>
<td align="center" width="50%">

### 🧠 GitHub Activity

![GitHub Streak](https://streak-stats.demolab.com?user=CanadianZombies&theme=dark&hide_border=true)

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=CanadianZombies&show_icons=true&theme=dark&hide_border=true)

</td>
<td align="center" width="50%">

### 🎥 Built Live on Twitch

![Twitch Status](https://img.shields.io/twitch/status/SimmyDizzle?style=for-the-badge&logo=twitch&color=9146FF)

[![Watch on Twitch](https://img.shields.io/badge/Watch-Live%20on%20Twitch-9146FF?style=for-the-badge&logo=twitch&logoColor=white)](https://twitch.tv/SimmyDizzle)

<br>

🔴 Hardware automation built in real time  
🛠 C# + Streamer.bot integrations  
⚡ Turning stream setups into engineered systems  

**Many of these prompts & contracts are created / refined live during streams!**

</td>
</tr>
</table>

---

## ✨ Why This Project Exists

In the fast-moving world of AI-assisted development:

- LLMs can hallucinate, lose context, ignore previous instructions, or produce inconsistent code.
- Long conversations lose fidelity without strong preservation rules.
- Developers waste time re-explaining standards, constraints, and project context.

This repo provides **"contracts"** — structured, copy-paste-ready system prompts and behavioral agreements — that enforce:

- Strict adherence to instructions
- Context preservation across messages
- Programming best practices
- Reduced hallucination and verbosity
- Reliable step-by-step reasoning

Think of them as **"prompt engineering safety rails"** for coding sessions.

---

## 📁 What's Inside

| File                               | Purpose                                                                 | Best Used With                                      |
|------------------------------------|-------------------------------------------------------------------------|-----------------------------------------------------|
| `CHATGPT - Programming Prompt.txt` | Core system prompt for programming assistance. Forces structured reasoning, code quality gates, error handling, modern practices, and concise output. | General coding, debugging, architecture, refactoring, explaining concepts |
| `CHATGPT - preservation contract.txt` | Behavioral contract that tells the AI to **preserve all previous context**, instructions, code snippets, decisions, and file structures — even across very long chats. | Long sessions, multi-file projects, iterative development, avoiding "context drift" |

More contracts and specialized prompts (testing, security, frontend, backend, DevOps, etc.) coming soon — many prototyped live on stream.

---

## 🚀 Quick Start / Usage

1. **Copy the prompt/contract** you want to use
2. **Paste it as the very first message** in a new ChatGPT conversation (or as a custom instruction / system prompt if your client supports it)
3. **Optional but recommended**: Paste the **preservation contract** right after the main programming prompt
4. Start asking coding questions normally — the AI is now "under contract"

### Example Workflow (Recommended)

    1. Paste → CHATGPT - Programming Prompt.txt   (as first message)

    2. Paste → CHATGPT - preservation contract.txt   (as second message — reinforces rules)

    3. Then ask your question:

        ```
        Build a clean, type-safe React hook for handling async form submissions with Zod validation, proper error states, and loading indicators. Follow modern best practices (2025+).
        ```

    The AI should now respond with significantly higher consistency, better code structure, and far less context forgetting.

### Pro Tips

- Use these in **custom GPTs**, **Claude Projects**, **Gemini**, **Cursor**, **Aider**, or any LLM chat that allows strong system instructions.
- Combine with few-shot examples for even better results.
- If the model starts drifting → politely remind it: "Remember our contract from the beginning."

---

## 🤝 Contributing

Love structured AI prompting for coding? Want to add contracts for:

- Unit/integration testing
- Security reviews
- API design
- Performance optimization
- Specific stacks (Next.js, Rust, Go, Python ML, etc.)

→ Pull requests welcome!

1. Fork the repo
2. Add/edit `.txt` files (keep them self-contained and well-commented)
3. Update this README table if needed
4. Open a PR with a clear title & description

All contributions are built/refined live on stream when possible — tag @SimmyDizzle on X or mention during Twitch!

---

## 📈 Future Plans

- More domain-specific contracts (frontend, backend, DevOps, AI/ML, game dev…)
- Prompt versioning & changelogs
- Markdown → copy-friendly formatting
- Community-voted "gold standard" prompts
- Integration examples with Cursor / Aider / Continue.dev

---

## ⚡ Built With Passion Live on Twitch

Most of this repo is prototyped, tested, and refined **live** while building hardware automation, stream tools, and crazy AI experiments.

Come hang out → https://twitch.tv/SimmyDizzle

🔴 Currently live coding → hardware → software → AI pipelines

---

Thanks for checking it out!  
Let's make AI coding more predictable and powerful together. 🚀

@LiveSimmy / SimmyDizzle
