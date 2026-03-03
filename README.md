# 👑 Touched Tierras — Website

**"A touch of Love and Royalty"**  
Natural Hair & Braiding Studio — Built by [3:56am Production](https://github.com/356amproduction)

---

## 🌐 Live Site
> Deploy link goes here once hosted (e.g. Render, Netlify, or GitHub Pages)

---

## 📁 Project Structure

```
TouchedTierras_Website/
│
├── index.html              ← Main website (home page)
├── lookbook.html           ← Standalone lookbook page (backup)
├── README.md               ← This file
│
└── images/
    ├── logo/
    │   └── touched_tierras_logo.png
    ├── hero/
    │   └── hero_group_photo.jpg
    ├── about/
    │   └── tierra_profile.jpg
    ├── services/
    │   ├── braiding_styles.png
    │   ├── twist_styles.png
    │   ├── loc_services.png
    │   └── added_hair_extensions.png
    └── gallery/
        └── *.jpg  (19 portfolio photos)
```

---

## 🚀 Getting Started Locally

### Step 1 — Clone the repo

```bash
git clone https://github.com/YOUR-USERNAME/touched-tierras.git
cd touched-tierras
```

### Step 2 — Open the site

No build tools needed — it's a static HTML site. Just open the file:

```bash
# Mac
open index.html

# Windows
start index.html

# Or drag index.html into any browser
```

---

## 🛠 Making Changes

### Edit the site
Open `index.html` in any code editor (VS Code recommended):

```bash
code index.html
```

### Save your changes to GitHub

```bash
# Check what changed
git status

# Stage your changes
git add .

# Commit with a message
git commit -m "Update hero section"

# Push to GitHub
git push origin main
```

---

## 🌍 Deploying (Free Hosting Options)

### Option A — GitHub Pages (easiest)
1. Go to your repo on GitHub
2. Click **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your site will be live at `https://YOUR-USERNAME.github.io/touched-tierras`

### Option B — Netlify
1. Go to [netlify.com](https://netlify.com) → **Add new site → Import from Git**
2. Connect your GitHub repo
3. Leave build settings blank (static site)
4. Click **Deploy** — live in ~30 seconds

### Option C — Render
1. Go to [render.com](https://render.com) → **New → Static Site**
2. Connect your GitHub repo
3. Set publish directory to `/` (root)
4. Click **Create Static Site**

---

## ✏️ Things to Update

| Location | What to change |
|----------|---------------|
| Footer | Add phone number, address, Instagram |
| Testimonials | Replace placeholder reviews with real client quotes |
| About section | Update years of experience / stats |
| Gallery | Add new photos to `images/gallery/` and reference in `index.html` |
| Booking link | Already set to `touchedtierras.booksy.com/a/` ✅ |

---

## 🎨 Brand Colors

| Name | Hex |
|------|-----|
| Deep Rose | `#e8789a` |
| Rose | `#f4a7b9` |
| Blush | `#f8d7da` |
| Petal | `#fce8ee` |
| Cream | `#fff5f7` |
| Text | `#3d1f2d` |

---

## 🔗 Booking
All booking buttons link to → **[touchedtierras.booksy.com/a/](http://touchedtierras.booksy.com/a/)**

---

## 📸 Adding New Gallery Photos

1. Drop the new `.jpg` or `.png` into `images/gallery/`
2. Open `index.html` and find the lookbook section (search for `lb-panel`)
3. Add a new `lb-item` div inside the correct category panel:

```html
<div class="lb-item fade-in">
  <img src="images/gallery/YOUR-PHOTO.jpg" alt="Touched Tierras" loading="lazy">
  <div class="lb-overlay"><span>View</span></div>
</div>
```

4. Save, commit, and push:

```bash
git add .
git commit -m "Add new gallery photos"
git push origin main
```

---

*Built with ❤️ by 3:56am Production*
