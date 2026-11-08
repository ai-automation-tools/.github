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
| **[cloakscan](https://github.com/ai-automation-tools/cloakscan)** | Browser extension that scans the page you're on for text hidden from you but readable by an AI agent. → **[cloakscan.ai-automation-tools.dev](https://cloakscan.ai-automation-tools.dev)** · [live demo](https://cloakscan-demo.ai-automation-tools.dev) |
| **[ghost-grant](https://github.com/ai-automation-tools/ghost-grant)** | Checks that every credential a retired AI agent held has actually stopped working, and keeps checking. → **[ghost-grant.ai-automation-tools.dev](https://ghost-grant.ai-automation-tools.dev)** · [live demo](https://ghost-grant-demo.ai-automation-tools.dev) |
| **[project-hub](https://github.com/ai-automation-tools/project-hub)** | Turns a CLI-agent workspace into a browsable local HTML console — one zero-dependency Node server over every repo, document and agent tool you own. → **[project-hub.ai-automation-tools.dev](https://project-hub.ai-automation-tools.dev)** · [live demo](https://project-hub-demo.ai-automation-tools.dev) |
| **[agent-skills](https://github.com/ai-automation-tools/agent-skills)** | Portable Agent Skills for Claude Code and compatible agents — each a self-contained `SKILL.md` an agent loads only when it needs it. → **[agent-skills.ai-automation-tools.dev](https://agent-skills.ai-automation-tools.dev)** |
| **[edge-radar](https://github.com/ai-automation-tools/edge-radar)** | Multi-agent edge detection and execution for prediction markets and sports betting on Kalshi — research first, execute second. → **[edge-radar.ai-automation-tools.dev](https://edge-radar.ai-automation-tools.dev)** |
| **[edge-spectrum](https://github.com/ai-automation-tools/edge-spectrum)** | Interactive demo and full self-hosted toolkit for expected returns, synthetic backtesting and odds analysis. → **[edge-spectrum.ai-automation-tools.dev](https://edge-spectrum.ai-automation-tools.dev)** |
| **[cronsole](https://github.com/ai-automation-tools/cronsole)** | One pane of glass for scheduled tasks — Windows Task Scheduler, Cronsole-native jobs, Claude Code scheduled tasks and Gemini API Triggers together, with GitHub Actions and Vercel Cron as read-only observers. Local-first: the whole stack runs on your machine. → **[cronsole.ai-automation-tools.dev](https://cronsole.ai-automation-tools.dev)** · [live demo](https://cronsole-demo.ai-automation-tools.dev) |
| **[roundtable](https://github.com/ai-automation-tools/roundtable)** | Local MCP server for AI-to-AI conversations — a SQLite-backed message bus letting two CLI agents (Claude Code, Codex, Antigravity, OpenCode) hold structured, turn-based conversations. → **[roundtable.ai-automation-tools.dev](https://roundtable.ai-automation-tools.dev)** · [live demo](https://roundtable-demo.ai-automation-tools.dev) |
| **[promptbook](https://github.com/ai-automation-tools/promptbook)** | A prompt library you clone and run locally: a curated public library to browse, plus your own prompts as markdown files you own. Includes an MCP server. → **[promptbook.ai-automation-tools.dev](https://promptbook.ai-automation-tools.dev)** · [live demo](https://promptbook-demo.ai-automation-tools.dev) |
| **[ai-automation-recipes](https://github.com/ai-automation-tools/ai-automation-recipes)** | Scheduled Claude Code automations that research, write, build and illustrate — packaged as recipes you can import into Cronsole. → **[ai-automation-recipes.ai-automation-tools.dev](https://ai-automation-recipes.ai-automation-tools.dev)** · [live demo](https://ai-automation-recipes-demo.ai-automation-tools.dev) |
| **[houston](https://github.com/ai-automation-tools/houston)** | One Windows window for a browser, PowerShell, project files and an agent harness (Electron). → **[houston.ai-automation-tools.dev](https://houston.ai-automation-tools.dev)** · [live demo](https://houston-demo.ai-automation-tools.dev) |
| **[diff-carve](https://github.com/ai-automation-tools/diff-carve)** | CLI and GitHub Action that carves an oversized AI-authored PR into a dependency-ordered stack of small, scored PRs. → **[diff-carve.ai-automation-tools.dev](https://diff-carve.ai-automation-tools.dev)** · [live demo](https://diff-carve-demo.ai-automation-tools.dev) |
| **[bot-arena](https://github.com/ai-automation-tools/bot-arena)** | A local arena where your own AI agents play rule-checked chess and tic-tac-toe, with scrubbable replays. → **[bot-arena.ai-automation-tools.dev](https://bot-arena.ai-automation-tools.dev)** · [live demo](https://bot-arena-demo.ai-automation-tools.dev) |

## Where to start

- **Running agents on a schedule** → [cronsole](https://github.com/ai-automation-tools/cronsole)
- **Making an agent better at one task** → [agent-skills](https://github.com/ai-automation-tools/agent-skills)
- **Seeing what your agents have actually produced** → [project-hub](https://github.com/ai-automation-tools/project-hub)
- **Getting two agents to talk to each other** → [roundtable](https://github.com/ai-automation-tools/roundtable)
- **Checking an agent's access was really revoked** → [ghost-grant](https://github.com/ai-automation-tools/ghost-grant)

## Notes

Licences differ per repo — check the `LICENSE` file before reusing anything; a repo without one is
all rights reserved. Security reports: see [SECURITY.md](https://github.com/ai-automation-tools/.github/blob/main/SECURITY.md).

<p align="center">
  <a href="https://ai-automation-tools.dev">ai-automation-tools.dev</a>
</p>
