<h1 align="center">AI Automation Tools</h1>

<p align="center">
  <em>Open tools for building, running, and scheduling AI agents.</em>
</p>

<p align="center">
  <a href="https://ai-automation-tools.dev"><img src="https://img.shields.io/badge/ai--automation--tools.dev-0078D4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="ai-automation-tools.dev"></a>
  <img src="https://img.shields.io/badge/focus-agents_·_scheduling_·_MCP-5FD6A1?style=for-the-badge" alt="Focus: agents, scheduling, MCP">
</p>

---

Small, self-hosted tools that came out of running a lot of CLI agents day to day. Each one solves a
problem that showed up in practice rather than one that looked interesting on paper, and each runs
on your own machine — there is no hosted service to sign up for and nothing phones home.

## Tools

| | What it does |
|:---|:---|
| **[cronsole](https://github.com/ai-automation-tools/cronsole)** | One pane of glass for scheduled tasks — Windows Task Scheduler, Cronsole-native jobs, Claude Code routines and Gemini API Triggers together, with GitHub Actions and Vercel Cron as read-only observers. Local-first: the whole stack runs on your machine. → **[cronsole.ai-automation-tools.dev](https://cronsole.ai-automation-tools.dev)** · [live demo](https://cronsole-demo.ai-automation-tools.dev) |
| **[agent-skills](https://github.com/ai-automation-tools/agent-skills)** | Portable Agent Skills for Claude Code and compatible agents — each a self-contained `SKILL.md` an agent loads only when it needs it. → **[agent-skills.ai-automation-tools.dev](https://agent-skills.ai-automation-tools.dev)** |
| **[project-hub](https://github.com/ai-automation-tools/project-hub)** | Turns a CLI-agent workspace into a browsable local HTML console — one zero-dependency Node server over every repo, document and agent tool you own. → **[project-hub.ai-automation-tools.dev](https://project-hub.ai-automation-tools.dev)** |
| **[Agent-chat](https://github.com/ai-automation-tools/Agent-chat)** | Local MCP server for AI-to-AI conversations — a SQLite-backed message bus letting two CLI agents hold a structured, turn-based conversation. → **[agent-chat.ai-automation-tools.dev](https://agent-chat.ai-automation-tools.dev)** |
| **[edge-spectrum](https://github.com/ai-automation-tools/edge-spectrum)** | Expected returns, synthetic backtesting and odds analysis — an interactive demo plus the full self-hosted toolkit. → **[edge-spectrum.ai-automation-tools.dev](https://edge-spectrum.ai-automation-tools.dev)** |
| **[Edge-Radar](https://github.com/ai-automation-tools/Edge-Radar)** | Multi-agent edge detection for prediction markets — research first, execute second. → **[ops page](https://edge-radar.mikesailab.com/)** |

## Where to start

- **Running agents on a schedule** → [cronsole](https://github.com/ai-automation-tools/cronsole)
- **Making an agent better at one task** → [agent-skills](https://github.com/ai-automation-tools/agent-skills)
- **Seeing what your agents have actually produced** → [project-hub](https://github.com/ai-automation-tools/project-hub)
- **Getting two agents to talk to each other** → [Agent-chat](https://github.com/ai-automation-tools/Agent-chat)

## Notes

Licences differ per repo — check the `LICENSE` file before reusing anything; a repo without one is
all rights reserved. Security reports: see [SECURITY.md](https://github.com/ai-automation-tools/.github/blob/main/SECURITY.md).

<p align="center">
  <a href="https://ai-automation-tools.dev">ai-automation-tools.dev</a>
</p>
