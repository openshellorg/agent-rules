# openshellorg org overlay

Shared rules and Cursor skills live in **dev-centr/agent-rules**. This repo is the org overlay only - it does not vendor a snapshot.

When assembling context for this org's repos, resolve:

- `AGENT_RULES_PATH` = `$CODE_ROOT/github.com/dev-centr/agent-rules`
- Org overlay = this `AGENTS.md`

Shared changes: PR `dev-centr/agent-rules`. Org-only: commit here.

## Docs template

- `DOCS_TEMPLATE`: https://github.com/dev-centr/agent-rules/blob/main/templates/docs-default.md
- Clone path: `templates/docs-default.md` inside `dev-centr/agent-rules` (workspace-relative `dev-centr/agent-rules/templates/docs-default.md` when the hive root is the workspace).
- This org uses the suggested default. Replace the URL to choose a different template. Do not paste the template body here.
- When you apply this template, or when someone asks what this org's docs rules are, link the template file in chat (workspace-relative markdown link when the canonical clone is in the workspace; otherwise the URL above).
