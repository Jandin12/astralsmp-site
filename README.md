# Astral SMP

The official landing page for **Astral SMP**, a Minecraft survival server. Single-page, static site — no build step, no dependencies beyond Google Fonts.

**Live site:** https://astralsmp.org
**Server IP:** `play.astralsmp.org` (Java & Bedrock via GeyserMC, Bedrock port `19132`)
**Live map:** https://map.astralsmp.org

## Structure

```
.
├── index.html                       # entire site (HTML/CSS/JS in one file)
├── favicon.svg                      # primary favicon (vector, modern browsers)
├── favicon.ico                      # fallback favicon (legacy browsers)
├── apple-touch-icon.png             # iOS home screen icon
├── CNAME                            # custom domain config for GitHub Pages
└── assets/
    ├── favicon-16x16.png
    ├── favicon-32x32.png
    ├── android-chrome-192x192.png
    └── android-chrome-512x512.png
```

## Tech

- Plain HTML/CSS/JS, no framework or build tooling
- Fonts: Montserrat + Inter (Google Fonts)
- Canvas-based starfield background, CSS nebula gradients, inline SVG ringed-planet emblem
- Hosted on GitHub Pages with a custom domain

## Local preview

Just open `index.html` in a browser — no server required.

## Deployment

This site deploys automatically via **GitHub Pages** whenever `main` is updated. See the setup guide provided alongside this README for connecting the `astralsmp.org` domain (registered on name.com) to this repo.

## Editing content

Everything lives in `index.html`:

- Hero title/tagline — `<section id="top" class="hero">`
- About/feature cards — `<section id="about">`
- How to Join steps — `<section id="join">`
- Server IP / map info — `<section id="server">`
- Color palette and fonts — CSS custom properties at the top of the `<style>` block (`:root`)

## License

Not affiliated with Mojang or Microsoft.
