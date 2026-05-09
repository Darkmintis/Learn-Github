# Git & GitHub Cheatsheet

Quick commands for day-to-day use.

Initialize
- `git init` — create a repo

Inspect
- `git status`
- `git log --oneline --graph --decorate --all`

Save changes
- `git add <file>`
- `git commit -m "type(scope): short message"`
- `git push` (first push may require `-u origin main`)

Branching
- `git checkout -b feature/xxx`
- `git push -u origin feature/xxx`

Update local
- `git fetch` then `git merge` or `git pull` (pull = fetch + merge)

Undo (careful)
- `git restore <file>` — discard local edits
- `git reset --soft HEAD~1` — undo last commit but keep changes staged

Staging tips
- Make small, focused commits
- Use Conventional Commits for clearer history
