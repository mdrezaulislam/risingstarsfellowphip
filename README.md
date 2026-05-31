# HOWLADER Rising Stars Program

A static website for the **HOWLADER Rising Stars Fellowship** — a program empowering Bangladesh's brightest undergraduate students to pursue careers in Neuroscience.

## 🚀 Hosting on GitHub Pages (Free)

Follow these steps to publish this site for free on GitHub Pages:

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create a free account).
2. Click the **+** icon → **New repository**.
3. Name it: `howlader-rising-stars` (or anything you like).
4. Set it to **Public**.
5. Click **Create repository**.

### Step 2 — Upload the Files

**Option A — Using the GitHub website (easiest):**
1. Open your new repository.
2. Click **Add file → Upload files**.
3. Drag and drop `index.html` into the upload area.
4. Click **Commit changes**.

**Option B — Using Git on your computer:**
```bash
git init
git add index.html README.md
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/howlader-rising-stars.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repository, go to **Settings → Pages** (left sidebar).
2. Under **Source**, select **Deploy from a branch**.
3. Choose `main` branch and `/ (root)` folder.
4. Click **Save**.

### Step 4 — Visit Your Live Site

After a minute, your site will be live at:

```
https://YOUR_USERNAME.github.io/howlader-rising-stars/
```

GitHub will show you the exact URL in the Pages settings.

---

## 📁 File Structure

```
howlader-rising-stars/
└── index.html      # Complete single-file website
└── README.md       # This file
```

## ✏️ How to Customise

Open `index.html` in any text editor and update:

- **Fellow names/bios** — search for `fellow-card` sections
- **Contact email** — search for `mrezaulislam33@gmail.com`
- **Fellowship amount** — search for `4,000 BDT`
- **Year** — search for `2025`

## 🎨 Tech Stack

- Pure HTML, CSS, and vanilla JavaScript
- No build tools or dependencies required
- Google Fonts (Cormorant Garamond, DM Sans, Playfair Display)
- Fully responsive (mobile-friendly)
