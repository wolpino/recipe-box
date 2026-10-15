@AGENTS.md

## Claude Code
- Use plan mode before changing packages/contracts, supabase/migrations or RLS policies.
- One task per session, in its own git worktree on a branch named task/<R-ID>-<short-slug>.
- Say a task is done only after pnpm verify passes; put the result summary in the PR.
- Have a separate session review each PR against its acceptance criteria; the author never reviews their own PR.
- Keep this file and AGENTS.md short; link to docs/ for anything long.
