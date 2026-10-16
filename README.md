# Vidushi Vinod - Personal Portfolio Website 🚀

Welcome to the repository for my personal developer portfolio and website, hosted with GitHub Pages at **[VidushiVinod25.github.io](https://VidushiVinod25.github.io)**!

Built with pure, modern HTML5, CSS3, and JavaScript — no heavy build steps, lightning-fast load times, and 100% responsive across desktop, tablet, and mobile devices.

---

## ✨ Features

- **🎨 Modern Dark & Light Mode**: Built-in dynamic theme toggling with preference persistence (`localStorage` & system preferences).
- **⚡ Animated Hero Section**: Dynamic typewriter text effect highlighting engineering roles, CTA buttons, and status indicator.
- **📂 Filterable Projects Showcase**: Category filters (Full Stack, AI/Data, Web Apps) with live interactive filtering.
- **🗺️ Interactive Milestones**: Vertical timeline highlighting experience, open-source work, and education.
- **🛠️ Categorized Skills Matrix**: Pill badges for languages, frontend, backend/cloud, and dev tools.
- **📬 Interactive Contact Section**: Contact channels and form with immediate user feedback (toast alerts).
- **📱 Fully Responsive**: Custom mobile navigation drawer, fluid typography, and glassmorphic UI elements.
- **🌐 GitHub Pages Ready**: Zero build configuration needed. Ready to deploy right out of the box.

---

## 📁 Project Structure

```text
VidushiVinod25.github.io/
├── index.html          # Main HTML structure & semantic sections
├── css/
│   └── style.css       # Design tokens, variables, dark/light themes, animations
├── js/
│   └── main.js         # Theme switch, typewriter effect, filter logic, contact toast
├── assets/
│   ├── avatar.svg      # Hero illustration graphic
│   └── favicon.svg     # Website favicon
└── README.md           # Documentation and setup guide
```

---

## 💻 How to Preview Locally

You can test and view the website locally in your browser using any of the following methods:

### Option 1: Direct Browser
Simply double-click `index.html` to open it in your browser of choice (Chrome, Edge, Firefox, Safari).

### Option 2: Python HTTP Server (Recommended)
Open your terminal in this repository folder and run:

```bash
# Python 3
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000) in your browser.

---

## 🚀 Publishing to GitHub Pages

Because this repository is named `VidushiVinod25.github.io`, GitHub will automatically publish it to `https://VidushiVinod25.github.io` when pushed to the default branch!

To publish:

1. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Initialize personal portfolio website"
   git push origin main
   ```

2. Go to your repository settings on GitHub:
   - Navigate to **Settings** > **Pages**
   - Under **Build and deployment** > **Source**, verify it is set to **Deploy from a branch**
   - Branch: `main` / `/(root)`
   - Click **Save**

3. Your website will be live in a couple of minutes at:
   **https://VidushiVinod25.github.io**

---

## 🛠️ Customization Guide

- **Personal Info & Bio**: Update `index.html` with your actual bio, links, and contact email.
- **Projects**: Replace dummy project descriptions, tech tags, and links in the `<section id="projects">` block.
- **Resume**: Place your `resume.pdf` in the `assets/` folder and link to it in `index.html`.
- **Colors & Themes**: Modify CSS variables inside `:root` in `css/style.css` to change primary colors, gradients, and font families.

---

Crafted with ❤️ by **Vidushi Vinod**.
