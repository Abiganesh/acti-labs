# ACTI Labs public website

Public marketing site for ACTI Labs, an advertising intelligence and creative
systems company.

## Local preview

From this directory:

```powershell
python -m http.server 4173
```

Open `http://localhost:4173`.

## Deployment

The included GitHub Actions workflow deploys this static site to GitHub Pages
whenever `main` is updated.

1. Create a public repository named `acti-labs` under `abiganesh`.
2. Push this directory as the repository root.
3. In repository settings, open **Pages** and set the source to **GitHub Actions**.
4. The site will be available at `https://abiganesh.github.io/acti-labs/`.

The private Ad Intelligence Pipeline is intentionally excluded from this public
site and must remain in a separate private repository.
