# Skills

Agent skills I use for engineering, marketing, and whatever comes next. Each skill is a small, self-contained folder you can read, copy, and adapt.

Follow me on X for new skills and updates: [@imdeadcode](https://x.com/imdeadcode)

## Categories

| Category | What's in it |
| --- | --- |
| [Engineering](skills/engineering/README.md) | Skills for building, reviewing, and shipping software. |
| [Marketing](skills/marketing/README.md) | Skills for positioning, content, campaigns, and growth. |

## Installation

### Claude Code (plugin)

```bash
claude plugin marketplace add ferdelamad/skills
claude plugin install ferdelamad-skills@ferdelamad
```

### Manual

Copy any skill folder into `~/.claude/skills/` (global) or `.claude/skills/` (per project).

## Structure

```
skills/
  <category>/
    README.md          # index of the skills in this category
    <skill-name>/
      SKILL.md         # the skill: frontmatter (name, description) + instructions
      ...              # optional references, scripts, templates
```

## Adding a skill

1. Create `skills/<category>/<skill-name>/SKILL.md` with `name` and `description` frontmatter.
2. List it in that category's `README.md`.
3. Add its path to the `skills` array in `.claude-plugin/plugin.json`.

## License

MIT
