# Valentine-Invite

Single-page romantic Valentine invite with a minimal frosted-glass landing message, gentle sakura petals, and a hidden envelope that opens into the main question.

## Run locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish on GitHub Pages

This repository includes an automatic GitHub Pages workflow at `.github/workflows/deploy-pages.yml`.

### One-time setup
1. Push this repo to GitHub.
2. In GitHub, go to **Settings → Pages**.
3. Set **Source** to **GitHub Actions**.

### Deploy
- Push to the `main` branch, or run the **Deploy static site to GitHub Pages** workflow manually from the Actions tab.
- Your site will be published at:
  - `https://<your-username>.github.io/<repo-name>/`
