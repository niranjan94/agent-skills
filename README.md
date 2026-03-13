# agent-skills

My personal collection of skills I use with AI Agents. Packaged as a [Claude Code plugin](https://docs.anthropic.com/en/docs/claude-code/skills).

## Skills

| Skill | Description |
|-------|-------------|
| [pin-github-actions](skills/pin-github-actions/SKILL.md) | Audit and pin GitHub Actions to commit SHAs with version comments for supply chain security |
| [postgres-explorer](skills/postgres-explorer/SKILL.md) | Explore and query PostgreSQL databases in strict read-only mode via psql |

## Installation

Add this plugin to your Claude Code configuration:

```bash
npx skills add niranjan94/agent-skills
```

## Adding a new skill

Create a new directory under `skills/` with a `SKILL.md` file:

```
skills/
  my-new-skill/
    SKILL.md
```

Each `SKILL.md` needs YAML frontmatter with `name` and `description` fields, followed by the skill instructions in Markdown.

## License

[MIT](LICENSE)
