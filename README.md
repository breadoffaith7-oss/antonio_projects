# Antonio M. Lemba — Applied AI Portfolio

A single-page portfolio website showcasing my vision, AI projects and research.

## Files

- `index.html` — the website
- `styles.css` — styling
- `images/` — put your profile photo here (see `images/README.txt`)

Pure static HTML/CSS — no build step, no dependencies.

## How to publish it

### Option A — GitHub Pages (free, fastest)

1. Push `index.html` and `styles.css` to the root of this repository.
2. On GitHub: **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then **Save**.
5. After ~1 minute the site is live at:
   `https://breadoffaith7-oss.github.io/antonio_projects/`

### Option B — Vercel (free, custom domain easy)

1. Go to vercel.com → **Add New → Project** → import this repository.
2. Framework preset: **Other**. No build command needed.
3. **Deploy**. You get a `*.vercel.app` URL and can add a custom domain.

## Use it in your application

Paste the published URL into the **"Website"** field of the Anthropic
application form.

## Editing

All text lives in `index.html`. Colours and layout are in `styles.css`
(see the `:root` variables at the top to change the accent colour).
