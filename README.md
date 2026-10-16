# Hoarde website

Static marketing site for [Hoarde](https://github.com/thedtripp/hoarde), plus the privacy policy and support pages that the App Store and Google Play listings link to.

Plain HTML/CSS, no build step:

| File | Page |
|---|---|
| `index.html` | Landing page |
| `privacy.html` | Privacy policy (App Store "Privacy Policy URL") |
| `support.html` | Support / FAQ (App Store "Support URL") |
| `404.html` | Not-found page |

## Publish with GitHub Pages

Settings → Pages → Source: **Deploy from a branch** → `main` / `(root)`.

The site will be live at `https://thedtripp.github.io/Hoarde-site/`. To use a custom domain (e.g. `hoarde.app`), add it in the same settings page and point DNS at GitHub.

## Before launch

- The contact address `support@hoarde.app` is a placeholder. Set up the mailbox, or replace it in `privacy.html` and `support.html`.
- Images in `assets/` are copies of the final Stage 1 art from the app repo. When that art changes, copy the matching files over.
- Keep `privacy.html` in sync with the app. Adding crash reporting, analytics or purchases (RevenueCat) requires updating it.

## Preview locally

```bash
python3 -m http.server 8000
```
