# Nexavia — Landing Page

Landing page de conversion pour **Nexavia**, studio web haut de gamme (sites vitrines,
apps web, e-commerce). Design dark mode futuriste, glassmorphism, animations néon,
CTA directs vers WhatsApp.

## Démo
Déployée sur Netlify (voir l'URL fournie après `netlify deploy`).

## Structure
- `index.html` — page unique autonome (HTML + Tailwind CDN + CSS/JS inline).
- `netlify.toml` — config Netlify (site statique, racine = `.`).

## Personnalisation rapide
- Numéro WhatsApp : remplacer `22892264531` (7 occurrences) dans `index.html`.
- Email de contact : `contact@nexavia.com`.
- Liens réseaux sociaux : les 4 icônes pointent vers `#` → mettre les vrais URLs.
- Textes, stats et projets : tout est en clair dans `index.html`.

## Déploiement local (CLI)
```bash
netlify deploy --prod --dir .
```
Ou via GitHub : importer le dépôt dans Netlify (Import from Git).

Dernier déploiement : 2026-08-29 13:19 UTC via webhook GitHub→Netlify
