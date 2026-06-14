# Ad Venture Hub — Website

Multi-page site for Ad Venture Hub (eco-zajednica i zadruga, planina Ozren, selo Prekonozi).

## Structure

```
index.html              Home — hero, koncept, o projektu, lokacija, zajednica teaser
model-saradnje.html     Model saradnje — Investitor/Rentijer/Stanovnik, Minima Casa, FAQ, kontakt
zajednica.html          Zajednica — članstvo, zaposlenje, ekologija, utočište za konje
infrastruktura.html     Infrastruktura — plan razvoja, skica imanja, partneri
assets/style.css         Shared design system (two-mode: "belonging" + "trust")
assets/photos/           Project photography (28 files, numbered + descriptively named)
```

## Design system

Two coexisting visual modes defined in `assets/style.css`:

- **belonging** — editorial, photo-led (hero, vision, community, location)
- **trust** — clean grid layouts (investment models, pricing, legal/FAQ)

Color tokens (`--moss`, `--field`, `--sand`, `--paper`, `--clay`, etc.) are derived from the
actual Ozren/Prekonozi photography. Single typeface pairing: Fraunces (display) + Source Sans 3 (body).

## Notes

- All photo references use relative paths (`assets/photos/...`) — keep folder structure intact.
- `27_infrastructure_map.png` and `28_logo_badge.png` are reference-only assets (map used on
  Infrastruktura page; logo badge currently unused — site uses an inline SVG house mark + wordmark).
- Lead form on `model-saradnje.html` is client-side only (no backend wired up yet).
