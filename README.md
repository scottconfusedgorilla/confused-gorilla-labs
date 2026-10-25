# Confused Gorilla Labs

A small, responsive, static one-page site for Confused Gorilla Labs.

## Projects

- [OGFramework](https://ogframework.com/) — structured open governance for AI organizations
- [airtrōv](https://airtrov.com/) — AI-powered catalogs
- [catdef](https://catdef.org/) — open portable object and catalog format

## Preview locally

No dependencies or build step. Run from this repository:

```bash
python -m http.server 8000 -d public
```

Then visit http://localhost:8000.

## Deploy on Cloudflare Pages (recommended)

1. Create a GitHub repository named `confused-gorilla-labs` and add these files.
2. In Cloudflare: **Workers & Pages → Create → Pages → Connect to Git**.
3. Select the repository and branch `main`.
4. **Build command:** `exit 0` (or leave empty), **Build output directory:** `public`.
5. Deploy, then add your custom domain under the Pages project's **Custom domains** setting.

The `public` directory is all that Cloudflare needs to serve.

> Cloudflare's **Direct Upload** is possible without a repository, but a Direct Upload Pages project cannot later be switched to Git integration. If you want continuous deployment from GitHub, start with **Connect to Git**.

## Notes

- Static HTML, CSS, and a tiny script; no npm, database, analytics, tracking, or cookies.
- The gorilla mark is cropped from the original selected option-2 brand concept provided by the project owner.
- External links open in a new tab with `noopener noreferrer`.
- The footer links to the owner's GitHub profile rather than inventing a contact email address.