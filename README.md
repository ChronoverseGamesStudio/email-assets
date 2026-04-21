# Email Campaign Assets

Image assets for Chrono CCG, Mastering Runeterra, and Runeterra.AR email campaigns. Served via [jsDelivr CDN](https://www.jsdelivr.com/) for fast, globally cached delivery into email HTML.

## Usage

Public URL pattern for any image in this repo:

```
https://cdn.jsdelivr.net/gh/ChronoverseGamesStudio/email-assets@main/<path>
```

Example: `https://cdn.jsdelivr.net/gh/ChronoverseGamesStudio/email-assets@main/chrono_ccg/top_hero.png`

jsDelivr caches files for long periods — push a new file name when updating an image, or append `?v=2` to bust cache. For a permanent anchor use a git tag (`@v1.0.0` instead of `@main`).

## Layout

- `chrono_ccg/` — Chrono CCG brand (burgundy + bronze, dark)
- `mastering_runeterra/` — Mastering Runeterra brand (black + yellow)
- `runeterra_ar/` — Runeterra.AR brand (light cards + black). LoR/2XKO/Riftbound character PNGs are pre-composited with their circular brand badges baked in.

## Source

These are exported from the Figma Email Design file (`wdZjuiYTV4mSViqkJoU8J2`). See `E:\Chrono for Claude\_email\` for the MJML templates + Brevo push scripts that consume these URLs.
