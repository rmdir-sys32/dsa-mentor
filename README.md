# DSA Mentor

A hint-first coach for data structures and algorithms problems. Build your own reasoning with pattern diagnostics, graduated hints, and structured workflows for dynamic programming, greedy algorithms, and more.

## What it does

- Helps narrow down an approach from the constraints and problem structure.
- Teaches DP state, transitions, base cases, evaluation order, memoization, tabulation, and space optimization.
- Requires a correctness argument for greedy choices.
- Gives hints in stages and withholds full code unless you explicitly request it.

## Install

### Install for one CLI

These commands use the [skills CLI](https://github.com/vercel-labs/skills), which installs the skill into each tool's user-level skills folder:

```sh
# Claude Code
npx skills add rmdir-sys32/dsa-mentor --skill dsa-mentor --global --agent claude-code

# Codex CLI
npx skills add rmdir-sys32/dsa-mentor --skill dsa-mentor --global --agent codex

# Gemini CLI (native installer)
gemini skills install https://github.com/rmdir-sys32/dsa-mentor.git --scope user

# Gemini CLI (via skills CLI)
npx skills add rmdir-sys32/dsa-mentor --skill dsa-mentor --global --agent gemini-cli

# Antigravity CLI
npx skills add rmdir-sys32/dsa-mentor --skill dsa-mentor --global --agent antigravity-cli
```

Omit `--global` to install into the current project. For Antigravity, the repo also includes the workspace skill at `.agents/skills/dsa-mentor/`; open the cloned repository as your workspace to use it without a separate install.

### Use the repository as a project skill

Clone this repository and open it in the tool. It includes `.agents/skills/dsa-mentor/SKILL.md` for Codex, Gemini CLI, and Antigravity, plus `.claude/skills/dsa-mentor/SKILL.md` for Claude Code.

## Invoke

Ask: “Use DSA Mentor. Help me solve this problem with hints only: [paste problem].”

You can also invoke it directly with `/dsa-mentor` in Claude Code, Gemini CLI, or Antigravity CLI, and `$dsa-mentor` in Codex. Ask for the next hint when you want more help; request the full solution only when you are ready to see it.
