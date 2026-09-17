# AI Storyboard Generator Skill

English | [简体中文](./README.zh-CN.md)

Turn a script, scene, or ad brief into a practical shot list and one to four storyboard key-frame images, from inside Claude Code, Codex, or OpenClaw.

> [!IMPORTANT]
> Rendering needs a [Beatra](https://beatra.ai) account and uses credits. The skill itself is free to install.

| Question | Answer |
| --- | --- |
| **What it does** | Turn a script, scene, or ad brief into a practical shot list and one to four storyboard key-frame images. |
| **Requirements** | Python 3.10+ and an agent that loads `SKILL.md` |
| **Cost** | Free to install. Each render uses credits on your Beatra account, and paid steps run only when you ask for that exact render or approve its card. |
| **Works with** | Claude Code, Codex, OpenClaw |

| Skill | Entry point | Version |
| --- | --- | --- |
| [`ai-storyboard-generator`](skills/ai-storyboard-generator) | [SKILL.md](skills/ai-storyboard-generator/SKILL.md) | 0.1.6 |

This repository is published automatically from [beatra-ai/beatra-skills](https://github.com/beatra-ai/beatra-skills/tree/main/skills/ai-storyboard-generator). Report issues there.

## Install

With the [`skills`](https://skills.sh) CLI:

```bash
npx skills add beatra-ai/ai-storyboard-generator-skill
```

With the GitHub CLI:

```bash
gh skill install beatra-ai/ai-storyboard-generator-skill ai-storyboard-generator
```

Or clone this repository and copy `skills/ai-storyboard-generator` into `~/.claude/skills/` for Claude Code,
`~/.agents/skills/` for Codex, or `~/.openclaw/skills/` for OpenClaw.

Or paste this into your agent:

```text
Install the ai-storyboard-generator skill from https://github.com/beatra-ai/ai-storyboard-generator-skill (folder skills/ai-storyboard-generator), then follow its SKILL.md to connect my Beatra account.
```

## What you get

- **Plan before rendering** — Define each beat, shot size, composition, camera intent, timing, dialogue, and sound before committing to visual frames.
- **Generate only decisive frames** — Choose one to four shots that need visual alignment, keeping the board focused and reviewable.

## Use cases

- **Short films and vertical drama** — Translate a scene into an ordered shot plan with clear beats, camera choices, timing, and continuity cues.
- **Advertising concepts** — Map the product message, hook, action, and closing beat into frames that creative and production teams can compare.
- **Animation and creative pitches** — Establish composition, character placement, locations, and visual rhythm before a larger production begins.

## FAQ

### Do I need a finished screenplay?

A scene outline, advertising brief, or story concept is enough when it includes the core action, audience, and intended format.

### How many storyboard images can I create?

The workflow plans the full shot list, then creates one to four selected key frames as individual storyboard images.

### Can I use character or location references?

Yes. Provide them in a clear order and name the role of each reference so the selected frame preserves the intended visual direction.

## Updates

Each installed skill checks for a new version at most once a day, verifies the
official archive before replacing itself, and leaves your installation untouched
if anything fails. Turn it off at any time — see
`references/automatic-updates-and-safety.md` inside the skill.

## License

[MIT-0](LICENSE) — free to use, modify, and redistribute, including
commercially. No attribution required. Same terms as these skills carry on
ClawHub.
