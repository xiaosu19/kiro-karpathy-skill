# Karpathy Coding Principles for Kiro

A [Kiro](https://kiro.dev) skill that enforces disciplined coding behavior, derived from [Andrej Karpathy's observations](https://x.com/karpathy/status/2015883857489522876) on LLM coding pitfalls.

## The Four Principles

1. **Clarify Before Acting** — State assumptions, ask when ambiguous, don't guess
2. **Minimum Viable Code** — Least code that solves the problem, nothing speculative
3. **Surgical Edits** — Every changed line traces to the request, no drive-by refactoring
4. **Goal → Test → Implement** — Define success criteria, verify, then loop

## Install

### Global (all projects)

```bash
mkdir -p ~/.kiro/skills/karpathy-coding-principles
curl -o ~/.kiro/skills/karpathy-coding-principles/SKILL.md \
  https://raw.githubusercontent.com/xiaosu19/kiro-karpathy-skill/main/.kiro/skills/karpathy-coding-principles/SKILL.md
```

### Per-project

```bash
mkdir -p .kiro/skills/karpathy-coding-principles
curl -o .kiro/skills/karpathy-coding-principles/SKILL.md \
  https://raw.githubusercontent.com/xiaosu19/kiro-karpathy-skill/main/.kiro/skills/karpathy-coding-principles/SKILL.md
```

## How It Works

Kiro automatically loads skills from `.kiro/skills/` in your project (or `~/.kiro/skills/` globally). Once installed, Kiro will reference these principles when writing, reviewing, or refactoring code.

## Credits

Inspired by [forrestchang/andrej-karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills) and [Andrej Karpathy's post](https://x.com/karpathy/status/2015883857489522876).

## License

MIT
