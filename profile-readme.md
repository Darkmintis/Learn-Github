# Make Your GitHub Profile Beautiful 👋

Your GitHub profile is like your developer resume. Let's make it shine.

**What's a profile README?**

GitHub lets you create a special README that shows on your profile. If you create a repo with the same name as your username and add a README.md, GitHub displays it at the top of your profile.

**Step 1: Create the repo**

1. Go to github.com and click the "+" in the top-right corner.
2. Select "New repository".
3. Name it exactly like your GitHub username (e.g., if your username is `jane`, name the repo `jane`).
4. Click "Create repository".

**Step 2: Add your README**

1. Click "Create a new file" on your repo page.
2. Name it `README.md`.
3. Paste in this template and customize it:

```markdown
# Hi, I'm Your Name 👋

![hello](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExMzZnNmx5bTlzbmNhbzRnY254dGdndHc0d2RmaXM4a3ZvY2Y5NTV0diZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/du3J3cXyzhj75IOgvA/giphy.gif)

I'm learning Git and GitHub! This is my journey.

## About Me

- 🎓 I'm new to programming and version control.
- 📚 I'm reading about Git workflows, Markdown, and open source.
- 🚀 I'm excited to collaborate and learn from others.

## My Learning Path

- [x] Learn Git basics
- [x] Understand branches and pull requests
- [ ] Contribute to open source
- [ ] Master Markdown

## Cool Things I Like

- Coding
- Problem-solving
- Learning
- [Open source](https://github.com/)

## Let's Connect

- GitHub: [@yourname](https://github.com/yourname)
- Email: your@email.com
- Portfolio: [mywebsite.com](https://mywebsite.com)

---

*Last updated: May 2026*
```

**Step 3: Customize**

- Replace "Your Name" with your real name
- Personalize the sections (About Me, My Learning Path, etc.)
- Add a GIF (see `docs/gif-guide.md` for tips)
- Include links to your portfolio, blog, or social media

**Step 4: Commit and push**

```bash
git add README.md
git commit -m "docs: add profile README"
git push origin main
```

**Design tips**

- Use emojis sparingly (a few personality boosters, not too many)
- Keep it short (recruiters skim)
- Add GIFs for visual interest (1–2 small ones)
- Use checkboxes for learning goals or progress
- Link to your best projects or repos

**Add badges and style (optional)**

You can add badges from `https://shields.io` to show your skills:

```markdown
![Python](https://img.shields.io/badge/Python-3.9-blue)
![Git](https://img.shields.io/badge/Git-Expert-green)
```

**See examples**

Explore other GitHub profiles for inspiration. Click on any project, then click a contributor's avatar to visit their profile.

**Common mistakes to avoid**

- Too long and overwhelming (keep it scannable)
- Too many GIFs (2–3 max)
- Broken links (test them!)
- Outdated info (refresh annually)
