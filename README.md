# 📝 Générateur d'Articles HTML pour WordPress

Processus de génération d'articles optimisés pour WordPress à partir de contenu brut rédigé sur Google Docs.

## 🗂️ Structure du Projet

```
article-html/
├── Template/               # Templates HTML de référence
│   ├── web-starting.fr/   # Templates pour web-starting.fr
│   └── [autre-projet]/    # Un dossier par projet
├── Article Brut/          # Articles bruts (texte depuis Google Docs)
│   ├── web-starting.fr/   # Articles pour web-starting.fr
│   └── [autre-projet]/    # Un dossier par projet
├── Article HTML généré/   # Articles HTML finaux générés
│   ├── web-starting.fr/   # Articles générés pour web-starting.fr
│   └── [autre-projet]/    # Un dossier par projet
├── PROMPT_TEMPLATE.md     # Template de prompt pour Claude IA
├── GUIDE_UTILISATION.md   # Guide rapide d'utilisation
└── README.md              # Ce fichier
```

### 🎯 Organisation par Projets

Pour faciliter la gestion de plusieurs sites/clients, chaque dossier principal (`Template`, `Article Brut`, `Article HTML généré`) est organisé en **sous-dossiers par projet**.

**Avantages** :
- Séparation claire entre les différents projets
- Templates et articles facilement retrouvables
- Meilleure organisation à long terme
- Évite les confusions entre projets

**Projets actuels** :
- **web-starting.fr** : Articles sur CMS, hébergement, création de sites web

## 🚀 Processus de Génération

### Étape 0 : Choisir/Créer un Projet

Si c'est votre **premier article pour un nouveau projet** :
1. Créer les sous-dossiers dans les 3 dossiers principaux :
   - `Template/[nom-projet]/`
   - `Article Brut/[nom-projet]/`
   - `Article HTML généré/[nom-projet]/`
2. Créer un template de base dans `Template/[nom-projet]/`
3. Ajouter un README.md dans chaque sous-dossier avec les spécificités du projet

Si c'est un article pour un **projet existant**, passer directement à l'étape 1.

### Étape 1 : Préparer le Contenu

1. **Rédiger l'article** sur Google Docs
2. **Copier le texte brut** de l'article
3. **Enregistrer** le texte dans `Article Brut/[nom-projet]/` (format `.txt` ou `.md`)

### Étape 2 : Choisir un Template

1. Sélectionner un **template HTML** dans `Template/[nom-projet]/`
2. Ce template servira de référence pour :
   - La structure HTML
   - Les styles CSS
   - L'architecture JavaScript
   - Les contraintes WordPress

### Étape 3 : Générer l'Article HTML

1. **Ouvrir** le fichier `PROMPT_TEMPLATE.md`
2. **Copier** le prompt template
3. **Remplacer** les sections :
   - `[MÉTIER]` : Indiquer le métier/thématique de l'article
   - Ajouter le contenu du template HTML
   - Ajouter le texte brut de l'article
4. **Soumettre** le prompt à Claude IA
5. **Récupérer** le code HTML généré

### Étape 4 : Intégration WordPress

1. **Copier** le code HTML généré
2. Dans WordPress, **créer un bloc HTML personnalisé**
3. **Coller** le code
4. **Publier** ou prévisualiser

## 📋 Caractéristiques des Articles Générés

### ✅ Structure WordPress

- **Classe racine unique** : `.ws-scope` pour l'isolation
- **CSS** : Utilisation de `all: revert` (pas `all: initial`)
- **JavaScript** : IIFE avec isolation de scope
- **Aucun conflit** avec les thèmes WordPress

### ✅ SEO-Friendly

- Contenu visible **sans JavaScript** (`opacity: 1`, `transform: translateY(0)`)
- **Structure sémantique** complète
- **H1 unique** par article
- **Sommaire interactif** pour navigation

### ✅ EmailJS Intégré

- Script CDN EmailJS inclus
- Configuration :
  - Service : `service_btbtgzn`
  - Template : `template_m06wtf1`
  - Destination : `contact.capitainepub@gmail.com`
- Vérification `typeof emailjs` avec fallback

### ✅ Formulaire Optimisé

- Styles d'autofill webkit corrigés
- Labels accessibles avec `for`/`id`
- Validation et feedback utilisateur
- États success/error

### ✅ Design & UX

- **Responsive** complet (mobile-first)
- **Animations** subtiles non-bloquantes
- **Focus visible** pour accessibilité
- **CTAs** stratégiquement placés pour conversion
- **Éléments interactifs** : simulateurs, outils selon le contenu

## 📁 Organisation des Fichiers

### Template/

Stockez ici vos templates HTML de référence :
- `template-article-standard.html`
- `template-article-metier-[nom].html`
- etc.

**Nommage recommandé** : `template-[type]-[description].html`

### Article Brut/

Stockez ici vos articles en texte brut :
- `2024-11-25-titre-article.txt`
- `article-metier-plombier.md`
- etc.

**Nommage recommandé** : `[date]-[titre-court].[txt|md]`

### Article HTML généré/

Les articles HTML finaux générés seront stockés ici :
- `2024-11-25-titre-article.html`
- `article-metier-plombier.html`
- etc.

**Nommage recommandé** : même nom que l'article brut avec extension `.html`

## 💡 Conseils d'Utilisation

1. **Toujours partir d'un template** : Assurez la cohérence visuelle entre vos articles
2. **Enrichir le contenu** : N'hésitez pas à demander des éléments interactifs (simulateurs, calculateurs, etc.)
3. **Tester sur mobile** : Vérifiez toujours le rendu mobile-first
4. **Vérifier EmailJS** : Testez le formulaire de contact après intégration
5. **Optimiser le SEO** : Vérifiez que tous les éléments sont visibles sans JavaScript

## 🔧 Personnalisation

Pour personnaliser le prompt de génération, modifiez le fichier `PROMPT_TEMPLATE.md` selon vos besoins :
- Ajustez les contraintes techniques
- Modifiez la configuration EmailJS
- Adaptez les exigences de design
- Changez les CTAs et stratégies de conversion

## 📞 Support

Pour toute question ou problème :
- Email : contact.capitainepub@gmail.com
- Référez-vous au `PROMPT_TEMPLATE.md` pour les spécifications détaillées

---

**Dernière mise à jour** : 2025-11-25
