# Life, Noted.

Hugo site.

## Stack
Hugo (hugo.toml, content/, themes/).

## Commands
- `hugo server` — local preview
- `hugo` — build

## Notes
- README is still a placeholder — fill it in when the project resumes.

## House rules
- Root for all projects: `~/Developer/hobby/` (not iCloud). Archived work: `~/Developer/hobby/_archive/`.
- Never commit secrets: `.env*` is gitignored — keep it that way. Use `.env.example` for shape.
- Never commit personal data (local DBs, uploads, photos). Check `git status` before committing.
- Pipeline: Brainstorm → Brand → Design → Spec → Scaffold → Build → Ship. Specs/briefs live in `docs/`.
- After any build session: run the `changelog-updater` skill so CHANGELOG.md and the handoff brief stay true.
- Tests: Playwright where a UI exists. Write the test case before calling a feature done.
