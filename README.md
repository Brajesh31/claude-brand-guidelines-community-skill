# Claude Brand Guidelines Community Skill

A community-oriented repository containing a skill for applying Anthropic's visual identity to presentation and document artifacts. The current skill instructions define brand colors, typography, text hierarchy, and accent styling.

## What It Covers

- **Color system:** Core dark, light, and gray tones.
- **Accent colors:** Orange, blue, and green for shapes and highlights.
- **Typography:** Poppins for headings and Lora for body text.
- **Fallback behavior:** Arial and Georgia when the preferred fonts are unavailable.
- **Visual consistency:** Readable hierarchy and color use across formatted artifacts.

## Installation

Clone the repository into your Claude skills directory:

```bash
git clone https://github.com/Brajesh31/claude-brand-guidelines-community-skill.git ~/.claude/skills/brand-guidelines-community
```

## Using the Skill

Example request:

```text
Use the brand-guidelines-community skill to apply Anthropic-style
colors and typography to this slide deck.
```

Read [SKILL.md](SKILL.md) for the complete styling instructions. The current skill uses Anthropic's palette and type guidance, including automatic font fallbacks.

## Brand Palette

| Role | Color |
|---|---|
| Dark | `#141413` |
| Light | `#faf9f5` |
| Mid gray | `#b0aea5` |
| Light gray | `#e8e6dc` |
| Orange accent | `#d97757` |
| Blue accent | `#6a9bcc` |
| Green accent | `#788c5d` |

## Typography

Use Poppins for headings and Lora for body copy when installed. Arial and Georgia are the documented fallbacks.

## License

See [LICENSE](LICENSE) for the repository license.
