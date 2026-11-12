# Xincheng Tan — Personal Academic Homepage

Personal homepage built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template, hosted on GitHub Pages at **https://xincheng-tan.github.io/**.

## Deploy to GitHub Pages

1. Create a repository named exactly `Xincheng-Tan.github.io` under your GitHub account (if it does not exist yet).
2. Push this folder to the `main` branch:
   ```bash
   git init            # skip if already a git repo
   git add -A
   git commit -m "Personal homepage"
   git branch -M main
   git remote add origin https://github.com/Xincheng-Tan/Xincheng-Tan.github.io.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root)**.
4. Wait 1–2 minutes, then visit https://xincheng-tan.github.io/.

No local build is required — GitHub Pages builds the Jekyll site automatically.

## Site structure

| Path | Purpose |
|---|---|
| `_config.yml` | Site-wide settings (name, bio, email, links) |
| `_pages/about.md` | Homepage content |
| `_pages/publications.html` | Publications list page |
| `_publications/` | One markdown file per publication |
| `_data/navigation.yml` | Header navigation links |
| `images/profile.jpg` | Profile photo |
| `files/` | PDFs and other downloadable files |

## Adding a publication later

Create a file in `_publications/`, e.g. `_publications/2026-01-01-my-paper.md`:

```markdown
---
title: "Paper Title"
collection: publications
category: conferences        # conferences | manuscripts | books | preprints
permalink: /publication/2026-01-01-my-paper
excerpt: "One-sentence summary (optional)."
date: 2026-01-01
authors: "<strong>Xincheng Tan</strong>, Coauthor Name<sup>†</sup>"
venue: "NeurIPS 2026"
paperurl: "https://arxiv.org/abs/xxxx.xxxxx"   # shown as the arXiv button; the title links here
links:                                           # extra buttons (optional)
  - name: "Code"
    url: "https://github.com/..."
citation: "Xincheng Tan et al. (2026). Paper Title. NeurIPS 2026."
---

Optional longer description here.
```

It will appear automatically on the homepage and the Publications page after pushing (rendered by `_includes/publication-card.html`).
