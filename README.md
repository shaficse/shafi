# Md Shafi Ud Doula — Personal Website

A modern, responsive personal portfolio website built with pure HTML, CSS, and JavaScript. Designed for hosting on **GitHub Pages**.

## 🌐 Live Site

Visit: [https://mdshafiudoula.github.io/git-personal-web-site/](https://mdshafiudoula.github.io/git-personal-web-site/)

## ✨ Features

- **Responsive Design** — Works on all devices (mobile, tablet, desktop)
- **Animated Hero Section** — Particle effects and gradient animations
- **Interactive Timeline** — Work experience presented chronologically
- **Filterable Project Gallery** — Filter by category (GenAI, NLP, CV, ML, Cloud)
- **Publications Section** — Academic papers and conference presentations
- **Skills Visualization** — Interactive skill tags and language proficiency bars
- **Scroll Animations** — Smooth fade-in effects as you scroll
- **No Build Tools Required** — Pure HTML/CSS/JS, ready for GitHub Pages

## 🚀 Deployment on GitHub Pages

1. Create a new repository on GitHub (e.g., `git-personal-web-site` or `mdshafiudoula.github.io`)
2. Push this code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit - personal website"
   git branch -M main
   git remote add origin https://github.com/mdshafiudoula/git-personal-web-site.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your GitHub repository
4. Under **Source**, select `main` branch and `/ (root)` folder
5. Click **Save** — your site will be live in a few minutes!

## 📁 File Structure

```
├── index.html      # Main HTML file
├── style.css       # All styles
├── script.js       # Interactivity (particles, filters, animations)
├── README.md       # This file
└── .nojekyll       # Tells GitHub Pages not to process with Jekyll
```

## 🎨 Customization

- **Profile Photo**: Replace the brain icon in the hero section with an `<img>` tag pointing to your photo
- **GitHub Links**: Update repository URLs in `index.html` to match your actual GitHub username
- **Social Links**: Update ORCID, LinkedIn, and GitHub profile URLs
- **Colors**: Modify CSS variables in `:root` at the top of `style.css`

## 📄 License

© 2026 Md Shafi Ud Doula. All rights reserved.
