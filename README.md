# wangjiahong.github.io

Information technology consulting company website, hosted via GitHub Pages.

Live site: https://wangjiahong.github.io

## Structure

- `index.html` – Desktop homepage.
- `mobile.html` – Mobile homepage (auto-redirected to from `index.html` for mobile user agents).
- `assets/` – Scripts, styles, images, and fonts used by the desktop page.
- `mobile_files/` – Assets used by the mobile page.
- `responsive.css` – Responsive style overrides.

## Local preview

Serve the folder with any static file server, for example:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Deployment

The `main` branch is published automatically by GitHub Pages. Pushing to `main` updates the live site.

## Analytics

Google Analytics (`G-VT4ZQ39273`) is configured in both `index.html` and `mobile.html`.
