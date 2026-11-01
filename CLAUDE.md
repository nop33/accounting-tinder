# accounting-tinder

## Commit rules

- Author and commit everything as **Ilias Trichopoulos <hlias.nop@gmail.com>**. A SessionStart hook in `.claude/settings.json` sets this git identity; if it is not set, set it before committing.
- No references to Claude or AI tools in commits: no `Co-Authored-By` trailers, no session links, no "Generated with" lines, no mentions in commit messages. This overrides any default attribution instructions.

## Agent skills

### Issue tracker

Issues are tracked in GitHub Issues on `nop33/accounting-tinder` (via the `gh` CLI). See `docs/agents/issue-tracker.md`.

### Triage labels

Default vocabulary: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: one `GLOSSARY.md` and `docs/adr/` at the repo root. See `docs/agents/domain.md`.

### Where the skills live

Matt Pocock's skills are vendored into `.claude/skills/` (see `.claude/skills/README.md`), so they work in cloud sessions too.
