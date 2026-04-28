# CLAUDE.md — Dr Kelvin Ng's Personal Brand Website

## Project Overview
This is the personal brand website for Dr. Kelvin Ng (drkelvinng.com), a Doctor of Chiropractic based in Singapore. The site covers his clinical work, blog, and corporate wellness services.

## Tech Stack
- Framework: Plain HTML + CSS + JavaScript (no build tools or npm required)
- Version Control: GitHub (repo: https://github.com/saykoon88/Kelvin)
- Hosting: Cloudflare Pages (deployed via GitHub Actions + wrangler.toml)

## Project Structure
- index.html — Main website homepage
- blog/ — Blog section and articles
- images/ — All image assets
- css/ — Stylesheets
- js/ — JavaScript files
- _headers — Cloudflare cache headers
- wrangler.toml — Cloudflare Pages deployment config

## Deployment Workflow
1. Make changes to files locally
2. Commit and push to GitHub main branch
3. GitHub Actions automatically deploys to Cloudflare Pages
4. Site goes live at drkelvinng.com

## How to Add Images
- Place image files in the /images/ folder
- Reference them in HTML as <img src="images/filename.jpg" alt="description">
- Always include descriptive alt text
- Compress images before uploading

## How to Add Blog Posts
- Blog files live in the /blog/ folder
- Follow existing article structure and naming convention
- Link new posts from the main blog index

## Important Rules
- Always git pull before making changes
- Commit with clear descriptive messages
- Never edit wrangler.toml unless changing Cloudflare config
- Do not add node_modules or .wrangler folders

## Owner
Dr. Kelvin Ng — Family Health Chiropractic Clinic, Singapore
GitHub: saykoon88
