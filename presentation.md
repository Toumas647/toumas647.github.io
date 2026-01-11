---
title: "GitHub Pages & Jekyll Presentation"
format:
  revealjs:
    theme: moon
    slide-number: true
    center: true
    controls: true
    progress: true
---

# GitHub Pages & Jekyll

## Building Static Websites

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

*By Toumas*

---

## What is GitHub Pages?

**GitHub Pages** is a free hosting service that allows you to publish websites directly from your GitHub repository.

### Key Features:
- 🌐 Free hosting
- 🚀 Easy deployment
- 🔒 HTTPS support
- 📝 Custom domains

---

## How It Works

1. Create a GitHub repository
2. Add HTML files
3. Enable GitHub Pages in settings
4. Your site is live!

![GitHub Pages Settings](https://via.placeholder.com/600x300/4d7e65/ffffff?text=Static+Website)

---

## What is Jekyll?

**Jekyll** is a static site generator that transforms plain text into static websites.

### Benefits:
- 📄 No database needed
- ⚡ Fast performance
- 🎨 Themes & layouts
- 🔧 Easy customization

---

## Jekyll Themes

GitHub Pages supports **official Jekyll themes** that provide:

- Consistent styling
- Professional layouts
- Responsive design
- Easy configuration

![Jekyll Theme Example](https://jekyllrb.com/img/octojekyll.png)

---

```markdown
## Configuration

Jekyll uses `_config.yml` for settings:

```yaml
# Site settings
title: My GitHub Pages Website
description: A static website
theme: jekyll-theme-slate

# Build settings
markdown: kramdown
