# Nefas11

Agentic software development, with the guardrails built in.

I build systems where AI agents do real work and are held to it: task
contracts, independent verification of what an agent claims, misalignment
detection while it runs, and a reputation that follows the agent. Most of it
is Python with zero dependencies, so it drops into an existing setup.

## On ClawHub

Six skills for [OpenClaw](https://github.com/openclaw), 6k+ downloads:
[clawhub.ai/nefas11](https://clawhub.ai/nefas11)

| Skill | What it does |
|---|---|
| [Governed Agents](https://clawhub.ai/nefas11/governed-agents) | Deterministic verification and reputation scoring for AI sub-agents. A hallucinated "done" costs the agent its score. |
| [Supervised Agentic Loop](https://clawhub.ai/nefas11/supervised-agentic-loop) | Brainstorm → Plan → Implement → Review → Verify → Evolve, with every tool call monitored. |
| [Swipenode](https://clawhub.ai/nefas11/swipenode-2) | Web extraction for agents without a headless browser: pulls the JSON out of Next.js and Nuxt pages at a fraction of the tokens. |
| [Brainstorming](https://clawhub.ai/nefas11/brainstorming-2) | Socratic design refinement before any code is written. Adapted from [obra/superpowers](https://github.com/obra/superpowers). |
| [Writing Plans](https://clawhub.ai/nefas11/writing-plans-2) | Breaks a design into 2–5 minute tasks, each with its own verification step. Adapted from [obra/superpowers](https://github.com/obra/superpowers). |
| [Maus HTML Summary](https://clawhub.ai/nefas11/maus-html-summary) | Turns articles and transcripts into a self-contained, illustrated explainer. |

## Repositories

- [governed-agents](https://github.com/Nefas11/governed-agents): the verification and reputation pipeline behind the skill above
- [agent-monitor](https://github.com/Nefas11/agent-monitor): two-phase misalignment detection for coding agents, sync blocking plus async LLM review
- [supervised-agentic-loop](https://github.com/Nefas11/supervised-agentic-loop): the self-improving loop, runs on OpenClaw, Antigravity and Claude Code
- [openclaw-superpowers-workflow](https://github.com/Nefas11/openclaw-superpowers-workflow): subagent orchestration with quality gates
- [public-skills](https://github.com/Nefas11/public-skills): skills for Claude Code and Codex, starting with `first-principles-reduction`: question, delete, simplify, accelerate, automate, in that order
- [swipenode](https://github.com/Nefas11/swipenode): the extraction engine behind the ClawHub skill

Based in Bavaria.
