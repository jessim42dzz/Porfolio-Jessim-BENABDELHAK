# Structure du Projet

Voici l'organisation des fichiers de votre portfolio pour GitHub Pages.

## 📁 Structure optimisée pour GitHub Pages

```
Porfolio/
│
├── index.html              ✅ Page principale (sera servie par défaut)
├── styles.css              ✅ Feuille de styles
├── script.js               ✅ JavaScript interactif
│
├── README.md               📖 Documentation principale (affiché sur GitHub)
├── GITHUB-PAGES.md         📖 Guide de publication sur GitHub Pages
├── PROJECT-STRUCTURE.md    📖 Ce fichier
│
├── .gitignore              ⚙️ Fichiers à ignorer par Git
├── .nojekyll               ⚙️ Configuration GitHub Pages
│
└── portfolio-split/        📦 (Ancien dossier - peut être supprimé)
    ├── index.html
    ├── styles.css
    ├── script.js
    ├── start-server.sh
    └── README.md
```

## 🎯 Fichiers clés

### `index.html`
- Contient toute la structure HTML du portfolio
- Importe `styles.css` et `script.js` depuis la racine
- Responsive design avec breakpoints mobiles

### `styles.css`
- Design moderne avec palette de couleurs personnalisée
- Animations fluides et transitions
- Support du mode responsive jusqu'à 820px de largeur

### `script.js`
- Curseur personnalisé animé
- Animation de révélation au scroll (Intersection Observer)
- Interactions souris sur les liens et boutons

### `README.md`
- Présentation générale du portfolio
- Liens cliquables vers les projets
- Instructions de démarrage local
- Aperçu des compétences

### `GITHUB-PAGES.md`
- Guide étape par étape pour publier sur GitHub Pages
- Troubleshooting et solutions aux problèmes communs

### `.gitignore`
- Ignore les fichiers système, éditeurs et environnements
- Garde le repository propre

### `.nojekyll`
- Fichier vide mais important
- Désactive le processus de build Jekyll de GitHub Pages
- Permet à GitHub de servir directement les fichiers statiques

## 🚀 Avant de publier

Vérifiez que :
- [ ] Les fichiers HTML, CSS et JS sont à la **racine** (`/Porfolio/`)
- [ ] Tous les chemins d'import sont corrects (chemins relatifs)
- [ ] Les fonts Google charger (vérifiez votre connexion internet en local)
- [ ] Le portfolio fonctionne localement : `python3 -m http.server 8000`

## 🌐 URL finale

Une fois publié, votre site sera accessible à :

```
https://VOTRE_USERNAME.github.io/jessim-benabdelhak
```

Ou si vous nommez votre repo `jessim-benabdelhak.github.io` :

```
https://VOTRE_USERNAME.github.io
```

## 📝 Mettre à jour le portfolio

Pour modifier le contenu :

1. Éditez les fichiers HTML/CSS/JS
2. Testez localement : `python3 -m http.server 8000`
3. Committez et pushez :
   ```bash
   git add .
   git commit -m "Description des modifications"
   git push
   ```
4. Attendez 1-2 minutes pour que GitHub Pages se mette à jour

## 🗑️ Dossier `portfolio-split/` (ancien)

Le dossier `portfolio-split/` contient les anciens fichiers. Vous pouvez le supprimer une fois que vous avez confirmé que tout fonctionne avec les fichiers à la racine :

```bash
rm -rf portfolio-split
git add -u
git commit -m "Remove legacy folder"
git push
```

---

**Vous êtes prêt à publier !** 🎉
