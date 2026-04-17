# About this site

Static memorial site for Katie Melynda Loeb, converted from WordPress and hosted on GitHub Pages.

## Technologies

| Area | Technology |
|------|------------|
| **Markup** | HTML5 (semantic structure, accessibility basics) |
| **Styling** | CSS3 — embedded `<style>` blocks, Flexbox, media queries |
| **Viewport / mobile** | `viewport-fit=cover`, `dvh` / `vh` viewport units, `env(safe-area-inset-*)` for notched devices |
| **Typography** | [Google Fonts](https://fonts.google.com/) — **Great Vibes** (display title), **Quicksand** (body / memorial text), **Dosis** (tagline / small UI) |
| **Meta / sharing** | Open Graph tags, Twitter Card meta, standard `<meta name="description">` |
| **Images** | PNG and JPEG assets in `images/`; favicons and legacy paths under `wp-content/uploads/` from the original WordPress export |
| **Hosting** | [GitHub Pages](https://pages.github.com/) — static files from the `master` branch |
| **Custom domain** | `CNAME` file for `boozemuse.net`; DNS points apex and `www` to GitHub Pages |
| **Jekyll** | Empty `.nojekyll` file so GitHub Pages serves files as-is (no Jekyll processing) |

## Third-party content (Rest In Peace page)

- **Twitter** — embedded tweets load `platform.twitter.com/widgets.js` when that page is viewed.
- **External images** — some article images are loaded from publisher CDNs (e.g. Billy Penn / WordPress.com image CDN) by URL.

## What this site does *not* use

- No JavaScript frameworks or CSS preprocessors.
- No build step or bundler — edit HTML/CSS and push to deploy.
- No server-side code or database.
