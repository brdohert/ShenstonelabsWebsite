# Shenstone Labs Website

The static website for **Shenstone Labs**, hosted on [Cloudflare Pages](https://pages.cloudflare.com/).

🌐 **Staging:** [test.shenstonefarm.net](https://test.shenstonefarm.net)

## 🧩 Overview

A lightweight, dependency-free static site (HTML + CSS) styled to match the
Shenstone Labs gold-and-black tech branding. No build step is required — the
files are served exactly as they are in this repository.

## 📁 Project Structure

```
ShenstonelabsWebsite/
├── index.html          # Landing page
├── css/
│   └── styles.css      # Site styles
├── img/
│   └── Shenstonelabs-Logo.png
├── LICENSE
└── README.md
```

## 🚀 Deployment

This repository is connected to **Cloudflare Pages**. Every push to the `main`
branch triggers an automatic deployment.

- **Build command:** _(none — static site)_
- **Build output directory:** `/` (repository root)

### Custom domain

The staging site is served at `test.shenstonefarm.net` via a Cloudflare Pages
custom domain (CNAME managed in Cloudflare DNS).

## 🛠️ Local Development

No tooling required. Open `index.html` directly in a browser, or serve the
folder with any static file server:

```bash
# Python 3
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file
for details.
