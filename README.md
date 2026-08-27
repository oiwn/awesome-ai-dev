# awesome-ai-dev

Using LLMs and Harness to build software.

A curated list of coding agents, runtimes, tooling, and reading for AI-assisted development.

## Coding Agents

- [Codex CLI](https://github.com/openai/codex) - OpenAI's lightweight open source coding agent that runs in your terminal.
- [opencode](https://opencode.ai) - Open source AI coding agent for terminal, IDE, and desktop. 75+ providers via Models.dev, LSP support, multi-session, shareable session links.
- [Command Code](https://commandcode.ai) - Terminal coding agent that continuously learns your coding taste — every accept, reject, and edit becomes a signal distilled into reusable skills and memory.
- [omp](https://omp.sh/) - A coding agent for the terminal with the IDE wired in: LSP, DAP, subagents, plan mode, hindsight memory, and hashline edits, powered by a native Rust engine.
- [Pi](https://pi.dev) - Minimal, aggressively extensible agent harness. Primitives, not features: subagents, plan mode, and even MCP are extensions you build or install. See the companion blog post in [Interesting Reading](#interesting-reading).
- [DeepSeek Harness](https://deepseek.com/harness/en/) - Agent harness where every capability is a plugin (models, tools, skills, sandboxes, UI) on the Cordis kernel, and every run is recorded in a traceable, replayable session log.

## Agent Runtimes & Orchestration

- [Herdr](https://herdr.dev) - The runtime coding agents live on. Holds terminals open so agents survive lid-close and reboots, marks each agent working/blocked/idle, and lets you reattach from anywhere.
- [Octomind](https://octomind.run) - Open source portable agent runtime. An agent is a TOML file you own: any model swapped mid-session, deterministic guardrails instead of approval popups, and it keeps working unattended.

## Editors & Review

- [Delta](https://delta.dev) - Multiplayer environment for coding with agents, by the creators of Zed. Review alongside the agent in shared threads where every change keeps the conversation that produced it.

## Model Access

- [OpenRouter](https://openrouter.ai) - Unified OpenAI-compatible API for 500+ models across 80+ providers, with price/performance routing, fallbacks for uptime, and fine-grained data policies.

## Agent Tooling

- [agent-browser](https://agent-browser.dev) - Browser automation CLI designed for AI agents (Vercel). Ref-based accessibility snapshots use a fraction of the tokens of a full DOM, with a native Rust daemon and 50+ commands.
- [Symposium](https://github.com/symposium-dev/symposium) - `cargo agents`: scans a Rust workspace's dependency graph and installs crate-specific skills, hooks, and MCP servers into the coding agents you use.
- [agtrace](https://github.com/lanegrid/agtrace) - Observability for coding agents: live context-window usage, token consumption trends, tool-call activity, and searchable session history your agent can query via MCP.

## Learning & Reference

- [The AI Coding Dictionary](https://www.aicodingdictionary.com/) - The vocabulary of AI coding in plain English: tokens, harnesses, context windows, handoffs, failure modes, and patterns of work.

## Interesting Reading

- [Building a minimal AI agent from scratch](https://minimal-agent.com) - The SWE-agent team's tutorial on building a working agent in ~60 lines of Python — scores up to 74% on SWE-bench Verified.
- [What I learned building an opinionated and minimal coding agent](https://mariozechner.at/posts/2025-11-30-pi-coding-agent/) - Mario Zechner on designing Pi: context engineering, minimal system prompts and toolsets, and the case against MCP, sub-agents, and plan mode.
