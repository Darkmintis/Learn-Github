# Markdown Basics — write better READMEs

Markdown is a simple text format that becomes pretty HTML. Here's what you need to know.

**Headings** (# at the start of a line)
```markdown
# H1 — Main title (rare in README)
## H2 — Section heading (most common)
### H3 — Subsection
#### H4 and deeper (less common)
```

Result:
- Your text becomes larger and bold
- GitHub auto-links headings in the "Table of Contents"

**Emphasis** (bold, italic, strikethrough)
```markdown
*italic* or _italic_
**bold** or __bold__
~~strikethrough~~
```

Result: *italic*, **bold**, ~~strikethrough~~

**Lists** (unordered or numbered)
```markdown
- Item 1
- Item 2
  - Nested item (use 2 spaces)

1. First
2. Second
3. Third
```

Result:
- Item 1
- Item 2
  - Nested item

**Code** (inline or code block)

Inline: Wrap with backticks `` ` ``
```markdown
Use the `git push` command to upload commits.
```

Result: Use the `git push` command to upload commits.

Code block: Wrap with three backticks and add language:
````markdown
```bash
git add .
git commit -m "feat: add feature"
```
````

Result:
```bash
git add .
git commit -m "feat: add feature"
```

**Links** (point to URLs)
```markdown
[Click here](https://github.com)
[Go to docs](./docs/guide.md)
```

**Images & GIFs** (embed visuals)
```markdown
![alt text](https://example.com/image.gif)
```

Why alt text? It describes the image for people who can't see it and helps search engines.

**Tables** (organize data)
```markdown
| Feature | Description |
|---|---|
| Git | Version control tool |
| GitHub | Collaboration website |
```

Result:
| Feature | Description |
|---|---|
| Git | Version control tool |
| GitHub | Collaboration website |

**Pro tips for beginners**
- Use headings to break up your README (people skim)
- Add a "Quick Start" section near the top
- Use lists instead of long paragraphs
- Wrap code examples in code blocks (with ```)
- Keep lines short (max 80–100 chars) for readability
- Always add alt text to images for accessibility
