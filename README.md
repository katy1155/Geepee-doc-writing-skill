# gp-doc-voice

A Claude Skill for writing NID Graduation Project (GP) document copy in a senior product designer / design director voice — body text, captions, sticky notes, section intros, and chapter cold-opens.

Built and refined over multiple editing rounds on a real GP document. Designed so that anyone writing a GP doc gets the same level of writing discipline without re-discovering the rules themselves.

## What it does

Tells Claude:
- What voice to write in (senior design director, first person, direct, no hedging).
- What content logic to follow (why first, then how, then connect to adjacent sections).
- How to build narrative hooks between paragraphs and chapters that carry real information instead of generic transitions.
- How much depth a section needs (most need the "why," not a screenshot walkthrough).
- Specific phrases and structural patterns to avoid that read as AI-generated filler.
- How to write sticky notes and research observations as mid-scan noticing, not conclusions.
- To never invent facts, numbers, or names not already in the conversation.

## Dependencies

This skill calls three other writing-discipline skills before every draft. You need all three installed for it to work as intended:

- **avoid-ai-writing** — sentence-level AI pattern detection and removal.
- **stop-slop** — phrase-level banned constructions, rhythm checks, active voice enforcement.
- **anti-slop-writing** — inflated significance language, staccato contrast detection, flow-by-relation between paragraphs, and a full editing pass.

If you don't have these three, the skill still works — you'll get the voice and content logic — but the anti-slop pass won't run automatically.

## How to install

**Claude Code**

Clone this repo, then copy the folder into your skills directory:

```bash
git clone https://github.com/<your-username>/gp-doc-voice.git
cp -r gp-doc-voice ~/.claude/skills/gp-doc-voice
```

Or, to scope it to one project:

```bash
cp -r gp-doc-voice <your-project>/.claude/skills/gp-doc-voice
```

**Claude.ai / Claude apps (web, desktop, mobile)**

1. Download this repo as a zip (Code → Download ZIP on GitHub), or just grab the `SKILL.md` file.
2. In Claude, go to Settings → Capabilities → Skills.
3. Upload the folder or zip.

## Customizing

The banned-phrases lists ("never reuse these opening patterns" and "never reuse these constructions") are meant to grow. When Claude produces a new phrase that feels like filler in your own document, add it to the relevant list in `SKILL.md` so it doesn't come back in a later section.

## License

MIT — use it, fork it, improve it.
