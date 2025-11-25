# 🎨 Articles HTML Générés

Ce dossier contient vos articles finaux en HTML, prêts pour intégration dans WordPress, organisés par projet.

## 📋 Utilisation

Les articles stockés ici sont les **versions HTML finales** générées par Claude IA, prêtes à être copiées dans un bloc HTML WordPress.

## 📁 Organisation par Projet

Les articles sont organisés dans des **sous-dossiers par projet/site** :

```
Article HTML généré/
├── web-starting.fr/
│   ├── 2024-11-25-cms-choisir-guide.html
│   ├── 2024-12-01-wordpress-vs-shopify.html
│   └── README.md
├── autre-projet/
│   ├── 2024-11-20-article-1.html
│   └── README.md
└── README.md
```

### Projets Disponibles

- **web-starting.fr** : Articles sur CMS, hébergement, création de sites
- *(Ajoutez vos projets au fur et à mesure)*

### Nommage dans un Projet

Format recommandé : `[date]-[titre-court].html`

**Exemples** :
- `2024-11-25-cms-choisir-guide.html`
- `2024-12-01-wordpress-vs-shopify.html`
- `2025-01-15-hebergement-comparatif.html`

**Astuce** : Utilisez le même nom que l'article brut correspondant, en changeant simplement l'extension pour `.html`

## ✅ Checklist avant Intégration WordPress

Avant d'intégrer un article dans WordPress, vérifiez :

### Fonctionnalités
- ✅ **Code complet** : HTML + CSS + JavaScript dans un seul fichier
- ✅ **Classe racine** : `.ws-scope` présente
- ✅ **Sommaire interactif** : Navigation fonctionnelle
- ✅ **Formulaire EmailJS** : Configuration correcte
- ✅ **CTAs** : Boutons de conversion présents

### Design & Responsive
- ✅ **Mobile-first** : Affichage correct sur mobile
- ✅ **Breakpoints** : Responsive sur tablette et desktop
- ✅ **Animations** : Fluides et non-bloquantes
- ✅ **Images** : Alt text présent, sources valides

### SEO & Accessibilité
- ✅ **H1 unique** : Un seul titre principal
- ✅ **Structure sémantique** : Balises HTML5 appropriées
- ✅ **Contenu visible sans JS** : Pas de dépendance JavaScript pour le contenu
- ✅ **Focus clavier** : Navigation au clavier possible
- ✅ **Contraste** : Lisibilité respectée

### Tests
- ✅ **Pas d'erreurs console** : Ouvrir avec un navigateur et vérifier
- ✅ **Formulaire fonctionnel** : Tester l'envoi d'email
- ✅ **Liens** : Tous les liens fonctionnent
- ✅ **Compatibilité** : Testé sur Chrome, Firefox, Safari

## 🚀 Intégration dans WordPress

### Étapes d'intégration :

1. **Ouvrir** le fichier HTML généré
2. **Copier** tout le code (Ctrl+A, Ctrl+C)
3. Dans WordPress :
   - Créer une nouvelle page/article
   - Ajouter un bloc **"HTML personnalisé"**
   - Coller le code
   - Prévisualiser
4. **Vérifier** :
   - L'affichage sur différents appareils
   - Le fonctionnement du formulaire
   - Les animations et interactions
5. **Publier** ou **enregistrer comme brouillon**

## 🔧 Modifications Post-Génération

Si vous devez modifier un article généré :

### Modifications Simples
- **Texte** : Chercher et remplacer directement dans le HTML
- **Couleurs** : Modifier les valeurs hexadécimales dans la section CSS
- **Liens** : Remplacer les URLs dans les balises `<a href="">`

### Modifications Complexes
- **Structure** : Dupliquer des sections HTML existantes
- **Formulaire** : Modifier les IDs EmailJS dans le JavaScript
- **Animations** : Ajuster les valeurs dans les `@keyframes` CSS

### Outils Recommandés
- **VS Code** : Éditeur avec coloration syntaxique
- **Prettier** : Pour formater le code (Extension VS Code)
- **Live Server** : Pour prévisualiser localement (Extension VS Code)

## 📊 Versioning

Si vous modifiez un article déjà publié :
- Conservez l'ancienne version : `article-v1.html`
- Nouvelle version : `article-v2.html`

Ou ajoutez la date de modification :
- `2024-11-25-article.html` (original)
- `2024-12-15-article.html` (modifié)

## 💾 Backup

**Important** : Ces articles sont précieux !
- Sauvegardez régulièrement ce dossier
- Utilisez Git pour versionner
- Conservez une copie cloud (Google Drive, Dropbox, etc.)

---

**Note** : Un exemple d'article généré sera fourni dans ce dossier comme référence.
