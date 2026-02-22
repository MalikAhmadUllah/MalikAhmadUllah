# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Repository Overview

This is a **GitHub profile README repository** — a special GitHub feature where the repository name matches the owner's GitHub username (`MalikAhmadUllah/MalikAhmadUllah`). The `README.md` at the root of this repository is automatically rendered on the owner's public GitHub profile page at `https://github.com/MalikAhmadUllah`.

**Owner:** Malik Ahmad Ullah — Machine Learning Engineer, Data Scientist and Researcher
**Affiliation:** Research Assistant, Department of Electrical Engineering, Qatar University, Doha, Qatar
**Research focus:** Machine learning and signal processing on time-series and image data (healthcare, robotics, computer vision)

## Repository Structure

```
MalikAhmadUllah/
└── README.md       # GitHub profile page content — the only content file
```

There is no source code, build system, test suite, or package manifest. This is a documentation-only repository.

## File Conventions

### README.md

- This is the sole content file and the one users will primarily want to update.
- It uses standard **GitHub Flavored Markdown (GFM)**.
- The current style uses bullet points with emoji prefixes (`👋`, `👀`, `🌱`, `💞️`, `📫`) for each section — preserve this pattern when adding new sections.
- The HTML comment block (`<!--- ... --->`) at the bottom is a GitHub-generated reminder and should not be removed.
- Keep the tone professional yet approachable; this is a public-facing profile page.

### Known Typos in Current README (as of Feb 2026)

The README contains minor spelling errors that may be worth correcting:
- Line 3: `"Asistant"` → `"Assistant"`
- Line 3: `"Departement"` → `"Department"`

Fix these if making other edits to the file.

## Development Workflow

### Making Changes

1. Edit `README.md` directly — it is the only file that affects the rendered profile.
2. Preview changes using the GitHub web interface "Preview" tab before committing, or use a local Markdown renderer.
3. Commit with a descriptive message (e.g., `Update README: add publications section`).
4. Push to the `master` or `main` branch for changes to appear on the live profile.

### Branch Strategy

- **`master` / `main`**: Live branch — content here renders on the GitHub profile.
- **`claude/*`**: Feature branches used by Claude Code for staged changes before merging.

### Git Commands

```bash
# Stage and commit README changes
git add README.md
git commit -m "Update README: <brief description of change>"

# Push to live profile branch
git push origin master

# Push a Claude feature branch
git push -u origin claude/<branch-name>
```

## Content Guidelines for AI Assistants

When updating the profile README, follow these principles:

1. **Accuracy first** — Only include information that is factually correct about the owner. Do not invent credentials, publications, or affiliations.
2. **Preserve existing voice** — The profile has a concise, bullet-point style. Maintain this format unless explicitly asked to change it.
3. **Keep it current** — Update roles, affiliations, and interests to reflect what the owner provides; do not assume details not given.
4. **Contact links** — The LinkedIn URL and email address are personal data. Update only when the owner provides new values.
5. **No code execution** — There is nothing to build, test, or lint in this repository.

## Common Tasks

| Task | What to do |
|------|------------|
| Update current role/affiliation | Edit the `🌱 I'm currently working as...` bullet in README.md |
| Add a new interest area | Add a bullet under the `👀` interests section |
| Update contact information | Edit the `📫` bullet with the new LinkedIn/email |
| Add skills or tech stack | Append a new bullet or section to README.md |
| Add badges/shields | Insert Markdown image links from [shields.io](https://shields.io) |
| Add GitHub stats widgets | Use GitHub readme stats snippets (image embeds) |

## No Build or Test Commands

This repository has no:
- Package manager (`npm`, `pip`, `cargo`, etc.)
- Build step
- Test suite
- Linter or formatter configuration
- CI/CD pipeline

There is nothing to install or run locally beyond a Markdown previewer.
