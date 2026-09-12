# Sunless Glow

A responsive single-page website for Sunless Glow, a home-based spray tanning studio in Leicester.

## Live site

- Production site: https://sunlessglow.co.uk
- GitHub Pages: https://darrenFrowen.github.io/sunlessGlow/

## Overview

This project contains the website for a beauty and tanning business, including:

- hero section and brand styling
- about section and owner profile
- service and studio information
- photo gallery with lightbox viewing
- interactive FAQ section
- booking and contact details
- mobile-friendly responsive layout

## Best-practice guidance

This repository is intended to be a public-facing marketing site. That means it is generally fine to keep it public on GitHub, provided there is no private or sensitive information included.

Before publishing anything to the repo, avoid adding:

- private personal details
- personal addresses or home location data beyond what is already public
- personal mobile numbers not intended for public use
- client images that are not approved for public use
- API keys or secrets

For a business website hosted on GitHub Pages, a public repo is usually the standard and expected approach.

## Local development

Open the project in a browser or use a local static file server. For simple local testing, opening `index.html` directly is enough for most changes.

## Project structure

```text
sunlessGlow/
├── index.html
├── CNAME
├── README.md
├── images/
│   ├── louise.jpg
│   ├── roomLargeNew.jpg
│   └── gallery/
├── .gitignore
└── scripts/
    └── git.ps1
```

## Updating the site

### Quick workflow

```powershell
git add .
git commit -m "Describe your change"
git push origin main
```

### Helper script

A helper script is included for easier use:

```powershell
pwsh ./scripts/git.ps1
```

This script will prompt for a commit message, then add, commit, and push the changes.

## Editing content

### FAQ section

The FAQ content is maintained in `index.html` and can be updated in the editable FAQ block.

### Gallery

New gallery images can be added to `images/gallery/` and then inserted into the gallery grid in `index.html`.

## Maintenance

Keep these updated regularly:

- booking links
- Instagram profile link
- phone number and address if they change
- gallery content and client images
- any seasonal promotional messaging

## Technologies used

- HTML
- CSS
- JavaScript
- Git
- GitHub Pages

## Notes

This site is designed for a public-facing beauty brand and is intentionally simple, fast, and easy to maintain.

---

Built for Sunless Glow
