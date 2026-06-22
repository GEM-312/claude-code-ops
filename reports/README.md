# Weekly Claude Code Maintenance Reports

Chronological index of weekly reports for Marina's iOS projects (RenaissanceArchitectAcademy + ChefAcademy).

Each report covers: what's new in Claude Code that week, per-project `.claude/` health checks, and any PRs opened for safe mechanical upgrades.

| Date | Highlights |
|------|------------|
| [2026-05-20](./2026-05-20.md) | v2.1.139–2.1.145; `/run`+`/verify` bundled skills; `/model` session-only default; 3 safe-change PRs opened |
| [2026-05-25](./2026-05-25.md) | v2.1.146–2.1.150; deny-override security fix (v2.1.146); pinned background sessions; `/code-review --comment`; `/usage` per-category; 1 safe PR (RAA deny-path fix) |
| [2026-06-01](./2026-06-01.md) | v2.1.152–2.1.159; Opus 4.8 + dynamic workflows; `MessageDisplay` hook; skills auto-load from `.claude/skills/`; `/reload-skills`; 2 safe PRs (RAA bash-guard port [#19](https://github.com/GEM-312/RenaissanceArchitectAcademy/pull/19); ChefAcademy code-reviewer 4.8 + adaptive-layout-engineer path [#2](https://github.com/GEM-312/ChefAcademy/pull/2)) |
| [2026-06-08](./2026-06-08.md) | v2.1.160–2.1.168; `ultracode` keyword rename; `fallbackModel` setting; glob deny rules; `additionalContext` for Stop/SubagentStop hooks; `$HOME` deny-rule security fix; 2 safe PRs (RAA + ChefAcademy `$schema` in settings.json); ⚠️ RAA PR #19 still open |
| [2026-06-15](./2026-06-15.md) | v2.1.169–2.1.177; **Claude Fable 5** released; sub-agents nest 5 deep; `--safe-mode` flag; `/cd` command; `post-session` hook (remote runners); `disableBundledSkills` setting; no new config PRs; ⚠️ RAA PRs #19 + #20 still unmerged (2 weeks) |
| [2026-06-22](./2026-06-22.md) | v2.1.178–2.1.185; Agent teams simplified (no TeamCreate/Delete); `Tool(param:value)` permission syntax; **⚠️ 0-byte file fix for Dropbox/cloud-synced folders** (v2.1.181 — ChefAcademy urgent update); prompt caching fix on custom base URL; auto mode blocks destructive git; `attribution.sessionUrl` setting; no new PRs; ⚠️ RAA PRs #10/#19/#20 still unmerged |
