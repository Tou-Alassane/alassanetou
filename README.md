# Portfolio professionnel — Alassane Tou

Portfolio Angular en français, avec un design clair et responsive.

## Prérequis
- Node.js 22 (version LTS recommandée)
- npm

## Lancer en local
```bash
npm install
npm start
```
Ouvrir http://localhost:4200

## Personnalisation obligatoire
1. Remplacer `public/assets/photo-alassane.jpg` par votre portrait (format JPG conseillé, nom exact).
2. Ajouter votre CV sous `public/assets/cv-alassane-tou.pdf`.
3. Dans `src/app/app.component.html`, remplacer `contact.alassane@example.com` par votre vraie adresse e-mail et vérifier le lien LinkedIn.
4. Dans `src/app/app.component.ts`, modifier les descriptions, technologies et liens des projets pour refléter vos réalisations réelles.
5. Vérifier les intitulés et dates de formation.

## Publier sur GitHub Pages
Le workflow `.github/workflows/deploy.yml` construit le projet puis publie automatiquement `dist/portfolio/browser`.

1. Créer le dépôt public `Tou-Alassane.github.io`.
2. Envoyer tout le contenu de ce dossier à la racine de la branche `main`.
3. Sur GitHub : Settings > Pages > Build and deployment > Source, choisir **GitHub Actions**.
4. Ouvrir l’onglet **Actions** et attendre la réussite du workflow « Déployer le portfolio Angular sur GitHub Pages ».
5. Le site sera disponible à `https://Tou-Alassane.github.io/`.

Chaque push sur `main` relancera le déploiement.

## Construire localement
```bash
npm run build
```
Les fichiers prêts à publier se trouvent dans `dist/portfolio/browser`.
