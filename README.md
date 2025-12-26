# Color Splash Studio

Une application web progressive (PWA) pour créer des effets "Color Splash" sur vos photos : gardez certains objets en couleur et passez le reste en noir et blanc.

## 🎨 Fonctionnalités

- **Sélection magique** : cliquez sur une zone pour la sélectionner automatiquement
- **Sélection par couleur** : gardez une gamme de couleur spécifique
- **Pinceau / Gomme** : affinez votre sélection manuellement
- **Pipette** : sélectionnez une couleur depuis l'image
- **Multi-sélections** : combinez plusieurs zones/couleurs
- **Export haute qualité** : téléchargez en résolution originale

## 📱 Installation sur téléphone

### iPhone (Safari)
1. Ouvrez le lien de l'app dans Safari
2. Appuyez sur le bouton "Partager" (carré avec flèche)
3. Sélectionnez "Sur l'écran d'accueil"
4. Confirmez "Ajouter"

### Android (Chrome)
1. Ouvrez le lien de l'app dans Chrome
2. Appuyez sur les 3 points (menu)
3. Sélectionnez "Ajouter à l'écran d'accueil"
4. Confirmez

## 🚀 Déploiement sur GitHub Pages

1. Créez un nouveau repository sur GitHub
2. Uploadez tous les fichiers de ce dossier
3. Allez dans Settings → Pages
4. Source : "Deploy from a branch"
5. Branch : main, folder : / (root)
6. Cliquez Save

Votre app sera disponible à : `https://VOTRE-USERNAME.github.io/NOM-DU-REPO/`

## 📁 Fichiers

```
├── index.html      # Application principale
├── manifest.json   # Configuration PWA
├── sw.js          # Service Worker (mode offline)
├── icon-192.png   # Icône 192x192
├── icon-512.png   # Icône 512x512
└── README.md      # Ce fichier
```

## 🛠️ Technologies

- HTML5 Canvas
- JavaScript vanilla (pas de dépendances)
- PWA (Progressive Web App)
- Service Worker pour le mode offline

## 📄 Licence

MIT - Libre d'utilisation
