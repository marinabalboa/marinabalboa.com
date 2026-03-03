# Copilot Instructions for marinabalboa.com

## Project Overview
- This is a static website project. All content is served from HTML, images, and video files.
- No build tools, frameworks, or package managers are present. All files are edited directly.

## Directory Structure
- `index.html`: Main entry point for the site. All navigation and content start here.
- `images/`: Contains all site images. Use descriptive filenames and organize by topic if needed.
- `video/`: Contains all site videos. Use clear, topic-based filenames.
- `robots.txt`, `sitemap.xml`: Standard SEO files. Update as needed for search engine visibility.

## Editing & Workflow
- Edit HTML directly. No templating or preprocessing is used.
- Add new content by creating new HTML files and linking them from `index.html`.
- Place new media in `images/` or `video/` and reference them with relative paths.
- No automated build, test, or deployment scripts. Manual updates only.

## Conventions
- Use semantic HTML tags for accessibility and SEO.
- Keep filenames lowercase and hyphenated (e.g., `about-me.html`, `profile-pic.jpg`).
- Link all new pages from `index.html` for discoverability.
- Organize media by topic if the collection grows.

## Integration Points
- No external dependencies or APIs are used.
- For SEO, update `robots.txt` and `sitemap.xml` as site structure changes.

## Example Patterns
- To add a new page:
  1. Create `new-page.html` in the root directory.
  2. Link it from `index.html`.
- To add an image:
  1. Place `topic-image.jpg` in `images/`.
  2. Reference it in HTML: `<img src="images/topic-image.jpg" alt="Description">`

## Key Files
- `index.html`: Main navigation and content hub.
- `images/`, `video/`: All media assets.
- `robots.txt`, `sitemap.xml`: SEO configuration.

---
For any unclear or missing conventions, ask the user for clarification before making structural changes.