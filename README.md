# Gem Match — Privacy Policy

Static, dependency-free privacy policy page for the **Gem Match** iOS app,
hosted on GitHub Pages. English + 中文 (English is the authoritative version).

- `index.html` → served at the repo root URL
- `privacy.html` → same content at an explicit path (use this as the official URL)
- `support.html` → technical support page (App Store Connect "Support URL")
- `marketing.html` → marketing / landing page (App Store Connect "Marketing URL"),
  uses compressed screenshots in `screenshots/`

index.html and privacy.html are identical; keep them in sync when you edit.
Contact email baked in: `wanggyxfmail@gmail.com`.

## Enable GitHub Pages
Repo → **Settings → Pages** → Source: **Deploy from a branch** →
Branch: `main` / `/ (root)` → Save. After ~1 minute the page is live at:

```
https://wanggit.github.io/gem-match-resources/privacy.html
```

## Where this URL goes
1. `assets/config/app_config.json` → `store.privacy_url` (in the game repo) — already filled in
2. App Store Connect → App Information → **Privacy Policy URL**

## Push (first time)
```bash
cd /Users/wanggang/projects/gem-match-resources
git push -u origin main
```
HTTPS auth: username = `wanggit`, password = a GitHub **Personal Access Token**
(repo scope). Or switch the remote to SSH if you have a key registered.
