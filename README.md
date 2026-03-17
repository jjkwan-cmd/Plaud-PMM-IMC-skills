# plaud-pmm-imc

Claude skills and automation for the Plaud PMM/IMC team.

## Structure

```
skills/                    Claude skill files — install these in Claude settings
  copywriting audit/       Content QA and cross-deliverable audits
```

## Skills

### copywriting audit
Acts as Plaud's senior content and copy auditor. Covers:
- Reviewing and rewriting existing copy against brand voice
- QA against brand voice, style guide, and content-type rules
- Cross-deliverable content audits
- Diagnosing issues across DTC pages, ads, EDMs, social, PR, UX, decks, Amazon listings

**To install:** Add `skills/copywriting audit/SKILL.md` and `skills/copywriting audit/references/` via Claude → Settings → Skills.

## Adding new skills

1. Create a new folder under `skills/`
2. Add `SKILL.md` with YAML frontmatter (`name`, `description`)
3. Add a `references/` subfolder for any supporting docs the skill loads on demand
4. Package and install

## Changelog

### 2026-03-17
**`skills/copywriting audit/references/brand-voice.md`**
- Added "Voice = constant. Tone = adaptive." section with brand voice summary
- Expanded four voice principles with sharper "In Practice" descriptions
- Added tone dimensions table (Formality, Emotion, Energy, Confidence)
- Added approved voice examples section with full updated press boilerplate (1,500,000 users; full compliance cert list)
- Added correct product names section (includes Plaud Desktop)
- Added compliance certifications reference section (ISO27001, ISO27701, SOC 2, HIPAA, GDPR, EN18031)
- Refined tone-by-scenario table: sentence case headings, expanded enterprise example, added closing note

## Team
PMM/IMC — Plaud
