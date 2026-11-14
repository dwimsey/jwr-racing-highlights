# Jonathan Wimsey Racing #64W — 2026 Bandolero season highlights

Static single-page site: hero, season story slideshow, photo gallery, and 34 short race clips.

- `site/index.html` — the page (HTML/CSS/JS, no dependencies)
- `media-b64/` — clips (720p H.264), posters, and web photos packed as `media.tar`, base64-encoded in parts
- `.github/workflows/pages.yml` — decodes the media and publishes the finished site to the `gh-pages` branch

To serve it: Settings → Pages → Build and deployment → Source: **Deploy from a branch** → `gh-pages` / `(root)`.
