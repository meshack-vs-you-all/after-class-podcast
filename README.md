# The After Class Podcast Website

Loud, Clear, and Real. The premier podcast for raw student conversations that happen when the lecture ends.

This website is a high-performance, dark-themed platform built with **Hugo** and the **Paige** theme to showcase podcast episodes, manage partner promotions, and engage with the student community.

## 🚀 Features

- **Automated Episode Management**: Synced directly from YouTube data.
- **Monetization Ready**: Integrated "Support the Show" sections and Partner Promotion blocks.
- **SEO Optimized**: Meta descriptions, thumbnails, and tags generated for every episode.
- **CI/CD**: Automatic deployment to GitHub Pages via GitHub Actions.
- **Glassmorphism Design**: Modern, premium dark aesthetic.

## 🛠️ Development

### Prerequisites
- Hugo Extended version
- Dart Sass

### Local Preview
To run the site locally:
```bash
hugo server -D
```
The site will be available at `http://localhost:1313`.

## 📦 Data Sync
The episode data is managed via a Python script that parses `afterclass_videos.csv` and generates the corresponding Hugo content files.

## 🚀 Deployment
This site is configured for **GitHub Pages**. 
1. Push changes to the `main` branch.
2. GitHub Actions will automatically build and deploy the site.
3. Ensure that in Repository Settings > Pages, the Source is set to **GitHub Actions**.

## 🤝 Partner with Us
Interested in reaching our audience? Contact us at [sponsor@theafterclass.com](mailto:sponsor@theafterclass.com).
