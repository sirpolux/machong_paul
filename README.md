# Machong Paul portfolio

Static, responsive portfolio built with Tailwind CSS 4. GitHub Pages serves `index.html`, `assets/styles.css`, and `Machong_Paul_Resume.pdf` directly; Node is needed only when changing the styling.

## Publish on GitHub Pages

1. Copy the contents of this folder into the root of your `mac_paul` repository (or another repository configured for Pages). Commit `assets/styles.css` and the PDF along with `index.html`.
2. In repository Settings → Pages, select **Deploy from a branch**, the `main` branch, and `/ (root)`.
3. If you use a different public URL, update the `canonical`, `og:url`, and JSON-LD `url` values in `index.html`.

## Change the site

Run `npm ci` and `npm run build` after changing `index.html` classes or `input.css`. Commit the regenerated `assets/styles.css`. Run `npm run dev` while actively editing.

## Content to review before publishing

- Confirm the employer names, job titles, dates, and project descriptions, especially where the uploaded résumé differs from older portfolio copy.
- Confirm whether `https://github.com/sirpolux/fintrack2` should be linked as a publicly reviewable project.
- Confirm permission to name or describe internal Fundtron platforms publicly.
- Review the attached résumé before publishing: some claims (for example “zero latency”) and dates deserve careful verification.
