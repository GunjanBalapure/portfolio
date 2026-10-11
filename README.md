# Gunjan Balapure — Personal Portfolio

A clean, responsive personal portfolio website built with **100% pure HTML and CSS** (no JavaScript, no React, no Vite, no dependencies), recreating the exact scrapbook/editorial design from your mockup sheets:

- **Blue graph paper background** (`22px × 22px` blueprint grid pattern)
- **White top navigation bar** (`GB.` monogram and uppercase navigation links)
- **Hero card** in warm cream (`#fffaf0`) with editorial serif typography and royal blue accents
- **Authentic portrait photo card** ([`profile.jpg`](profile.jpg)) with clean border frame and `GUNJAN BALAPURE` caption
- **Section 01 / A LITTLE ABOUT ME**: Academic & engineering focus card
- **Section 02 / TOOLBOX**: 2×2 colored cards in cream, pastel yellow (`#ffe27a`), pastel pink (`#fbcfe8`), and cream
- **Section 03 / SELECTED WORK**: 6 projects in a 2-column grid with color-coded cards (VisualMath, Sahayak AI, HajAIri, MoodMate, Fake News Detector, CarboNIL)
- **Section 04 / EXPERIENCE & LEARNING**: HP – CII – IndiaAI, Lenovo LEAP, and Cisco Networking Academy
- **Section 05 / THE CREATIVE SIDE**: Music, songwriting, singing, and visual storytelling
- **Section 06 / SAY HELLO**: Striking deep navy card (`#1c2f6b`) with gold label and direct contact links (`GitHub ↗`, `LinkedIn ↗`, `Instagram ↗`, `Mail ↗`)

---

## 🖥️ Previewing the Website Locally

### Method 1: Local Dev Server (Running Now)
Your local development server is active at:
👉 **[http://localhost:3000](http://localhost:3000)**

You can also start it anytime from your terminal by running:
```bash
npm run dev
```

### Method 2: Direct File Open
Double-click [**`index.html`**](index.html) in Windows File Explorer to open it directly in Chrome, Edge, or any browser.

---

## ✏️ Customizing Links

1. **Project Links**: Open `index.html` and search for `<a href="#" class="project-card`. Replace `href="#"` with your repository or live demo links.
2. **Social Media Links**: In the `06 / SAY HELLO` section of `index.html`, update the `href` values for GitHub, LinkedIn, and Instagram. The `Mail` link is already pre-configured to open `mailto:gunjanbalapure04@gmail.com`.

---

## 🚀 How to Publish Online for Free

### Option 1: GitHub Pages
1. Create a new repository on [GitHub](https://github.com/new) named `portfolio`.
2. Push your code:
   ```bash
   git init
   git add .
   git commit -m "Scrapbook portfolio for Gunjan Balapure"
   git branch -M main
   git remote add origin https://github.com/<your-username>/portfolio.git
   git push -u origin main
   ```
3. Go to **Settings** → **Pages** → under **Branch**, choose `main` and `/ (root)` → click **Save**.
4. Your site will be live at `https://<your-username>.github.io/portfolio/`.

### Option 2: Netlify (Drag & Drop)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag and drop this folder (`e:\portfolio only html css`).
3. It will deploy instantly and give you a live shareable URL!
