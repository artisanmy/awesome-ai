# awesome-artisan-ai — Design Spec

**Date:** 2026-04-17  
**Status:** Approved

## Overview

Public GitHub repository: a curated awesome list of AI resources for Artisan employees and the broader community. Follows official sindresorhus/awesome standards to qualify for awesome.re inclusion.

## Goals

- Comprehensive coverage of all notable AI domains
- Open community contributions via PRs
- Maintain quality bar through enforced contribution rules
- Achieve sindresorhus/awesome compliance and badge

## Repo Structure

```
awesome-artisan/
├── README.md                        # main list (sindresorhus-compliant)
├── CONTRIBUTING.md                  # contribution guidelines
├── CODE_OF_CONDUCT.md
├── .github/
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── ISSUE_TEMPLATE/
│       └── add-resource.md
└── assets/
    └── logo.png                     # optional badge/banner
```

Single `README.md` as the list. No per-category files. TOC handles navigation.

## Categories (README.md sections)

1. Foundations & Research
2. Large Language Models (LLMs)
3. Image & Vision
4. Audio & Speech
5. Video
6. Multimodal
7. AI Coding & Developer Tools
8. Agents & Automation
9. AI APIs & Platforms
10. Frameworks & Libraries
11. MLOps & Deployment
12. Data & Datasets
13. Prompt Engineering
14. AI Safety & Ethics
15. Learning Resources
16. Communities & Newsletters
17. Blogs & Podcasts

## Entry Format

```
- [Name](https://url) - Single sentence description, starts capital, ends period.
```

Entries within each section sorted alphabetically by name.

## Contribution Rules (CONTRIBUTING.md)

- One item per PR
- Item must be genuinely useful/notable — no self-promo spam
- Description: single sentence, capital start, period end, no marketing language
- Link must be HTTPS and not dead
- Added to correct category in alphabetical order
- New category requires minimum 5 items

## Sindresorhus Compliance

- GitHub repo topic: `awesome`
- Repo description: `🤖 A curated list of awesome AI resources`
- License: CC0
- README has ToC with anchor links
- `awesome-lint` runs via GitHub Actions CI on every PR

## License

CC0 (public domain dedication) — required for sindresorhus/awesome submission.
