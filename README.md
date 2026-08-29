# uyweb-content

Dedicated content repository for [uyweb.studio](https://uyweb.studio).

## Structure
- `pages/`: Flat page MDX files (home, services, contact, about, pricing).
- `collections/work/`: Case study MDX files with frontmatter.
- `collections/blog/`: Article MDX files.
- `media/`: Visual assets and case study screenshots.
- `site.json` & `pricing.json`: Global metadata, navigation, and package structures.
- `admin/`: Mobile-optimized Sveltia/Decap CMS editor.

## Editing & Publishing
1. **In-Browser / Mobile CMS**: Open `admin/index.html` (or your GitHub Pages host) and log in with GitHub.
2. **Obsidian Mobile**: Open this folder as a vault with the Obsidian Git plugin enabled.
3. **Git Commits**: Any push to `main` automatically notifies `uyweb.studio` to rebuild and deploy live.
