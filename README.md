# 🌌 Cyberpunk Portfolio Template

A super-cool, dark-themed personal portfolio template for developers. Designed for those who navigate the fine line between the digital frontier and the dark night.

[![GitHub stars](https://img.shields.io/github/stars/lenmei233/cyberpunk-portfolio-template.svg?style=social&label=Star)](https://github.com/YOUR_USERNAME/REPO_NAME)
[![GitHub forks](https://img.shields.io/github/forks/lenmei233/cyberpunk-portfolio-template.svg?style=social&label=Fork)](https://github.com/YOUR_USERNAME/REPO_NAME)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**[中文版 README](README.zh-CN.md)** | Report Bug · Request Feature

![Preview Screenshot](https://github.com/user-attachments/assets/16ee1901-9976-4ada-82d0-dc32693ce51e)

## ✨ Features

-   **🎨 Cyberpunk Aesthetics**: Deep dark backgrounds paired with neon colors for an immersive tech vibe.
-   **🎬 Dynamic Visual Effects**: Stunning Glitch art title, Matrix-style digital rain background, and hover-scan animations.
-   **📱 Fully Responsive**: Looks perfect on desktops, tablets, and mobile devices.
-   **⚡ Zero Dependencies**: Built with pure HTML, CSS, and JavaScript. No frameworks, no bloat, just speed.
-   **🧩 Highly Customizable**: Easily change colors, fonts, and more using simple CSS variables.

## 🚀 Quick Start

Get your own dark-themed homepage up and running in just a few steps.

### Online Deployment (Recommended)

The easiest way is to deploy it to a free static hosting service like Vercel, Netlify, or GitHub Pages.

1.  **Fork this repository**.
2.  Go to your forked repository's settings, enable GitHub Pages, and select the `main` branch.
3.  Visit `https://YOUR_USERNAME.github.io/REPO_NAME` to see your site.

**For Vercel / Netlify:**
Click the button below, authorize your GitHub account, and you're good to go.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/lenmei233/cyberpunk-portfolio-template)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/lenmei233/cyberpunk-portfolio-template)


### Local Development

If you want to preview and customize locally:

1.  **Clone the repository**
    ```bash
    git clone https://github.com/lenmei233/cyberpunk-portfolio-template.git
    cd REPO_NAME
    ```

2.  **Start a local server**
    You'll need a simple static server. If you have Python installed, run:
    ```bash
    # Python 3
    python -m http.server
    ```
    Or, if you have Node.js, you can use `npx serve`:
    ```bash
    npx serve
    ```

3.  **Open in browser**
    Navigate to `http://localhost:8000`.

## 🛠️ Customization Guide

This template is designed to be easy to customize. Just edit the `index.html` file.

### Editing Personal Info & Projects

Open `index.html`:

-   **Title & Subtitle**: Find the `<header>` tag and modify the content of `.glitch-title` and `.subtitle`.
-   **Project Cards**: Inside the `<main>` tag, you'll find multiple `<article class="project-card">` elements. Copy, delete, or modify these to showcase your own work.
    ```html
    <!-- Example Project Card -->
    <article class="project-card">
        <div class="project-header">
            <h3 class="project-name">Your Project Name</h3>
            <span class="project-type">[Project Type]</span>
        </div>
        <div class="project-body">
            <p>Write a brief description of your project here...</p>
            <div class="tech-stack">
                <!-- Add your tech stack tags -->
                <span class="tech-tag">Rust</span>
                <span class="tech-tag">WebGPU</span>
            </div>
            <!-- Status can be active, deprecated, or dead -->
            <p class="status active">◆ Status: Active Development</p>
        </div>
        <div class="project-footer">
            <!-- Update your links -->
            <a href="YOUR_GITHUB_REPO_LINK" class="project-link">View Source &gt;</a>
            <a href="YOUR_PROJECT_DEMO_LINK" class="project-link">Live Demo &gt;</a>
        </div>
    </article>
    ```

### Changing Theme Colors

In `index.html`, at the top of the `<style>` tag, you'll find the `:root` block. You can easily modify these color variables to change the entire color scheme.

```css
:root {
    --bg-color: #0a0a0a;            /* Main background */
    --surface-color: #111;          /* Card background */
    --primary-color: #00ffff;       /* Primary accent (Cyan) */
    --accent-color: #ff00ff;        /* Secondary accent (Magenta) */
    --danger-color: #ff0040;        /* Danger/Warning color */
    --text-color: #e0e0e0;          /* Main text color */
    --muted-text-color: #888;       /* Secondary text color */
}
```
## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

     Fork the Project.
     Create your Feature Branch (git checkout -b feature/AmazingFeature).
     Commit your Changes (git commit -m 'Add some AmazingFeature').
     Push to the Branch (git push origin feature/AmazingFeature).
     Open a Pull Request.

## 📜 License

Distributed under the MIT License. See LICENSE for more information.
## 🙏 Acknowledgments

    Inspiration from all cyberpunk culture and minimalist design.
    The Matrix background effect is a classic frontend exercise.
    Thanks to Orbitron and Noto Sans SC for the awesome fonts.

 
 
