# Maintenance — WaspTracker (GitHub Pages)

Page de maintenance statique (HTML/CSS) pensée pour être utilisée comme cible d’une redirection **OVH 302**
pendant des travaux sur un site principal (ex. Lovable).

## Déploiement
1. Fork ce repo
2. Repo → **Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` / Folder: `/ (root)`

URL finale:
- `https://<user>.github.io/<repo>/`

## OVH (redirection temporaire)
Créer une redirection **302** de `https://tondomaine.fr/*` vers l’URL GitHub Pages.

## Personnalisation rapide
- Remplacer l’email `contact@wasptracker.com`
- Remplacer le texte (titre / sous-titre)
- Remplacer les SVG dans `assets/`

## SEO
- `noindex, nofollow` + `robots.txt` qui bloque tout.
