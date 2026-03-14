# Souranil Ghosh — Portfolio Website

A modern, interactive portfolio website for gaming & esports content writer Souranil Ghosh.

## 🗂️ Folder Structure

```
your-repo/
├── index.html          ← Main portfolio file
├── resume/
│   └── ATS_RESUME.pdf  ← PUT YOUR RESUME HERE (exact filename)
└── README.md
```

## 🚀 Deployment (GitHub Pages + Vercel)

### Step 1: GitHub Setup
1. Create a new GitHub repo (e.g. `souranil-portfolio`)
2. Upload `index.html` and your `resume/ATS_RESUME.pdf`
3. Go to **Settings → Pages**, set source to `main` branch / root

### Step 2: Vercel (Custom Domain)
1. Go to [vercel.com](https://vercel.com) and import your GitHub repo
2. Framework preset: **Other** (plain HTML, no build needed)
3. Deploy — Vercel auto-deploys on every GitHub push!

## 🔐 Admin Panel

The admin panel lets you add/manage writing samples without touching code.

**How to access:**
- Click the **footer copyright text 5 times quickly**
- A login modal will appear

**Default credentials:**
- Username: `admin`
- Password: `souranil2025`

⚠️ **Change the password!** Open `index.html`, find this line and update it:
```js
const ADMIN_PASS = 'souranil2025'; // CHANGE THIS!
```

**What admin can do:**
- Add new articles (title, publication, URL, category, date)
- Edit or delete custom articles
- Articles are saved in the browser's localStorage

## 📄 Resume

Place your resume PDF at exactly this path in your repo:
```
resume/ATS_RESUME.pdf
```
The "Resume" button in the nav and contact section will link to it automatically.

## ✏️ Customisation

### Change Default Articles
In `index.html`, find `const DEFAULT_ARTICLES = [...]` and update the array.

### Change Color Palette
Find `:root { ... }` in the CSS and update these variables:
```css
--cyan: #00e5cc;      /* Primary accent */
--magenta: #ff2d6b;   /* Secondary accent */
--amber: #ffb830;     /* Typewriter highlight */
```

### Add Your Photo
In the About section, you can add an `<img>` tag with your photo.

## 🧩 Features
- ✅ Custom animated cursor
- ✅ Particle background with connecting lines
- ✅ Typewriter effect hero
- ✅ Animated stats counters
- ✅ Scroll-reveal animations
- ✅ Filterable article grid (by publication)
- ✅ Experience timeline
- ✅ Admin login panel (5x footer click secret)
- ✅ Add/Edit/Delete articles via admin modal
- ✅ Articles persist via localStorage
- ✅ Mobile responsive
- ✅ Resume PDF linked from GitHub repo
