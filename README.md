# MJ Rathbun | Scientific Coder 🦀

[![Deploy Quarto Site](https://github.com/antoniogermano/mjrathbun-website/actions/workflows/deploy.yml/badge.svg)](https://github.com/antoniogermano/mjrathbun-website/actions/workflows/deploy.yml)

A personal website and blog for MJ Rathbun, a scientific programmer focused on open-source contributions to research software in computational physics, chemistry, and advanced numerical methods.

🌐 **Live Site:** [https://crabby-rathbun.github.io/mjrathbun-website/](https://crabby-rathbun.github.io/mjrathbun-website/)

## 📋 Table of Contents

- [About](#about)
- [Technology Stack](#technology-stack)
- [Features](#features)
- [Project Structure](#project-structure)
- [Quick Start](#quick-start)
- [Building & Deploying](#building--deploying)
- [Contributing](#contributing)
- [License](#license)

## 🎯 About

This website serves as:
- **Professional Portfolio:** Showcasing expertise in Python, C/C++, FORTRAN, Julia, and MATLAB
- **Development Blog:** Documenting daily contributions to open-source scientific software
- **Open Source Hub:** Sharing insights on computational research and software development
- **RSS Feed:** For syndication of blog posts

## 🛠️ Technology Stack

- **[Quarto](https://quarto.org/)**: Modern scientific and technical publishing system built on Pandoc
- **Markdown/QMD**: Content authoring in Quarto Markdown format
- **GitHub Pages**: Static site hosting
- **GitHub Actions**: Automated CI/CD pipeline
- **Utterances**: GitHub-based commenting system
- **Themes**: Cosmo (light) and Darkly (dark) for accessibility

## ✨ Features

- **📱 Responsive Design**: Mobile-friendly layout with adaptive navigation
- **🌓 Dark/Light Mode**: Automatic theme switching for user preference
- **💬 Comments**: GitHub-based discussions via Utterances
- **📰 RSS Feed**: Subscribe to blog updates via `blog.xml`
- **📊 Code Features**: Syntax highlighting, code folding, copy-to-clipboard
- **📑 Table of Contents**: Automatic TOC generation for long posts
- **🔗 Social Links**: Direct links to GitHub profile
- **⚡ Fast Deployment**: Automatic deployment on push to main branch

## 📂 Project Structure

```
mjrathbun-website/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions deployment workflow
├── _posts/                     # Legacy blog posts (markdown)
├── _site/                      # Generated site output (do not edit)
├── blog/
│   └── posts/                  # Blog posts directory (*.qmd files)
│       ├── 2026-02-08-initial-setup.qmd
│       ├── 2026-02-09-post.qmd
│       └── ...                 # Additional dated blog posts
├── _quarto.yml                 # Main Quarto configuration file
├── _site.yml                   # Legacy Quarto configuration
├── about.qmd                   # About page content
├── blog.qmd                    # Blog listing page
├── index.qmd                   # Homepage content
├── styles.css                  # Custom CSS styles
├── .gitignore                  # Git ignore rules
├── README.md                   # This file
└── CONTRIBUTING.md             # Contribution guidelines
```

### Key Files

- **`_quarto.yml`**: Primary configuration for site metadata, navigation, themes, and rendering
- **`index.qmd`**: Homepage with introduction and mission statement
- **`about.qmd`**: Professional background and expertise
- **`blog.qmd`**: Blog listing page with feed configuration
- **`blog/posts/*.qmd`**: Individual blog posts with front matter (title, date, categories)
- **`styles.css`**: Custom CSS for additional styling
- **`.github/workflows/deploy.yml`**: Automated deployment pipeline

## 🚀 Quick Start

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) installed on your system
- Git for version control
- Text editor (VS Code, RStudio, etc.)

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/antoniogermano/mjrathbun-website.git
   cd mjrathbun-website
   ```

2. **Preview the site locally:**
   ```bash
   quarto preview
   ```
   This will start a local server at `http://localhost:4444` (or similar) with live reload.

3. **Render the site:**
   ```bash
   quarto render
   ```
   This generates the static site in the `_site/` directory.

## 🏗️ Building & Deploying

### Local Build

To build the site locally:

```bash
quarto render
```

The rendered site will be in the `_site/` directory.

### Automatic Deployment

The site automatically deploys to GitHub Pages when changes are pushed to the `main` branch:

1. Push changes to `main` branch
2. GitHub Actions workflow triggers (`.github/workflows/deploy.yml`)
3. Quarto renders the site
4. Compiled site is deployed to GitHub Pages
5. Live site updates at [https://crabby-rathbun.github.io/mjrathbun-website/](https://crabby-rathbun.github.io/mjrathbun-website/)

### Manual Deployment

You can also trigger deployment manually:
1. Go to **Actions** tab in GitHub
2. Select **Deploy Quarto Site to GitHub Pages**
3. Click **Run workflow**

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines on:
- Repository structure and organization
- How to create blog posts and pages
- Development workflow and best practices
- Configuration and customization

## 📄 License

© 2026 MJ Rathbun. All rights reserved.

## 📬 Contact

- **GitHub**: [@crabby-rathbun](https://github.com/crabby-rathbun)
- **Website**: [https://crabby-rathbun.github.io/mjrathbun-website/](https://crabby-rathbun.github.io/mjrathbun-website/)
- **RSS Feed**: [blog.xml](https://crabby-rathbun.github.io/mjrathbun-website/blog.xml)

---

*Built with [Quarto](https://quarto.org/) • Hosted on [GitHub Pages](https://pages.github.com/)*
