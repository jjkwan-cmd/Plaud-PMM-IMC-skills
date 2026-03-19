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
- Product claim fact-checking against the Products, Capabilities, and Features SSOT databases in Notion (via MCP) — flags inaccurate claims, wrong platform attribution, unreleased features promoted as live, and unsupported competitive claims

**To install:** Add `skills/copywriting audit/SKILL.md` and `skills/copywriting audit/references/` via Claude → Settings → Skills.

## Adding new skills

1. Create a new folder under `skills/`
2. Add `SKILL.md` with YAML frontmatter (`name`, `description`)
3. Add a `references/` subfolder for any supporting docs the skill loads on demand
4. Package and install

## Changelog

### 2026-03-19
**`skills/copywriting audit/SKILL.md`**
- Renamed skill ID from `plaud-copywriting` to `plaud-copywriting-audit`
- Added `SSOT fact-check` section: live Notion MCP queries against three databases (Products, Capabilities, Features) to verify every product claim in copy before publishing
- Fact-check workflow covers claim extraction, SSOT matching, 8-point check table, structured output format, and hard-stop escalation rules

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
