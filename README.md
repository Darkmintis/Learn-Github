<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/221352995-5ac18bdf-1a19-4f99-bbb6-77559b220470.gif" alt="Dipesh Mahat Banner" width="100%" style="border-radius: 10px;" />
</p>

# 🚀 Learn-GitHub - simple, friendly Git & GitHub practice

Welcome! This tiny repo is written to be short, helpful, and fun for absolute beginners. If you don't know Git or GitHub yet, start here. You're in the right place.

**What is Git?**
- Git is a tool that tracks changes to files on your computer. You create snapshots (commits) as you work so you can go back, compare, or share work.
- Think of it as "Save points for your code". Every time you commit, Git saves exactly what changed and why.

**What is GitHub?**
- GitHub is a website that hosts Git repositories and adds collaboration features: remotes, pull requests, issues, and project pages.
- Think of it as "cloud storage + collaboration tool for code". You push your Git commits to GitHub to back them up and share with others.

**Key concepts** (short & simple)
- **Repository (repo)**: a project folder tracked by Git
- **Commit**: a saved snapshot with a message describing the change (like "Save Point #1")
- **Branch**: a parallel line of work (e.g., `feature/new-thing`). You work on branches, then merge into `main`
- **Pull Request (PR)**: ask to review and merge your branch into another (usually `main`)
- **Clone**: copy a repo from GitHub to your computer
- **Fork**: your own personal copy of someone else's repo on GitHub
- **Push**: upload your commits to GitHub
- **Pull**: download new commits from GitHub
- **Confused by any term?** Check `docs/glossary.md` for simple explanations.

**Quick hands-on example** (copy & paste these commands)

1. Start a repo locally:

```bash
git init myproject
cd myproject
echo "Hello" > README.md
git add README.md
git commit -m "docs: add README"
```

2. Create a branch and work on something new:

```bash
git checkout -b feature/example
# edit your files here
git add .
git commit -m "feat: add new example"
```

3. Push to GitHub (after creating a repo on GitHub):

```bash
git remote add origin https://github.com/yourname/yourrepo.git
git push -u origin feature/example
```

4. On GitHub, open a Pull Request (PR) to merge `feature/example` into `main` and ask for review.

**How this repo helps you learn**

- **Read first:** `docs/glossary.md` if you're confused by any term
- **Learn Git step-by-step:** `docs/guide.md` (super detailed, explains the "why")
- **Quick reference:** `docs/cheatsheet.md` (copy & paste commands)
- **Write better READMEs:** `docs/markdown.md` (Markdown basics)
- **Better commit messages:** `docs/conventional-commits.md` (how professionals write commits)
- **Make your profile shine:** `profile-readme.md` (create a beautiful GitHub profile)
- **Add GIFs to your repos:** `docs/gif-guide.md` (tips + examples)

**Try the exercise first!**

Do `examples/exercise-1/README.md` to practice forking, branching, and opening a real PR. It's hands-on and fun.

---

**Keep it simple**
- Start with `docs/guide.md` if you're completely new.
- Copy examples into your terminal and try them.
- Don't worry about mistakes — that's how you learn.
- When stuck, check `docs/glossary.md` for a quick explanation.