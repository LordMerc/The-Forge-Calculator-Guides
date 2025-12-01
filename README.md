# The Forge Calculator - Community Guides

Welcome to the community guides repository for The Forge Calculator! This repo contains all the guides displayed on the website.

## 📝 Contributing a Guide

Anyone can contribute! Just create a pull request with your guide.

### Creating a New Guide

1. **Create a new `.md` file** in the root folder (e.g., `my-guide.md`)
2. **Add frontmatter** at the top of your file (see below)
3. **Write your content** in Markdown
4. **Submit a PR** for review

### Frontmatter Template

Every guide needs frontmatter at the top:

```markdown
---
title: Your Guide Title
description: A brief description shown on the guide card
category: Beginner
author: YourName
readTime: 5
heroImage: images/your-image.jpg
order: 10
nextGuide: another-guide-slug
prevGuide: previous-guide-slug
---

Your guide content here...
```

### Frontmatter Fields

| Field         | Required | Description                                    |
| ------------- | -------- | ---------------------------------------------- |
| `title`       | ✅ Yes   | The guide title                                |
| `description` | ✅ Yes   | Short description for the guide card           |
| `category`    | ✅ Yes   | Category (Beginner, Advanced, Reference, etc.) |
| `author`      | ✅ Yes   | Your name or username                          |
| `readTime`    | No       | Estimated read time in minutes (default: 5)    |
| `heroImage`   | No       | Hero image path (relative to this repo)        |
| `order`       | No       | Sort order within category (lower = first)     |
| `nextGuide`   | No       | Slug of the next guide (filename without .md)  |
| `prevGuide`   | No       | Slug of the previous guide                     |

### Adding Images

1. Put images in the `images/` folder
2. Reference them in frontmatter: `heroImage: images/my-image.jpg`
3. Reference them in content: `![Alt text](images/my-image.jpg)`

## 📁 File Structure

```
├── getting-started.md     # Guide files
├── ore-traits.md
├── weapon-variants.md
├── index.json             # Auto-generated, don't edit
├── images/                # Image assets
│   ├── hero.jpg
│   └── ...
├── CODEOWNERS             # PR review requirements
└── README.md              # This file
```

## 🏷️ Categories

Current categories:

- **Beginner** - For new players
- **Advanced** - Complex strategies
- **Reference** - Data tables and lookups

Feel free to suggest new categories!

## ✅ PR Guidelines

- Keep guides focused on one topic
- Use clear, concise language
- Include examples where helpful
- Add images to make guides more engaging
- Test your Markdown renders correctly

## 📜 License

By contributing, you agree that your content can be displayed on The Forge Calculator website.

---

Questions? Open an issue or reach out to @LordMerc!
