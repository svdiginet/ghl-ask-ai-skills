# Security and data

- Data stored: none. The repository holds Markdown skills only.
- Data handled at runtime: the skills run inside the user's own GoHighLevel Ask AI; any account data stays in GoHighLevel and is governed by the user's account and HighLevel's terms.
- The skills never instruct Ask AI to change account settings, send messages, or publish; they draft, review, and recommend.
- Secrets: none required; any found must be reported privately (see `SECURITY.md`).

## Accepted duplication

`auditoria-subcuenta` and `reporte-mensual-cliente` repeat the same "Datos de la subcuenta" paragraph on purpose. Each SKILL.md is uploaded to GoHighLevel on its own, so a skill cannot reference a shared file; the rule must live inside each skill that reads account data.
