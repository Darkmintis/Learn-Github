Exercise 1 — Edit README and open a PR

Goal: practice editing a repository and opening a pull request.

Steps
1. Fork this repository on GitHub (click the Fork button on the repo page).
2. Create a branch on your fork: `git checkout -b fix/readme-typo`
3. Edit `README.md` — fix a typo or add a short friendly sentence.
4. Commit and push your branch: `git add README.md` → `git commit -m "docs: fix typo"` → `git push -u origin fix/readme-typo`
5. Open a Pull Request on GitHub — go to the original repo and click "New Pull Request". Describe your change and submit.

What you'll practice: forking, branching, committing, pushing, and opening a Pull Request.

Hints
- A fork is your own copy of the repo so you can experiment without affecting the original.
- A branch lets you work on changes separately before merging.
- A Pull Request is how you ask the repo owner to review and merge your changes.

Commit message practice
- Use Conventional Commits style for commit messages. Example:

```
docs(readme): fix typo in getting started
```

Optional extension
- After making the change, try adding a small GIF inline to your edit (see [docs/gif-guide.md](../../docs/gif-guide.md)) and push another commit.
