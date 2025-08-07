# 🌟 Portail d'Applications

Une application web élégante pour présenter et organiser vos projets personnels avec un design moderne et responsive.

## ✨ Fonctionnalités

- 🎨 Design moderne avec mode clair/sombre
- 🔍 Recherche en temps réel
- 📋 Tri des applications (nom, date)
- 💫 Animations fluides et transitions
- 🎯 Interface responsive
- 🌊 Effets visuels subtils (bulles en arrière-plan)
- 💾 Persistance du mode sombre/clair

## 🛠️ Technologies utilisées

- HTML5
- TailwindCSS (via CDN)
- JavaScript (Vanilla)
- Lucide Icons
- LocalStorage pour la persistance

## 📝 Structure des données

Les applications sont chargées depuis un fichier `apps.json` avec la structure suivante :

```json
[
  {
    "name": "Nom de l'application",
    "description": "Description de l'application",
    "icon": "nom-icone-lucide",
    "link": "https://lien-vers-app.com",
    "github": "https://github.com/...",
    "date": "2025-01-01"
  }
]
```

## 🚀 Installation

1. Clonez le dépôt
2. Créez votre fichier `apps.json` à la racine
3. Servez les fichiers via un serveur web (nécessaire pour le chargement du JSON)

## 💡 Utilisation

- Le thème s'adapte automatiquement aux préférences système
- Utilisez la barre de recherche pour filtrer les applications
- Triez les applications par nom ou date
- Cliquez sur une carte pour ouvrir l'application
- Le lien "Code source" ouvre le dépôt GitHub dans un nouvel onglet

## 🎨 Personnalisation

- Modifiez les couleurs via les classes Tailwind
- Ajustez les animations dans la section CSS
- Personnalisez les bulles d'arrière-plan via la fonction `createBubbles()`

## 📱 Compatibilité

- ✅ Responsive (mobile, tablette, desktop)
- ✅ Navigateurs modernes
- ✅ Mode sombre/clair