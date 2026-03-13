---
name: Git commands without cd prefix
description: Never use cd prefix with git commands. Run git directly since we're already in the project directory. cd + git compound commands trigger security prompts.
type: feedback
---

Never use `cd "C:\Users\jason\OneDrive\Documents\Claude-Setter-Bot" &&` before git commands. Just run `git status`, `git add`, `git commit`, `git push`, etc. directly.

**Why:** Compound commands with `cd` + `git` trigger a built-in Claude Code security prompt ("Compound commands with cd and git require approval to prevent bare repository attacks") that cannot be bypassed via settings. Running git without the cd prefix auto-approves via the `Bash(git *)` permission rule.

**How to apply:** At session end, run all git commands bare: `git status`, `git diff`, `git add [files]`, `git commit -m "..."`, `git push`. No cd prefix. We're already in the project directory.
