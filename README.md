# Gem Match — Privacy Policy

Static, dependency-free privacy policy page for the **Gem Match** iOS app,
hosted on GitHub Pages.

- `index.html` → served at the repo root URL
- `privacy.html` → same content at an explicit path

Both files are identical; keep them in sync when you edit.

## Before publishing
Replace every `REPLACE_ME_EMAIL` with your real contact email (Apple requires
a reachable contact in the privacy policy), and update the "Effective date".

## Enable GitHub Pages
Repo → **Settings → Pages** → Source: **Deploy from a branch** →
Branch: `main` / `/ (root)` → Save. After ~1 minute the page is live at:

```
https://<your-username>.github.io/<repo-name>/
https://<your-username>.github.io/<repo-name>/privacy.html
```

Paste that URL into:
1. `assets/config/app_config.json` → `store.privacy_url` (in the game repo)
2. App Store Connect → App Information → **Privacy Policy URL**
