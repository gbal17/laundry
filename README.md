# Mariama's Premium Laundry & Garment Care — Website

**"We Wash, You Relax – Freshness You Can Trust!"**

---

## 📁 Folder Structure

```
laundry/
├── index.html          ← Main website page
├── css/
│   └── style.css       ← All styles
├── js/
│   └── main.js         ← Mobile menu + scroll effects
├── logos/
│   └── logo.png        ← Business logo (YOU MUST ADD THIS)
└── README.md
```

---

## 🚀 How to Publish on GitHub Pages (Step by Step)

### Step 1 — Make sure your logo is in the right place
Copy your logo file into the `logos/` folder and name it exactly:
```
logos/logo.png
```

### Step 2 — Open Terminal on your Mac
Press `Cmd + Space`, type **Terminal**, press Enter.

### Step 3 — Navigate to your laundry folder
```bash
cd ~/Documents/GitHub/laundry
```

### Step 4 — Initialise Git (only needed once)
```bash
git init
git add .
git commit -m "Initial commit — Mariama's Laundry website"
```

### Step 5 — Create a GitHub repository
1. Go to **https://github.com/new**
2. Name it: `laundry`
3. Set it to **Public**
4. Click **Create repository**
5. Copy the two commands GitHub shows you under *"push an existing repository"* — they look like:
```bash
git remote add origin https://github.com/YOUR-USERNAME/laundry.git
git branch -M main
git push -u origin main
```

### Step 6 — Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. Click **Pages** (left sidebar)
4. Under *Source* → select **Deploy from a branch**
5. Branch: **main** / Folder: **/ (root)**
6. Click **Save**

### Step 7 — Your website is live! 🎉
After 1–2 minutes your site will be live at:
```
https://YOUR-USERNAME.github.io/laundry/
```

---

## ✏️ One important edit before publishing

Open `index.html` and find this line (around line 14):
```html
<link rel="canonical" href="https://YOUR-USERNAME.github.io/laundry/" />
```
Replace `YOUR-USERNAME` with your actual GitHub username.

---

## 🔄 How to update the website later

Every time you change something, run:
```bash
cd ~/Documents/GitHub/laundry
git add .
git commit -m "Updated prices" 
git push
```
The website updates automatically within 1–2 minutes.

---

## 📞 Business Info
- **Phone 1:** +220 334 0782
- **Phone 2:** +220 415 1871
- **Location:** Brusubi Phase One, Last junction before Right Choice
- **WhatsApp:** https://wa.me/2203340782
