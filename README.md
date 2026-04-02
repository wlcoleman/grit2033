# grit2033.com site

Simple static site for `grit2033.com`.

## Files
- `index.html`
- `styles.css`

## Deploy to GoDaddy

### Option 1: GoDaddy cPanel / Web Hosting
1. Log into GoDaddy.
2. Open the hosting account for `grit2033.com`.
3. Go to **File Manager** or connect via FTP.
4. Upload `index.html` and `styles.css` into the site's root folder (`public_html/` or the domain's document root).
5. If GoDaddy created a default `index.html`, replace it.
6. Visit `https://grit2033.com`.

### Option 2: GoDaddy Websites + Marketing
If the domain is only attached to Websites + Marketing and not standard hosting, this static upload flow may not work. In that case:
- easiest path is to attach the domain to any static host (Netlify, Vercel, GitHub Pages + custom domain), or
- provision basic GoDaddy hosting and upload these files there.

## Notes
- This is fully static: no build step, no framework, no package install.
- Edit copy directly in `index.html`.
- Main styling lives in `styles.css`.
- The mailto link currently points to `challenge@grit2033.com` — update or remove if you don't want that.

## Easy tweaks
- Ranking number: search `#9` in `index.html`
- Main headline: search `TOP 10 IN THE COUNTRY.`
- Fine print joke level: edit the footer paragraph
