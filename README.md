# DTech Support — Static Site

This is a simple, fast one‑page website for **DTech Support** you can host for free on **GitHub Pages** or upload to Blacknight.

## Files
- `index.html` — main page
- `styles.css` — styles
- `assets/logo.png` — put your logo here (replace the placeholder)
- `assets/cover.jpg` — optional cover image (hero background)
- `assets/favicon.svg` — small icon for browser tabs

> Tip: keep images small (under ~300 KB) so the page loads fast on mobile.

---

## How to publish on GitHub Pages (free)

1. Create a new GitHub repo called **dtechsupport.ie** (or any name).
2. Upload all files from this folder (keep the same structure).
3. In the repo → **Settings → Pages** →
   - **Build & deployment**: Deploy from **branch**
   - **Branch**: `main` / root (`/`) → **Save**
4. Your site will be live at `https://YOUR-USERNAME.github.io/REPO-NAME/`

### Use your custom domain
1. In GitHub → Settings → Pages → **Custom domain** → enter `dtechsupport.ie` (or `www.dtechsupport.ie`).
2. In Blacknight DNS:
   - For **apex** (dtechsupport.ie): add **A records** pointing to GitHub Pages:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - For **www**: add a **CNAME** to `YOUR-USERNAME.github.io`
3. Back in GitHub Pages → make sure **Enforce HTTPS** is ticked.

(Propagation may take up to a few hours.)

---

## Where to edit content
- Main headline, services, and text are in `index.html`
- Colours and spacing are in `styles.css` (primary navy `#0A1F44`, teal `#1ABC9C`)

---

## Contact form
The form uses Formspree (free). Replace the `action` URL in `index.html` with your own Formspree endpoint, or just remove the form and use the email + phone links.

---

## Replace images
- Put your **logo** at `assets/logo.png` (PNG with transparent background recommended)
- Put an optional **cover image** at `assets/cover.jpg` (will show subtly behind the hero text)
