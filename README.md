# Likhon Dev Blog CMS

## 🚀 Project Overview
A modern, static blog CMS with multi-language support, built for GitHub Pages.

## 📂 Project Structure
```
likhon-dev.github.io/
│
├── .github/
│   └── workflows/
│       ├── deploy.yml
│       └── build.yml
│
├── assets/
│   ├── css/
│   │   ├── main.css
│   │   ├── fonts.css
│   │   └── responsive.css
│   │
│   ├── js/
│   │   ├── main.js
│   │   ├── cms.js
│   │   ├── seo.js
│   │   └── utils.js
│   │
│   └── fonts/
│       ├── bn/
│       └── en/
│
├── content/
│   ├── posts/
│   │   ├── 2024-01-first-post.md
│   │   └── 2024-02-tech-insights.md
│   │
│   ├── pages/
│   │   ├── about.md
│   │   └── contact.md
│   │
│   └── config.json
│
├── dist/
│   ├── index.html
│   └── assets/
│
├── src/
│   ├── templates/
│   │   ├── base.html
│   │   ├── blog-post.html
│   │   └── page.html
│
├── scripts/
│   ├── build.js
│   ├── deploy.js
│   └── sitemap.js
│
├── .gitignore
├── README.md
├── index.html
├── sitemap.xml
└── robots.txt
```

## 🛠 Setup Instructions
1. Clone the repository
2. Install dependencies: `npm install`
3. Run local development: `npm run dev`
4. Build for production: `npm run build`

## 🌐 Features
- Multi-language Support
- SEO Optimized
- Static Site Generation
- Responsive Design
- Performance Monitoring

## 📦 Technologies
- Tailwind CSS
- Alpine.js
- Marked.js
- Highlight.js

## 🚢 Deployment
Deployed automatically via GitHub Actions to GitHub Pages

## 📝 License
MIT License
```
