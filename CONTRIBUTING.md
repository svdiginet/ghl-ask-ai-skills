# Contributing

Contributions are welcome: new skills, fixes, and translations.

## Adding or changing a skill

1. One skill per folder: `skills/<slug>/SKILL.md`, slug in kebab-case without accents.
2. Start the file with frontmatter: `name` (the slug) and `description` (one sentence that starts with "Usa esta skill cuando...", because Ask AI reads it to decide when to use the skill).
3. Sections, in order: what the skill needs first, the exact output, and the rules (what it must not promise, invent, or change).
4. Write in Spanish with correct accents and `tú`. No em dashes or en dashes.
5. The skill must not change anything in the account. It drafts, reviews, or recommends.
6. Test it once in a GoHighLevel sub-account (Ask AI > Customize > Skills > + > Upload a skill) and say in the pull request what you tested.
7. Add the skill to the table in `README.md` and a line to `changelog.md`.

## Rules for every change

- No secrets, personal data, client names, or account IDs.
- Only content you wrote or that has a license allowing redistribution; credit the source.
- Claims about platform behavior (GoHighLevel, Google) must match the platform's current documentation.
- Keep pull requests small and focused.

By contributing you agree that your contribution is released under the MIT license of this repository.
