# Maxwell Five — maxwelfive.com

Static site, no build step: `index.html`, `gracias.html`, `styles.css`, `img/`.

## Dev

```bash
python3 -m http.server 4322   # http://localhost:4322
```

## Deploy (Netlify)

Import the repo in Netlify, leave the build command empty, publish directory `.`.
Then Domains → add the domain, point DNS, and HTTPS is automatic.

## Contact form

Uses **Netlify Forms** (`contacto`), with a honeypot and reCAPTCHA. After the first deploy, go to
Forms → `contacto` → Settings & notifications and add an email notification.
Submissions redirect to `/gracias`.

## Editing

- Video: change `videoid` on `<lite-youtube>` in `index.html`.
- Members: the `.disc` list in `index.html` and the JSON-LD `member` list in `<head>`.
# maxwell-five
# maxwell-five
