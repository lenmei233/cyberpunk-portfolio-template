
---

### Second: Chinese (README.zh-CN.md)

```markdown
# 🌌 Cyberpunk 作品集模板

一个超级炫酷的暗黑系个人开发者作品集展示页面模板。专为那些游走于代码与暗夜之间的开发者而设计。

[![GitHub stars](https://img.shields.io/github/stars/lenmei233/cyberpunk-portfolio-template.svg?style=social&label=Star)](https://github.com/YOUR_USERNAME/REPO_NAME)
[![GitHub forks](https://img.shields.io/github/forks/lenmei233/cyberpunk-portfolio-template.svg?style=social&label=Fork)](https://github.com/YOUR_USERNAME/REPO_NAME)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**[English README](README.md)** | 提交问题 · 功能建议

![预览图](https://github.com/user-attachments/assets/16ee1901-9976-4ada-82d0-dc32693ce51e)

## ✨ 特性

-   **🎨 暗黑赛博朋克美学**: 深邃的背景搭配霓虹色彩，营造沉浸式科技感。
-   **🎬 动态视觉效果**: 炫酷的 Glitch 故障艺术标题、Matrix 数字雨背景、悬停光扫动画。
-   **📱 响应式设计**: 完美适配桌面端、平板和移动设备。
-   **⚡ 零依赖**: 不依赖任何前端框架，纯 HTML, CSS, 和 JavaScript 实现，加载飞快。
-   **🧩 高度可定制**: 使用 CSS 变量轻松调整主题色彩、字体等。

## 🚀 快速开始

只需几步，即可拥有你自己的暗黑系主页。

### 在线部署（推荐）

最简单的方式是直接部署到免费的静态托管平台，如 Vercel, Netlify, 或 GitHub Pages。

1.  **Fork 本仓库**。
2.  进入你 Fork 后的仓库设置，开启 GitHub Pages 功能，并选择 `main` 分支。
3.  访问 `https://你的用户名.github.io/你的仓库名` 即可查看你的网站。

**对于 Vercel/Netlify**:
点击上方按钮，授权你的 GitHub 账号，即可一键部署。

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/lenmei233/cyberpunk-portfolio-template)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/lenmei233/cyberpunk-portfolio-template)


### 本地运行

如果你想先在本地预览和修改：

1.  **克隆仓库**
    ```bash
    git clone https://github.com/lenmei233/cyberpunk-portfolio-template.git
    cd REPO_NAME
    ```

2.  **启动本地服务器**
    你需要一个简单的静态服务器。如果安装了 Python，可以运行：
    ```bash
    # Python 3
    python -m http.server
    ```
    或者，如果你安装了 Node.js，可以使用 `npx serve`：
    ```bash
    npx serve
    ```

3.  **访问**
    在浏览器中打开 `http://localhost:8000`。

## 🛠️ 自定义指南

这个模板的核心优势在于易于定制。只需修改 `index.html` 文件即可。

### 修改个人信息和项目

打开 `index.html` 文件：

-   **标题和副标题**: 找到 `<header>` 标签，修改 `.glitch-title` 和 `.subtitle` 的内容。
-   **项目列表**: 在 `<main>` 标签内，你会找到多个 `<article class="project-card">`。复制、删除或修改这些卡片来展示你自己的项目。
    ```html
    <!-- 这是一个项目卡片示例 -->
    <article class="project-card">
        <div class="project-header">
            <h3 class="project-name">你的项目名</h3>
            <span class="project-type">[项目类型]</span>
        </div>
        <div class="project-body">
            <p>在这里写你的项目简介...</p>
            <div class="tech-stack">
                <!-- 添加你的技术栈标签 -->
                <span class="tech-tag">Rust</span>
                <span class="tech-tag">WebGPU</span>
            </div>
            <!-- 状态可以是 active, deprecated, dead -->
            <p class="status active">◆ 状态: 活跃开发中</p>
        </div>
        <div class="project-footer">
            <!-- 修改链接 -->
            <a href="你的GitHub仓库链接" class="project-link">查看源码 &gt;</a>
            <a href="你的项目在线地址" class="project-link">在线Demo &gt;</a>
        </div>
    </article>
    ```

### 修改主题颜色

打开 `index.html` 文件，在 `<style>` 标签的顶部，你会找到 `:root` 块。你可以轻松修改这里的颜色变量来改变整个网站的配色方案。

```css
:root {
    --bg-color: #0a0a0a;            /* 背景色 */
    --surface-color: #111;          /* 卡片背景色 */
    --primary-color: #00ffff;       /* 主要高亮色（青色） */
    --accent-color: #ff00ff;        /* 次要高亮色（品红） */
    --danger-color: #ff0040;        /* 危险/警告色 */
    --text-color: #e0e0e0;          /* 主文本色 */
    --muted-text-color: #888;       /* 辅助文本色 */
}
```
## 🤝 贡献

开源社区之所以伟大，是因为它是一个学习、启发和创造的绝佳之地。你的任何贡献都将被高度重视。

如果你有能让这个项目变得更好的建议，请 Fork 此仓库并创建一个 Pull Request。你也可以直接使用 "enhancement" 标签提交一个 Issue。别忘了给项目点个 Star！再次感谢！

     Fork 本仓库。
     创建你的特性分支 (git checkout -b feature/AmazingFeature)。
     提交你的更改 (git commit -m 'Add some AmazingFeature')。
     推送到分支 (git push origin feature/AmazingFeature)。
     打开一个 Pull Request。

## 📜 许可证

本项目采用 MIT 许可证 - 查看 LICENSE 文件了解详情。
## 🙏 致谢

    灵感来源于所有赛博朋克文化和极简主义设计。
    Matrix 背景效果是经典的前端练习项目。
    感谢 Orbitron 和 Noto Sans SC 提供的优秀字体。
