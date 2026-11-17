# Human_claud

A Claude Code skill for writing text and designs without the usual signs of AI generation: em dashes, semicolons, title case headings, colons in titles, generic vocabulary, bullet lists everywhere, washed-out colors.

The skill applies to chat replies, articles, reports, emails, slides and web pages.

## What it avoids

- Punctuation: no em dashes, no double hyphens, no triple hyphens, no semicolons.
- Headings: sentence case, no colons, few headings.
- AI vocabulary in English and French (*delve*, *tapestry*, *au cœur de*, *force est de constater*, and similar).
- Chatbot habits: openers like "Certainly!", closers like "Feel free to ask", reflexive lists of three.
- Unnecessary sections and subsections, and a bullet list under every paragraph.
- Pale colors and hard-to-read fonts. The default font is Avenir, unless a journal or template requires another.

## Installation

Copy `SKILL.md` into a `Human_claud` folder in your Claude Code skills directory:

```bash
mkdir -p ~/.claude/skills/Human_claud
curl -o ~/.claude/skills/Human_claud/SKILL.md https://raw.githubusercontent.com/MadBezoui/Human_claud/main/SKILL.md
```

Restart Claude Code or open a new session. The skill loads when you ask for a text or a design.

## Limits

The skill does not try to fool AI detectors. Its goal is natural, readable writing. It does not remove information or nuance: only the form changes.

## License

Free to use.
