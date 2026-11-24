# human-communication

An open-source [Agent Skill](https://agentskills.io) by [Canonry](https://canonry.ai) that teaches AI coding agents how to communicate, summarize completed work, give honest ETA updates, surface blockers, and write zero-rediscovery handoffs for humans and downstream agents.

## Install

### Agent Skills CLI (Claude Code, Codex, Cursor, Windsurf, Antigravity, and others)

```bash
npx skills add Canonry/human-communication
```

### Claude Code Plugin

```text
/plugin marketplace add Canonry/human-communication
/plugin install human-communication@canonry-human-communication
```

### Manual Drop-In

Copy [`skills/human-communication/SKILL.md`](skills/human-communication/SKILL.md) into your agent's skills directory (for example `.claude/skills/human-communication/SKILL.md`, `.agents/skills/human-communication/SKILL.md`, or `~/.codex/skills/human-communication/SKILL.md`).

## What's Inside

- **5 core principles**: Bottom Line Up Front (BLUF), receipts over vague reassurance, 3-speed scannable layout, natural tone matched to user urgency, and showing rather than narrating.
- **5 copy-paste blueprints**: Completed work summaries, live ETA/progress updates, bug/blocker reports, design trade-off calls, and agent-to-agent handoffs.
- **Anti-pattern table**: Concrete replacements for the most common robotic agent habits.
- **5-second pre-send check**: Final pass before sending any substantive response.

## Repository Layout

```text
.
├── .claude-plugin/
│   ├── marketplace.json
│   └── plugin.json
├── skills/
│   └── human-communication/
│       └── SKILL.md
├── LICENSE
└── README.md
```

## License

MIT. See [LICENSE](LICENSE).
