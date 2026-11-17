# ourcrepe — Official Product Landing Page

[![ourcrepe](https://img.shields.io/badge/ecosystem-ourcrepe-3178c6?style=flat)](https://quickrunner.ourcrepe.live/)
[![QuickRunner](https://img.shields.io/badge/QuickRunner-Live-059669?style=flat&logo=visualstudiocode&logoColor=white)](https://quickrunner.ourcrepe.live/)
[![QuickEditor](https://img.shields.io/badge/QuickEditor-Upcoming%20AI-d97706?style=flat)](https://quickeditor.ourcrepe.live)
[![License: MIT](https://img.shields.io/badge/license-MIT-0f2744?style=flat)](https://opensource.org/licenses/MIT)
[![Supported Languages](https://img.shields.io/badge/languages-60%2B-4a90e2?style=flat)](https://quickrunner.ourcrepe.live/)

Minimalist, high-performance landing page for the **ourcrepe** developer tooling ecosystem, styled with the clean aesthetic, typography, and simplicity of [quickrunner.ourcrepe.live](https://quickrunner.ourcrepe.live/).

---

## Products & Ecosystem

| Product | Status | Primary URL | Description |
| :--- | :--- | :--- | :--- |
| **QuickRunner** | Live | [quickrunner.ourcrepe.live](https://quickrunner.ourcrepe.live/) | All-in-one code runner for VS Code & terminal. Execute files, selections, or custom commands across 60+ languages with zero setup. |
| **QuickEditor** | Upcoming (AI) | [quickeditor.ourcrepe.live](https://quickeditor.ourcrepe.live) | AI-powered code editor engineered for competitive coders (Codeforces, LeetCode, AtCoder) featuring automated stress-testing, algorithmic hints, and edge-case generation. |

---

## Theme & Design Details

- **Typography**: 
  - **Inter**: Modern UI sans-serif for body and navigation.
  - **JetBrains Mono**: Terminal code blocks, shortcuts, and domain badges.
  - **Pinyon Script**: Signature cursive accents (`"Simple, fast, developer-first"`).
- **Brand Assets**:
  - `images/logo.png`: High-resolution **ourcrepe** emblem, shaded with the theme's blue gradient.
  - `favicon.ico` & `images/logo.ico`: Multi-resolution icon resource (16x16, 32x32, 48x48, 64x64) for browser tabs and bookmarks.
- **Vector Icons (Font Awesome 6)**:
  - Vector icons used exclusively throughout the UI (theme toggles, external link indicators, feature grid, and card badges). Zero raw emojis.
- **Light & Dark Mode**:
  - Automatically respects system appearance (`prefers-color-scheme`).
  - Interactive theme toggle button in the navigation header with local storage persistence.
- **Interactive Elements**:
  - Infinite marquee ticker highlighting supported languages and competitive programming features.
  - Responsive layout optimized across mobile, tablet, and desktop viewports.
  - Zero build step / zero framework dependencies — pure HTML, CSS, and vanilla JS.

---

## Local Development & Preview

You can preview the site directly in any browser:

### Option 1: Local HTTP Server (Recommended)
Using Python (pre-installed on macOS/Linux):
```bash
python3 -m http.server 3000
```
Then open [http://localhost:3000](http://localhost:3000) in your browser.

Using Node / npx:
```bash
npx serve .
```

### Option 2: Direct File
Double-click `index.html` to open it directly in Chrome, Safari, or your preferred browser.

---

## Deployment

Since this is a lightweight static site, you can deploy it in seconds:

- **GitHub Pages**: Push to GitHub and enable Pages in `Settings > Pages > Branch: main`.
- **Vercel**: Run `npx vercel` or import the GitHub repository into [Vercel](https://vercel.com).
- **Netlify**: Drag and drop the folder into [Netlify Drop](https://app.netlify.com/drop) or deploy via Git.
- **Cloudflare Pages**: Connect your Git repository with build command left empty and output directory set to `/`.
