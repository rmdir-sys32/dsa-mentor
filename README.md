# DSA Mentor

A hint-first coach for data structures and algorithms problems. It helps you build your own reasoning through pattern diagnostics, graduated hints, and structured problem-solving workflows for dynamic programming, greedy algorithms, and other common techniques.

## What it does

- Helps narrow down an approach from the constraints and problem structure.
- Teaches DP state, transition, base cases, evaluation order, and the distinctions between memoization, tabulation, and space optimization.
- Requires a correctness argument for greedy choices.
- Gives hints in stages and withholds full code unless you explicitly request it.

## Install

This repository packages the same `SKILL.md` for these tools:

- **Codex:** `.agents/skills/dsa-mentor/SKILL.md` (project skill; also supported from `~/.codex/skills/dsa-mentor/`).
- **Gemini CLI:** `.agents/skills/dsa-mentor/SKILL.md` (workspace skill). Or install the root skill with `gemini skills install https://github.com/rmdir-sys32/dsa-mentor.git`.
- **Google Antigravity:** `.agents/skills/dsa-mentor/SKILL.md` (workspace skill).
- **Claude Code:** `.claude/skills/dsa-mentor/SKILL.md` (project skill; copy to `~/.claude/skills/dsa-mentor/` for user-wide use).

## Try it

Ask: “Use DSA Mentor. Help me solve this problem with hints only: [paste problem].”

To request more help, say “give me the next hint.” Ask for a full solution only when you are ready to see one.
