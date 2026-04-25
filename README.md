# Riverland International GmbH — Website

A simple one-page corporate website for Riverland International GmbH, the company behind the **OG ASIA** retail brand. Built as static HTML/CSS so it can be hosted for free on GitHub Pages.

## Deploy to GitHub Pages

1. Create a new repo on GitHub (public). Suggested name: `riverland-website` or `riverland-international`.
2. Upload the contents of this folder (`index.html`, `404.html`, `.nojekyll`, `README.md`) to the repo root.
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to `Deploy from a branch`.
5. Set **Branch** to `main` and folder to `/ (root)`. Click **Save**.
6. After a minute, your site will be live at `https://<your-username>.github.io/<repo-name>/`.

## Custom domain (optional)

If you want to host this on something like `riverland-international.de`:

1. Add a `CNAME` file to the repo root containing only the domain (e.g. `riverland-international.de`).
2. In your DNS provider, add the records GitHub asks for (4 A records pointing to GitHub's IPs, plus an optional `www` CNAME).
3. In **Settings → Pages**, enter the custom domain and enable "Enforce HTTPS" once the certificate is issued.

## Editing content

Everything lives in `index.html` — open it, find the section, edit the text. Sections are clearly commented:

- `HERO` — headline and lead paragraph
- `ABOUT` — company description and OG ASIA card
- `VALUES` — the five principles
- `CONTACT` — HQ + warehouse addresses
- `IMPRESSUM` — legal info (do not change without checking with your tax/legal advisor)

## Brand

- Brand color: `#004FFF`
- Display font: Fraunces (serif)
- Body font: Inter Tight (sans-serif)
- Both fonts are loaded from Google Fonts — no setup required.

## Adding photos later

When you have logo and photo assets, drop them into an `/assets` folder and reference them from `index.html`. The hero section is the natural place to add a product shot or brand photo if you want one.
