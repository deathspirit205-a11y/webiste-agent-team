# Reusable Website Agent Team

A reusable specialist team for websites across industries and stacks, designed for Claude Code in VS Code.

## Agents
- web-project-orchestrator
- website-discovery-researcher
- seo-strategist
- information-architecture-ux
- content-strategist
- visual-design-ux
- web-engineer
- technical-seo-performance
- qa-accessibility-security

## Install globally for Claude Code
Global Claude Code subagents live in `~/.claude/agents/`.

1. Extract this ZIP.
2. In Terminal run: `mkdir -p ~/.claude/agents`
3. Copy the extracted `agents/` folder contents into `~/.claude/agents/`. Example if extracted to Downloads:
   `cp -R ~/Downloads/website-agent-team/agents/. ~/.claude/agents/`
4. Inspect for same-named files before overwriting any existing agents.
5. Restart Claude Code if agents do not appear.

These definitions are global on this machine and reusable across repositories. Project facts belong in each repository's `CLAUDE.md` and `docs/PROJECT-BRIEF.md`.

## Start a project
Open the target repo in VS Code, start Claude Code, invoke `web-project-orchestrator`, and ask it to read `docs/PROJECT-BRIEF.md`. Start with a read-only audit. Approve the plan before implementation.

## Safety
Subagents do not prevent simultaneous file conflicts. Use separate worktrees or exclusive file ownership; serialize shared-file edits. Never allow unapproved commits, pushes, merges or deployments.

## Copilot note
VS Code Copilot uses a different `.agent.md` format in `.github/agents/` or `~/.copilot/agents/`. This package is Claude Code format (`.md` in `~/.claude/agents/`); do not assume harness fields are interchangeable.# webiste-agent-team
Reusable AI specialist agents for website research, SEO, design, development and quality assurance.
