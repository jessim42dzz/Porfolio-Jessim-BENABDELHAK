# Configuration GitHub Pages

Voici comment configurer et publier votre portfolio sur GitHub Pages.

## Étape 1 : Créer un repository GitHub

1. Allez sur [github.com](https://github.com)
2. Cliquez sur **"New repository"**
3. **Nommez votre repository** : `jessim-benabdelhak` ou `portfolio` (le nom du compte n'est pas obligatoire si vous ne voulez pas `username.github.io`)
4. **Description** : Portfolio - Jessim Benabdelhak | Développeur Web BTS SIO SLAM
5. Cochez **"Public"** (pour que GitHub Pages soit gratuit)
6. Cliquez sur **"Create repository"**

## Étape 2 : Initialiser Git localement

Dans votre terminal, à la racine du projet (`/home/user/SLAM/Porfolio`) :

```bash
git init
git add .
git commit -m "Initial commit: Portfolio Jessim Benabdelhak"
git branch -M main
git remote add origin https://github.com/VOTRE_PSEUDO/VOTRE_REPO.git
git push -u origin main
```

Remplacez :
- `VOTRE_PSEUDO` par votre username GitHub
- `VOTRE_REPO` par le nom de votre repository

## Étape 3 : Activer GitHub Pages

1. Allez sur votre repository GitHub
2. Cliquez sur **Settings** (Paramètres)
3. Allez à **Pages** (dans le menu de gauche)
4. Sous **Source**, sélectionnez :
   - **Branch** : `main`
   - **Folder** : `/ (root)`
5. Cliquez sur **Save**

## Étape 4 : Accéder au portfolio en direct

Après 1-2 minutes, votre portfolio sera accessible à :

- Si votre repo s'appelle `jessim-benabdelhak.github.io` :
  ```
  https://votrepseudo.github.io
  ```

- Si votre repo a un autre nom (ex: `portfolio`) :
  ```
  https://votrepseudo.github.io/portfolio
  ```

Vous verrez une notification verte "Your site is live at..." dans les settings Pages.

## Étape 5 : Mettre le lien dans votre README

Le README affichera déjà un lien cliquable vers votre site en direct. Vous pouvez le mettre dans la description de votre repository aussi.

## 🚀 Publier les modifications

Chaque fois que vous faites des modifications :

```bash
git add .
git commit -m "Description de vos modifications"
git push
```

Le site se mettra à jour automatiquement en 1-2 minutes !

## Troubleshooting

### Le site n'apparaît pas
- Vérifiez que le repository est **Public**
- Attendez 2-3 minutes après le premier push
- Vérifiez dans les Settings > Pages que la source est correcte

### Le CSS/JS ne charge pas
- Vérifiez les chemins dans `index.html`
- Assurez-vous que `styles.css` et `script.js` sont à la racine
- Attendez quelques minutes pour que le cache se vide

### Les images/ressources ne s'affichent pas
- Utilisez des chemins relatifs : `./image.png` au lieu de `/image.png`

---

**Vous êtes prêt !** 🎉 Bon courage pour votre portfolio !
