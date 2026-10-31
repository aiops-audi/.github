# aiops-audi/.github

Public org profile and **public design assets** for Audi AIOPS.

- `profile/README.md` — public org profile (branding only), shown to non-members.
- `profile/assets/` — SVGs also used by the members-only profile in `aiops-audi/.github-private`. Images must live in a public repo: GitHub's image proxy cannot read private repos.

Do not put private repository names or internal details here — everything in this repo is public.

Images are referenced via jsDelivr (`cdn.jsdelivr.net/gh/aiops-audi/.github@main/...`) because `raw.githubusercontent.com` is blocked by the corporate Zscaler proxy. jsDelivr caches branches for up to 12h; after changing an SVG, purge it at `https://purge.jsdelivr.net/gh/aiops-audi/.github@main/profile/assets/<file>.svg`.

Palette: `#080b20` navy · `#f1f4ff` type · `#00e7ff` cyan · `#6035c9` violet glow.
