# TECHNOLOGIC AI POWER — Website

Static website for TECHNOLOGIC AI POWER, a Windows desktop application for managing and running AI models locally.

Plain HTML, CSS and JavaScript. No build step, no dependencies, no external requests, no separate image files.

## Files

- `index.html` — the whole site in ONE self-contained file (Home, Create an Account, Download, Help). The logo and the two real application screenshots are embedded inside it, so nothing else needs to be uploaded next to it.
- `.github/workflows/pages.yml` — optional GitHub Pages deployment

## Run locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository (branch `main`).
2. In the repository: Settings → Pages → Source: **GitHub Actions**.
3. Push again, or run the workflow manually from the Actions tab.

## Current status (what is NOT available yet)

- **Download:** no release exists. The Download page shows "Not published". When a build is ready, fill in version, date and size and replace the disabled button with a real link (see the comment in `index.html`).
- **Create an Account:** the form only validates input. No account service is connected.
- **Help:** topics are marked "Coming soon".
- **Privacy Policy / Terms of Use:** not written or linked yet.
- **Comparison:** competitor entries are intentionally general and must be verified against official documentation before publishing.
- **Screenshots:** real, but taken from one PC at one moment. To replace them, swap the embedded WebP images inside `index.html`.

## License

No license has been chosen. Add a `LICENSE` file before making the repository public.
