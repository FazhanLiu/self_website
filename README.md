# Self Website

A clean, high-end personal website template for introducing background, skills, projects, experience, and contact information.

Live site: https://fazhanliu.github.io/self_website/

## Features

- Minimal portfolio-style layout
- Responsive design for desktop and mobile
- Soft neutral color palette with restrained accent colors
- Sections for profile, skills, projects, timeline, and contact
- Lightweight static implementation with HTML, CSS, and JavaScript
- GitHub Pages deployment through GitHub Actions

## Project Structure

```text
.
├── self_website/
│   ├── index.html
│   ├── styles.css
│   └── script.js
└── .github/workflows/pages.yml
```

## Local Preview

Run a static server from the site directory:

```bash
cd self_website
python3 -m http.server 5173
```

Then open:

```text
http://localhost:5173
```

## Deployment

This repository deploys automatically to GitHub Pages when changes are pushed to the `main` branch.

The Pages workflow uploads the `self_website/` folder as the static site artifact, so the published site is available at:

```text
https://fazhanliu.github.io/self_website/
```

If the site does not appear immediately, check the repository's **Actions** tab and **Settings > Pages**. The first deployment can take a minute or two.

## Customization

Edit `self_website/index.html` to replace placeholder profile content such as name, role, location, project descriptions, and email address. Edit `self_website/styles.css` to adjust the visual identity.
