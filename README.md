# Doodlewing Gallery

A self-contained Three.js first-person gallery for Doodlewing.

## Local Preview

Run a static server from this folder, then open:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Preview URL:

```txt
http://127.0.0.1:4173/?v=doodlewing-wall-text-5
```

## Deployment

This project is intended to be connected to Vercel. The site is static: `index.html`, `images/`, and `vendor/`.
