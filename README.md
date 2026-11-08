# Raffay Rohan — Official Digital Agency & SEO Portfolio (`raffayrohan.com`)

**We Build. We Optimize. We Rank. We Grow.**

This repository contains the production static build for **https://raffayrohan.com**, pre-configured for **GitHub Pages**, **Cloudflare Pages**, **Vercel**, or **Netlify** with:
- **62 KB Ultra-Fast HTML Routes** + externalized `/assets/images/*.jpg` for `<0.5s` Largest Contentful Paint (`LCP`) and `0.00` Cumulative Layout Shift (`CLS`)
- **`CNAME`** pre-configured for `raffayrohan.com`
- **`.nojekyll`** for instant static serving without Jekyll build delays
- **`.github/workflows/deploy.yml`** for automatic GitHub Pages deployment on every push
- **Full Technical SEO Suite**: `robots.txt`, `sitemap.xml` (with English & Arabic `hreflang` links), `llms.txt` (for ChatGPT, Perplexity & Google AI Overviews), `site.webmanifest`, `favicon.svg`, and `404.html`

---

## How to Push & Go Live on GitHub Pages in 3 Minutes

### Step 1 — Upload or Push These Files to Your GitHub Repository
Unzip `raffay_rohan_agency_source_bundle.zip` into a folder on your computer, open your terminal in that folder, and run:

```bash
git init
git add .
git commit -m "Launch Raffay Rohan VIP Website & SEO Portfolio"
git branch -M main
git remote add origin https://github.com/<YOUR_GITHUB_USERNAME>/<YOUR_REPO_NAME>.git
git push -u origin main
```
*(Or simply drag-and-drop all unzipped files/folders directly into your GitHub repository via **Add file → Upload files** on github.com).*

### Step 2 — Enable GitHub Pages in Repository Settings
1. Open your repository on GitHub and click **Settings → Pages** (on the left sidebar).
2. Under **Build and deployment → Source**, select **Deploy from a branch** (branch: `main`, folder: `/ (root)`) **OR** select **GitHub Actions** (the included `.github/workflows/deploy.yml` workflow will deploy automatically).
3. Because the root `CNAME` file is already included in this bundle, GitHub Pages will automatically set your Custom Domain to **`raffayrohan.com`**.
4. Check the box **Enforce HTTPS**.

### Step 3 — Point Your Domain (`raffayrohan.com`) DNS to GitHub Pages
In your domain registrar / Cloudflare DNS panel for `raffayrohan.com`, add these records:

| Type | Name / Host | Value / Target |
| :--- | :--- | :--- |
| **A** | `@` | `185.199.108.153` |
| **A** | `@` | `185.199.109.153` |
| **A** | `@` | `185.199.110.153` |
| **A** | `@` | `185.199.111.153` |
| **CNAME** | `www` | `<YOUR_GITHUB_USERNAME>.github.io` |

### Step 4 — Submit to Google Search Console
Once live on `https://raffayrohan.com`, open **Google Search Console → Sitemaps** and submit:
- `https://raffayrohan.com/sitemap.xml`
