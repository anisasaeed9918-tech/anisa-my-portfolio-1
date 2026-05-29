# Anisa Saeed – Data Analyst Portfolio

A modern, responsive personal portfolio website built with pure HTML, CSS, and JavaScript.

## 🗂 File Structure

```
anisa-portfolio/
├── index.html
├── Anisa_CV.pdf          ← Place your CV PDF here
├── README.md
├── assets/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── main.js
```

## 📋 Setup Instructions

### 1. Add Your CV
Place your CV file named exactly `Anisa_CV.pdf` in the **root folder** (same level as `index.html`).

### 2. Add Certificates (Optional)
Place certificate PDFs in the root folder:
- `canva-cert.pdf`
- `ai-image-cert.pdf`
- `video-editing-cert.pdf`

Then update the `onclick` handlers in `index.html` to `window.open('canva-cert.pdf')` etc.

---

## 🖥 Run Locally

No build tools needed. Just open in a browser:

**Option A – Double click:**
Open `index.html` directly in any browser.

**Option B – VS Code Live Server:**
1. Install the "Live Server" extension in VS Code
2. Right-click `index.html` → **Open with Live Server**

**Option C – Python HTTP server:**
```bash
cd anisa-portfolio
python -m http.server 8000
# Visit: http://localhost:8000
```

---

## 🚀 Deploy on GitHub Pages

### Step 1 – Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **New repository**
3. Name it: `anisa-portfolio` (or `your-username.github.io` for root deployment)
4. Set to **Public**
5. Click **Create repository**

### Step 2 – Upload Files
**Option A – GitHub Web UI:**
1. In your new repo, click **Add file → Upload files**
2. Drag all files/folders from `anisa-portfolio/`
3. Commit changes

**Option B – Git CLI:**
```bash
cd anisa-portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/anisa-portfolio.git
git push -u origin main
```

### Step 3 – Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select `main` branch and `/ (root)` folder
3. Click **Save**
4. Your site will be live at:
   `https://YOUR_USERNAME.github.io/anisa-portfolio/`

(It may take 1–2 minutes to go live.)

---

## ✏️ Customization

| What to change | Where |
|---|---|
| Name / Title / Bio | `index.html` – Hero & About sections |
| Skills percentages | `index.html` – `data-w` attributes |
| Project links | `index.html` – `<a href="">` in Projects section |
| Contact info | `index.html` – Contact section |
| Colors | `assets/css/style.css` – `:root` CSS variables |
| Fonts | `index.html` – Google Fonts `<link>` |

---

## 🎨 Color Palette

| Variable | Value | Usage |
|---|---|---|
| `--accent` | `#1a5276` | Primary – Navy blue |
| `--accent-2` | `#2e86c1` | Secondary – Medium blue |
| `--gold` | `#c9a84c` | Accent – Gold |
| `--bg` | `#f8f7f4` | Background |
| `--text` | `#1c1c1e` | Body text |

---

## 📱 Browser Support
Chrome, Firefox, Safari, Edge – all modern browsers. Fully mobile responsive.

---

© 2024 Anisa Saeed. All rights reserved.
