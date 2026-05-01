# RISE — AR/VR Natural Wake System

> *We don't wake you up. We bring the morning to you.*

A fully interactive onboarding experience and AR/VR dawn simulation for the RISE Natural Wake System. Built as a single-file HTML app — no dependencies, no build step, runs anywhere.

**Live Demo:** [your-project.vercel.app](https://your-project.vercel.app)

---

## What This Is

An 8-screen interactive product experience that:

1. Collects user sleep habits and lifestyle data
2. Captures sensory preferences (light, sound, temperature, airflow)
3. Lets users pick their emotional anchor environment
4. Runs an AI analysis animation sequence
5. Generates a personalised morning wake preset
6. Previews the full AR/VR dawn experience with a real-time canvas simulation

---

## Project Structure

```
rise-wake/
├── index.html      ← The entire app (self-contained)
├── vercel.json     ← Vercel deployment config
├── .gitignore      ← Standard ignores
└── README.md       ← This file
```

Everything lives in `index.html` — no external dependencies except Google Fonts (loaded via CDN).

---

## How to Share (3 Ways)

### Option 1 — Send the File Directly
Just share `index.html` with anyone. They open it in any browser. Works 100% offline.

### Option 2 — Vercel (Recommended, Free, Instant URL)
Follow the deployment guide below. You get a public URL like `rise-wake.vercel.app`.

### Option 3 — GitHub Pages (Also Free)
Follow the GitHub Pages section below.

---

## Deploy to Vercel

### Method A: Drag & Drop (Fastest — No account setup needed)

1. Go to [vercel.com](https://vercel.com) and sign up (free)
2. Click **"Add New → Project"**
3. Scroll down — find the **"Or deploy without a Git provider"** section
4. Drag this entire `rise-wake` **folder** onto the upload area
5. Click **Deploy**
6. Wait ~30 seconds → you get a live URL ✅

> ⚠️ Important: Drag the **folder**, not just the file.

---

### Method B: GitHub → Vercel (Best for Updates)

#### Step 1 — Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `rise-wake-system` (or anything you like)
3. Set to **Public** or **Private** (both work with Vercel)
4. Do NOT check "Add a README" — you already have one
5. Click **Create repository**

#### Step 2 — Upload Files to GitHub

**If you have Git installed on your computer:**

```bash
# Open terminal, navigate to the rise-wake folder
cd path/to/rise-wake

# Initialize git
git init

# Add all files
git add .

# First commit
git commit -m "Initial deploy: RISE Natural Wake System"

# Connect to your GitHub repo (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/rise-wake-system.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**If you prefer the GitHub website (no terminal):**

1. Open your new GitHub repo in the browser
2. Click **"uploading an existing file"** link
3. Drag all 4 files (`index.html`, `vercel.json`, `.gitignore`, `README.md`) into the upload area
4. Scroll down → click **"Commit changes"**

#### Step 3 — Connect Vercel to GitHub

1. Go to [vercel.com/new](https://vercel.com/new)
2. Click **"Import Git Repository"**
3. Sign in with GitHub → select your `rise-wake-system` repo
4. Vercel auto-detects the config (thanks to `vercel.json`)
5. Click **Deploy** — no settings to change
6. Done! You get a URL like `rise-wake-system.vercel.app` ✅

#### Step 4 — How to Update in the Future

Whenever you change `index.html` and push to GitHub, Vercel auto-redeploys in ~20 seconds:

```bash
git add index.html
git commit -m "Update: improved experience screen"
git push
```

---

## Deploy to GitHub Pages (Alternative)

1. Push files to GitHub (follow Step 1 & 2 above)
2. In your GitHub repo → click **Settings**
3. Left sidebar → click **Pages**
4. Under "Source" → select **"Deploy from a branch"**
5. Branch: `main` | Folder: `/ (root)`
6. Click **Save**
7. Wait 2–3 minutes → your site is live at:
   `https://YOUR_USERNAME.github.io/rise-wake-system/`

---

## Custom Domain (Optional)

If you own a domain (e.g., `rise-wake.com`):

1. In Vercel dashboard → your project → **Settings → Domains**
2. Add your domain name
3. Copy the DNS records Vercel gives you
4. Add them in your domain registrar (GoDaddy, Namecheap, etc.)
5. Wait 10–60 minutes for DNS propagation
6. Your site is live at your custom domain ✅

---

## Running Locally

No server needed. Just double-click `index.html` — it opens in your browser.

Or use a local server for best results:

```bash
# Python (usually pre-installed on Mac/Linux)
python3 -m http.server 3000
# Then open: http://localhost:3000

# Node.js (if installed)
npx serve .
# Then open the URL it shows
```

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `→` Arrow Right | Next screen / Next dawn stage |
| `←` Arrow Left | Previous screen / Previous dawn stage |

---

## Browser Compatibility

| Browser | Status |
|---------|--------|
| Chrome 90+ | ✅ Full support |
| Firefox 88+ | ✅ Full support |
| Safari 14+ | ✅ Full support |
| Edge 90+ | ✅ Full support |
| Mobile Chrome | ✅ Responsive |
| Mobile Safari | ✅ Responsive |

---

## Credits

- **Concept:** AR/VR Natural Wake System — RISE
- **Design & Development:** Abhimanyu Shukla
- **Fonts:** Cormorant Garamond, DM Sans, DM Mono (Google Fonts)
- **Technology:** Vanilla HTML, CSS, JavaScript — zero dependencies

---

## License

This project is for portfolio and demonstration purposes.
© 2026 RISE Natural Wake System. All rights reserved.
