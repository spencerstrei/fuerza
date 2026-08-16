# fuerza — legacy URL redirects

This repo exists for one reason: the Fuerza marketing site used to be published
here as GitHub Pages at `https://spencerstrei.github.io/fuerza/`. Those URLs are
still referenced by already-released App Store listings, so they must keep
resolving.

The real site now lives at **https://fuerza.spencerstrei.com** (Cloudflare
Workers, private repo `spencerstrei/fuerzasite`).

This repo contains **only redirect stubs** — no site source, no assets.

| Legacy URL | Redirects to |
|---|---|
| `/fuerza/` | `https://fuerza.spencerstrei.com/` |
| `/fuerza/privacy.html` | `https://fuerza.spencerstrei.com/privacy` |
| `/fuerza/support.html` | `https://fuerza.spencerstrei.com/support` |

It is public because GitHub Pages requires a public repo on the Free plan.
It can be deleted once no released App Store version references these URLs.
