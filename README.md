# 🦘 Aussie Tracker

Application PWA pour ton WHV Australie.

## Contenu
- 🏠 Accueil — dashboard résumé
- 💼 Jobs — candidatures + commentaires
- 📚 Vocabulaire — mots + quiz
- 🎓 Formation — certifications + dépenses
- ✅ Tâches — todo list
- 🗺️ Parcours — timeline des lieux visités

---

## Déploiement sur GitHub Pages (5 min)

### 1. Créer le repo GitHub
1. Va sur [github.com](https://github.com) → **New repository**
2. Nom du repo : `aussie-tracker`
3. Laisse tout par défaut → **Create repository**

### 2. Push les fichiers depuis VS Code

Ouvre un terminal dans le dossier du projet et tape :

```bash
git init
git add .
git commit -m "init"
git branch -M main
git remote add origin https://github.com/TON_USERNAME/aussie-tracker.git
git push -u origin main
```

*(Remplace `TON_USERNAME` par ton pseudo GitHub)*

### 3. Activer GitHub Pages
1. Dans le repo GitHub → **Settings** → **Pages**
2. Source : **Deploy from a branch**
3. Branch : **main** → **/ (root)**
4. Clique **Save**

Ton app sera dispo en quelques secondes sur :
**`https://TON_USERNAME.github.io/aussie-tracker`**

---

## Ajouter sur l'écran d'accueil du tel

### iPhone (Safari)
1. Ouvre l'URL dans Safari
2. Icône **Partager** (carré avec flèche) → **Sur l'écran d'accueil**
3. Nomme-la "Aussie" → **Ajouter**

### Android (Chrome)
1. Ouvre l'URL dans Chrome
2. Menu **⋮** → **Ajouter à l'écran d'accueil**

L'app s'ouvre alors en plein écran, sans barre de navigateur, comme une vraie app.

---

## Fichiers
```
aussie-tracker/
├── index.html     ← toute l'app (1 seul fichier)
└── manifest.json  ← config PWA (icône, couleur, nom)
```

Aucune installation, aucun npm, aucune compilation. Juste 2 fichiers.
