# NaniTech (Pty) Ltd — Official Website

> **Technology Solutions That Empower Businesses and Individuals**

A complete, production-ready single-page website for **NaniTech (Pty) Ltd** — a South African ICT company founded by Vuyolwethu Ndolela.

---

## 🚀 Hosting on GitHub Pages (Step-by-Step)

### Step 1 — Create a GitHub account
If you don't have one, sign up at [github.com](https://github.com).

### Step 2 — Create a new repository
1. Click the **+** icon (top right) → **New repository**
2. Name it: `nanitech` (or `nanitech-website`)
3. Set visibility to **Public**
4. Do **not** initialise with a README (you already have one)
5. Click **Create repository**

### Step 3 — Upload the files
**Option A — Drag & Drop (easiest):**
1. On the new repo page, click **uploading an existing file**
2. Drag both `index.html` and `README.md` into the upload area
3. Scroll down → click **Commit changes**

**Option B — Using Git (recommended for future updates):**
```bash
git init
git add index.html README.md
git commit -m "Initial NaniTech website launch"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/nanitech.git
git push -u origin main
```

> ⚠️ Rename `nanitech.html` → `index.html` before uploading so GitHub Pages serves it correctly.

### Step 4 — Enable GitHub Pages
1. Go to your repository → **Settings**
2. Scroll to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: `main` | Folder: `/ (root)`
5. Click **Save**

### Step 5 — Visit your live site
After 1–2 minutes your site will be live at:
```
https://YOUR_USERNAME.github.io/nanitech/
```

---

## ✨ Features

| Feature | Details |
|---|---|
| 🌗 Dark / Light Mode | Toggle in the navbar — preference saved across visits |
| 📱 Fully Responsive | Mobile-first, works on all screen sizes |
| 💬 Smart Enquiry | Form → choose Email or WhatsApp → pre-filled message sent |
| 🎨 Animated Background | Live particle network canvas |
| ⚡ Scroll Reveal | Elements animate into view as you scroll |
| 🔍 SEO Ready | Meta tags, semantic HTML, ARIA labels |
| 🚫 Zero Dependencies | No frameworks — pure HTML, CSS, JavaScript |

---

## 📁 File Structure

```
nanitech/
├── index.html      ← The entire website (rename from nanitech.html)
└── README.md       ← This file
```

---

## 📞 Contact Details (in the website)

| | |
|---|---|
| 📱 Phone / WhatsApp | +27 65 893 8239 |
| 📧 Email | nanitechsolve@gmail.com |
| 📍 Location | South Africa |

---

## 🛠️ Updating the Website

All content is in a **single `index.html` file**. To make changes:

1. Open `index.html` in any text editor (VS Code recommended)
2. Search (`Ctrl+F`) for the text you want to change
3. Edit and save
4. Re-upload to GitHub (or `git push` if using Git)

Changes go live within ~1 minute.

---

## 🌐 Custom Domain (Optional)

To use `www.nanitech.co.za` instead of the GitHub URL:
1. In your repo → **Settings → Pages → Custom domain** → enter your domain
2. At your domain registrar, add a `CNAME` record pointing to `YOUR_USERNAME.github.io`

---

*© NaniTech (Pty) Ltd — Proudly South African. Technology for Everyone.*
