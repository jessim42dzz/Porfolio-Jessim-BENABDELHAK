# 🚀 Quick Start - Portfolio sur GitHub Pages

## 3 étapes pour publier votre portfolio

### Étape 1 : Préparation locale (30 secondes)

Vérifiez que les fichiers sont en place :
```bash
ls -la /home/user/SLAM/Porfolio/
# Doit afficher : index.html, styles.css, script.js, README.md, .gitignore, .nojekyll
```

### Étape 2 : Créer un repo GitHub (2 minutes)

1. Allez sur **[github.com/new](https://github.com/new)**
2. Nommez-le : `jessim-benabdelhak` (ou le nom que vous préférez)
3. Cochez **"Public"**
4. Créez le repository

### Étape 3 : Pousser le code (2 minutes)

```bash
cd /home/user/SLAM/Porfolio

# Initialiser Git
git init
git add .
git commit -m "Initial commit: Portfolio"

# Ajouter le repository distant (remplacez USERNAME et REPO)
git remote add origin https://github.com/USERNAME/REPO.git
git branch -M main
git push -u origin main
```

**Remplacez :**
- `USERNAME` → votre pseudo GitHub
- `REPO` → le nom de votre repository

### Étape 4 : Activer GitHub Pages (30 secondes)

1. Allez dans **Settings** de votre repo
2. Cherchez **Pages** (dans le menu gauche)
3. Sélectionnez `main` et `/` (root)
4. Cliquez **Save**

### 🎉 Voilà !

Attendez 1-2 minutes, puis allez à :

```
https://USERNAME.github.io/REPO
```

## Besoin d'aide ?

- **Erreur lors du push ?** → Vérifiez que le remote est correct : `git remote -v`
- **Le site ne s'affiche pas ?** → Vérifiez que le repo est PUBLIC
- **Les fichiers ne chargent pas ?** → Attendez 2-3 minutes et videz le cache (Ctrl+Maj+Suppr)

## Fichiers de documentation

Consultez :
- 📖 [README.md](README.md) - Présentation générale
- 📖 [GITHUB-PAGES.md](GITHUB-PAGES.md) - Guide détaillé
- 📖 [PROJECT-STRUCTURE.md](PROJECT-STRUCTURE.md) - Structure du projet

---

**C'est fait ! Votre portfolio est prêt à être publié.** ✨
