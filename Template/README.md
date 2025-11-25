# 📄 Templates HTML

Ce dossier contient vos templates HTML de référence pour la génération d'articles, organisés par projet.

## 📋 Utilisation

Les templates stockés ici servent de **modèle de référence** pour :
- La structure HTML
- Les styles CSS
- L'architecture JavaScript
- Les contraintes WordPress

## 📁 Organisation par Projet

Les templates sont organisés dans des **sous-dossiers par projet/site** :

```
Template/
├── web-starting.fr/
│   ├── template-cms-article.html
│   ├── template-hebergement.html
│   └── README.md
├── autre-projet/
│   ├── template-article-1.html
│   └── README.md
└── README.md
```

### Projets Disponibles

- **web-starting.fr** : Templates pour articles sur CMS, hébergement, création de sites
- *(Ajoutez vos projets au fur et à mesure)*

### Nommage dans un Projet

Format recommandé : `template-[type]-[description].html`

**Exemples** :
- `template-cms-article.html`
- `template-comparatif-hebergement.html`
- `template-guide-wordpress.html`
- `template-tutoriel-technique.html`

## ✅ Checklist d'un Bon Template

Un template doit contenir :
- ✅ Structure HTML complète avec `.ws-scope`
- ✅ CSS inline avec `all: revert`
- ✅ JavaScript en IIFE pour isolation
- ✅ Configuration EmailJS fonctionnelle
- ✅ Formulaire de contact optimisé
- ✅ Design responsive mobile-first
- ✅ Sommaire interactif (si applicable)
- ✅ CTAs stratégiquement placés
- ✅ Commentaires clairs dans le code

## 💡 Conseils

1. **Créez un sous-dossier par projet** : Un dossier par site/client pour mieux s'organiser
2. **Testez vos templates** : Assurez-vous qu'ils fonctionnent dans WordPress avant de les utiliser comme référence
3. **Documentez les spécificités** : Ajoutez un README.md dans chaque projet avec les détails (couleurs, fonts, config EmailJS)
4. **Versionnez** : Si vous modifiez un template, conservez l'ancienne version (ex: `template-v1.html`, `template-v2.html`)

## 🚀 Créer un Nouveau Projet

1. Créer un nouveau sous-dossier : `Template/nom-du-projet/`
2. Copier un template existant comme base
3. Adapter le design et la structure
4. Créer un README.md avec les spécificités du projet
5. Tester dans WordPress
6. Documenter les composants réutilisables

## 🚀 Créer un Nouveau Template dans un Projet

1. Aller dans le dossier du projet
2. Copier un template existant du projet
3. Modifier le design et la structure selon vos besoins
4. Tester dans un bloc HTML WordPress
5. Sauvegarder avec un nom descriptif
6. Ajouter des commentaires pour les sections spécifiques

---

**Organisation** : Un sous-dossier par projet pour une meilleure gestion
