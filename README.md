# Atelier — Athletic Coaching

Export du code source présent dans le projet au moment de la publication.

Compte : [elmafiozam10-dot](https://github.com/elmafiozam10-dot)

## Ce que contient ce dépôt

- L’identité **Atelier** : titre, couleur, favicon (`public/favicon.svg`, `src/lib/og/site.json`).
- Le socle technique du workspace (React, TanStack Start, Vite, Tailwind).
- Les scripts, l’authentification précâblée et la configuration de build.

## Ce qui n’est pas dans ce dépôt

L’application de coaching (séances, nutrition, suivi, écran d’accueil) n’a pas été écrite : il n’y a pas encore de routes `src/routes`. Seule l’identité de marque a été produite.

Fichiers binaires non repris par l’export texte :

- `public/og.jpg` (carte de partage)
- images PNG de `public/__grok/`

`node_modules` n’est pas versionné. Aucun secret (jeton, `.env`, `DATABASE_URL`) n’est inclus.

## Installation

```bash
npm install
npm run dev
```
