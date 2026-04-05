# refindapp.com

Marketing website for [ReFind](https://github.com/refindretail/refindapp) — a women's clothing resale marketplace app.

## Structure

Static HTML site with no build step. Four pages:

- `index.html` — Landing page (hero, how it works, app download)
- `features.html` — Feature highlights and trust & safety
- `privacy.html` — Privacy Policy (mirrors text in the mobile app)
- `terms.html` — Terms of Service (mirrors text in the mobile app)

## Deployment

Hosted on Netlify. Every push to `main` triggers an automatic deploy.

## Local preview

Open any HTML file directly in a browser, or run a simple static server:

```bash
npx serve .
```

## Editing

- Edit HTML files directly — no framework, no build.
- Styles are inline in each file's `<head>`.
- Keep privacy.html and terms.html in sync with `src/legal/privacy-policy.ts` and `src/legal/terms-of-service.ts` in the app repo when legal text changes.
