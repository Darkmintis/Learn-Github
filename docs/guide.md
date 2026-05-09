# Beginner Guide — Learn Git & GitHub

This guide walks through essential Git and GitHub workflows. Don't skip the "Why?" sections — they explain what problems each step solves.

**1) Install & Configure Git**

Why? Git needs to know who you are before you create commits.

```bash
# Download and install
# Visit https://git-scm.com/ and follow the installer

# Tell Git who you are (once)
git config --global user.name "Your Name"
git config --global user.email your@email.com

# Verify it worked
git config --global --list
```

**2) Create a repository**

Why? A repo is a folder where Git tracks all changes.

Locally:
```bash
git init myproject
cd myproject
echo "# My First Project" > README.md
git add README.md
git commit -m "docs: initial commit"
```

On GitHub:
- Go to github.com, click "+" → New repository.
- Choose a name, click Create Repository.
- Follow the instructions to push your local work to GitHub.

**3) Day-to-day workflow (edit, save, commit)**

Why? This cycle saves your work in Git so you can track, share, and revert changes.

```bash
# See what files changed
git status

# Tell Git to track changes to a file
git add myfile.txt

# Create a snapshot (commit) with a message
git commit -m "feat: add new feature"

# Upload commits to GitHub (remote)
git push
```

**4) Branching (work on features safely)**

Why? Branches let you experiment without affecting the main code.

```bash
# Create and switch to a new branch
git checkout -b feature/my-idea

# Make changes, add, commit (same as above)
git add .
git commit -m "feat: implement my idea"

# Push the branch to GitHub
git push -u origin feature/my-idea
```

**5) Pull Requests (ask for review)**

Why? PRs let others review your code and discuss changes before merging.

- Go to GitHub, click "Compare & pull request"
- Write a clear title and description
- Click "Create Pull Request"
- Reviewers can comment; you can make more commits to fix feedback
- Once approved, merge the PR

**6) Good commit messages**

Why? Clear messages make history readable. Future you will thank you.

Use Conventional Commits style (see [docs/conventional-commits.md](../docs/conventional-commits.md)):
- Bad: "update stuff"
- Good: `feat: add login form validation`
- Good: `fix: correct typo in README`

**7) Useful commands (copy these)**

```bash
# See commit history (pretty)
git log --oneline --graph --decorate --all

# See what changed in your files
git diff

# Undo last commit (keep changes)
git reset --soft HEAD~1

# Discard changes to a file
git restore myfile.txt

# Download new commits from GitHub
git fetch
```

**Next steps**
- Practice: do [examples/exercise-1/README.md](../examples/exercise-1/README.md)
- Read [docs/conventional-commits.md](../docs/conventional-commits.md) for better commit messages
- When comfortable, learn about merging, rebasing, and collaborating
