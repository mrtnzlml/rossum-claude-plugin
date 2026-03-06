# Rossum Claude Plugin

This is a Claude Code plugin for Rossum.ai workflows. It follows the plugin structure defined at https://code.claude.com/docs/en/plugins.

## Project structure

- `.claude-plugin/plugin.json` — Plugin manifest (name, version, metadata)
- `skills/` — All skills as `<name>/SKILL.md` directories
- `README.md` — Public-facing documentation

## Rules

- **README.md must always stay in sync with the project.** When adding, removing, or renaming skills, update README.md to reflect the change in the same commit.
