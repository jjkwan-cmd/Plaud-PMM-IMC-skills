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

## Team
PMM/IMC — Plaud
