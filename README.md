# aiops-audi/.github

Public org profile and **public design assets** for Audi AIOPS.

- `profile/README.md` — public org profile (branding only), shown to non-members.
- `profile/assets/` — SVGs also used by the members-only profile in `aiops-audi/.github-private`. Images must live in a public repo: GitHub's image proxy cannot read private repos.

Do not put private repository names or internal details here — everything in this repo is public.

Images are referenced via jsDelivr pinned to a commit of `aiops-audi/.github` (`cdn.jsdelivr.net/gh/aiops-audi/.github@<commit>/...`) because `raw.githubusercontent.com` is blocked by the corporate Zscaler proxy and `@main` is cached for hours. After changing an SVG in `.github`, push it, then replace the commit hash in both `profile/README.md` files with the new commit.

Palette: `#080b20` navy · `#f1f4ff` type · `#00e7ff` cyan · `#6035c9` violet glow.
