# Architecture

## Components

- `skills/<slug>/SKILL.md`: one skill per folder. YAML frontmatter (`name`, `description`) plus a Markdown body.
- `README.md`: the index of skills and the upload steps.

## Data flow

A user downloads a `SKILL.md` from GitHub and imports it in GoHighLevel: Ask AI > Customize > Skills > + > Upload a skill. Ask AI then uses the skill when a request matches its description, or when called with its slash command.

## External boundaries

GoHighLevel controls how skills are parsed and which account data Ask AI can read. Neither is controlled or guaranteed by this repository.

## Failure modes

- Frontmatter shown as text after upload (not yet tested; tracked in `ROADMAP.md`).
- A skill relies on account data Ask AI cannot read; the skills ask the user for missing data instead of inventing it.
