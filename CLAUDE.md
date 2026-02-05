# CLAUDE.md

## Repository Overview

This is the **GitHub profile repository** for [Akhlaq Ahmad](https://github.com/akhlaqahmad). It is a special repository (username matches repo name) whose `README.md` is rendered on the owner's GitHub profile page. The repository contains no application source code — it is purely a personal branding and introduction page.

## Repository Structure

```
/
├── README.md            # GitHub profile content (HTML + Markdown)
├── LICENSE              # MIT License
├── akhlaq-banner.jpg   # Banner image displayed at the top of the profile (~3.7 MB, 4950x1238)
└── CLAUDE.md           # This file — guidance for AI assistants
```

## Key Files

| File | Purpose |
|------|---------|
| `README.md` | The entire profile page. Uses a mix of raw HTML (`<h2>`, `<h3>`, `<p>`, `<div>`, `<a>`, `<img>`) and GitHub-flavored Markdown. Contains shield.io badges, GitHub stats widgets, and social links. |
| `akhlaq-banner.jpg` | Hero banner image referenced at the top of `README.md`. Large file — avoid re-committing unless actually changed. |
| `LICENSE` | Standard MIT License. |

## Content Conventions

### README.md Format
- **Banner**: Raw `<img>` tag at the very top referencing `akhlaq-banner.jpg`
- **Headings**: Centered HTML headings (`<h2>`, `<h3>`) for the intro section
- **Bullet lists**: Standard Markdown list items with emoji prefixes for visual appeal
- **Badges**: Inline shield.io badge images (`img.shields.io`) for the skills/tools section
- **Stats widgets**: GitHub Readme Stats (`github-readme-stats.vercel.app`) and GitHub Streak Stats (`github-readme-streak-stats.herokuapp.com`) with the `radical` theme and `hide_border=true`
- **Section separators**: Horizontal rules (`---`) between major sections
- **Links**: Standard Markdown links for social/contact info

### Sections (in order)
1. Banner image
2. Name and title (centered HTML)
3. Current work and interests (emoji bullet list)
4. Favorites (emoji bullet list)
5. Languages & Tools (shield.io badges)
6. GitHub Stats (dynamic stat cards)
7. Buy Me A Coffee (centered CTA button)
8. Connect With Me (contact links)
9. Footer CTA

## Development Workflow

There is no build, test, or CI/CD pipeline. Changes are purely content edits:

1. Edit `README.md` to update profile content
2. Replace `akhlaq-banner.jpg` to change the banner image
3. Commit and push — changes are live immediately on the GitHub profile

## Guidelines for AI Assistants

- **No build/test steps exist.** Do not attempt to run `npm install`, `make`, or any build commands.
- **README.md is the product.** Treat it with the same care as production code — preview rendering matters.
- **Preserve the existing style.** Use the same HTML/Markdown hybrid approach, emoji conventions, and badge format already present.
- **Be mindful of the banner image size.** Avoid unnecessarily re-adding or modifying `akhlaq-banner.jpg` as it is ~3.7 MB.
- **Keep shield.io badge format consistent.** Use `style=flat-square` and appropriate brand colors/logos.
- **GitHub stats widgets use the `radical` theme.** Maintain `theme=radical&hide_border=true&include_all_commits=true` for consistency.
- **Do not add tooling or config files** (e.g., `.eslintrc`, `package.json`) unless explicitly requested. This is intentionally a minimal repository.

## Owner Profile

- **Name**: Akhlaq Ahmad
- **Role**: iOS Developer, Tech Consultant, Aspiring Entrepreneur
- **Location**: Kuala Lumpur, Malaysia
- **Current Work**: OCBC Business App (Swift)
- **Tech Focus**: Swift, Clean Swift, MVVM, MVC, Protocol-oriented design, Firebase
- **Tools**: Xcode, Git, Jira, Postman, VS Code, Figma, Linux
