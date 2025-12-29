# Chronist

**Feed your knowledge, create in parallel.**

Chronist is a desktop application that orchestrates AI agents locally from your ideas, notes, and research. Each agent runs sandboxed in its own worktree, enabling safe parallel execution without touching your main branch.

## Overview

Chronist solves the challenge of running autonomous AI coding assistants safely on local codebases. It provides isolation, real-time visibility, and approval controls for AI-driven development tasks - ensuring you maintain complete control over what changes get applied.

Powered by your existing Claude Code subscription. No separate subscription required during beta.

## Key Features

### Knowledge-Driven Agents

Your personal ideas, notes, and research live as local files you own. This knowledge becomes the foundation that shapes how agents think, research, and create - establishing a compounding loop between what you know and what AI generates.

### Safe Sandboxed Execution

Each agent runs in its own git worktree. Agents can research, write code, generate assets, and update files - but changes don't touch your main branch until you explicitly approve them. Experiment freely with full isolation and safety.

### Parallel Agent Execution

Launch multiple agents from a single task screen. Each agent gets its own worktree sandbox and independent timeline, enabling simultaneous experiments without interference.

### Unified Curation & Control

Review every agent's commits, logs, and generated assets in a single unified editor. Diff changes inline to see exactly what changed. Merge only the pieces you approve. Keep your main workspace pristine and controlled.

### Real-Time Streaming

Live logs and structured events provide real-time visibility into task execution progress. Watch agents work and intervene when needed.

### Approval Workflow

Built-in approval gates for risky operations. Review and approve or reject file modifications and command executions before they're applied. Built-in safety checks ensure you stay in control.

## Installation

### Requirements

- macOS (Apple Silicon or Intel)
- [Claude(Claude Code)](https://claude.com/product/claude-code) subscription
- [ChatGPT(Codex)](https://openai.com/codex) subscription

### Download

Download the latest release for your platform:

- [Apple Silicon (arm64)](https://github.com/yusa-n/chronist-ai/releases/latest)
- [Intel (x64)](https://github.com/yusa-n/chronist-ai/releases/latest)

## How It Works

1. **Feed Knowledge** - Your ideas, notes, and research serve as context for AI agents
2. **Launch Tasks** - Create tasks that spawn agents in isolated worktrees
3. **Monitor Progress** - Watch real-time logs and streaming output as agents work
4. **Review Changes** - Inspect commits, diffs, and generated assets in the unified editor
5. **Approve & Merge** - Merge only the changes you approve into your main branch

## Use Cases

- **Autonomous Coding Tasks** - Run Claude to implement features, fix bugs, or refactor code
- **Safe AI Experimentation** - Test AI-driven code generation without risking your main codebase
- **Code Review & Execution** - Approve AI-suggested changes before they're applied
- **Parallel Development** - Accelerate work by delegating tasks to multiple agents simultaneously

## Privacy & Security

Chronist is local-first. Your files and knowledge stay on your machine. Agent execution happens locally through Claude Code. No data is sent to external servers beyond what Claude Code itself requires.

## Links

- [Website](https://chronist-ai.com)
- [Privacy Policy](https://chronist-ai.com/privacy)
- [Terms of Service](https://chronist-ai.com/terms)

## License

Copyright 2025 Skunc, Inc.

## Contact

- X/Twitter: [@n_asuy](https://x.com/n_asuy)
