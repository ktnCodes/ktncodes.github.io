# ktncodes.github.io — Project Context

## What This Project Is

Kevin's v1 blog and portfolio site. Built with Hugo + PaperMod theme. Being archived — all new content goes to ktncodes-v2 (ktncodes.com).

**Status:** Archiving
**Live site:** https://ktncodes.github.io/

---

## Tech Stack

- Hugo static site generator
- PaperMod theme (git submodule)
- GitHub Actions → GitHub Pages deployment

---

## Folder Structure

```
ktncodes.github.io/
├── hugo.toml        # Site configuration
├── content/         # Blog post sources (Markdown)
├── layouts/         # Hugo layout overrides
├── themes/          # PaperMod theme (submodule)
└── archetypes/      # Hugo content templates
```

---

## Routing Table

| Task                        | Load These                     | Skip These       |
|-----------------------------|--------------------------------|------------------|
| Review old posts            | `content/posts/`               | themes/, layouts/|
| Fix redirects or config     | `hugo.toml`                    | content/         |
| Understand site structure   | This file, README.md           | —                |
