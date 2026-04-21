# CV — Karin Aït-Si-Amer

CV en ligne (Senior SRE & DevOps), site statique d'une seule page.

## Stack

- `index.html` — HTML/CSS/JS vanille, aucune dépendance, aucun build.
- `avatar.jpeg` — photo de profil.
- Export PDF via `window.print()` (bouton « ↓ PDF » en haut à droite, rendu light dédié via `@media print`).

## Développement local

Ouvrir `index.html` directement dans le navigateur, ou servir le dossier :

```bash
python3 -m http.server 8000
# puis http://localhost:8000
```

## Déploiement Vercel

Projet statique — aucune configuration nécessaire.

1. Importer le repo sur [vercel.com/new](https://vercel.com/new).
2. Framework Preset : **Other**.
3. Build Command : *(vide)*  ·  Output Directory : *(vide, racine)*.
4. Deploy.

Vercel sert `index.html` à la racine automatiquement.
