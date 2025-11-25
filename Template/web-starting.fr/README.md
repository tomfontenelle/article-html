# 📄 Templates web-starting.fr

Ce dossier contient les templates HTML pour les articles du site **web-starting.fr**.

## 🎨 Style et Identité Visuelle

**Couleurs principales** :
- Vert foncé : `#082416` / `#0a2d1a`
- Jaune fluo : `#e8ff45` / `#d4f442`
- Police : Montserrat

**Caractéristiques** :
- Design moderne et professionnel
- Gradient vert foncé avec accents jaune fluo
- Responsive mobile-first
- Animations subtiles

## 📋 Templates Disponibles

### `template-cms-article.html`
Template complet pour articles de blog avec :
- Hero section avec gradient
- Sommaire interactif numéroté
- Simulateur interactif CMS
- Tableaux comparatifs
- CTAs stratégiques
- Formulaire de contact EmailJS
- Section finale avec split layout (texte + formulaire)

**Utilisation** : Articles de guide/comparatif technique

**Éléments interactifs** :
- Simulateur de choix CMS (3 questions)
- Formulaire de contact avec EmailJS
- Navigation sommaire smooth scroll

## ⚙️ Configuration EmailJS

**Service ID** : `service_btbtgzn`
**Template ID** : `template_m06wtf1`
**Public Key** : `EbZUccJ9uKukb5WRE`
**Email destination** : contact.capitainepub@gmail.com

## 🔧 Composants Disponibles

### Hero Section
```html
<section class="article-hero">
  <!-- Meta + Titre + Description + Stats -->
</section>
```

### Sommaire
```html
<div class="table-of-contents">
  <!-- Liste avec numérotation -->
</div>
```

### Simulateur
```html
<div class="cms-simulator">
  <!-- Questions + Recommandations -->
</div>
```

### CTA Inline
```html
<div class="cta-inline">
  <!-- Titre + Texte + Bouton -->
</div>
```

### Tableau Comparatif
```html
<div class="comparison-table">
  <div class="comparison-grid">
    <!-- Grid 3 colonnes -->
  </div>
</div>
```

### Highlight Box
```html
<div class="highlight-box">
  <span class="highlight-icon">💡</span>
  <p class="highlight-text">Texte important</p>
</div>
```

### Formulaire Final
```html
<section class="final-cta">
  <div class="final-box">
    <!-- Split: Texte + Formulaire -->
  </div>
</section>
```

## 💡 Bonnes Pratiques

1. **IDs de section** : Toujours utiliser `id="section-X"` pour le sommaire
2. **Classe racine** : Tout dans `.ws-scope` pour isolation
3. **CTAs** : Alterner les styles (primary/secondary)
4. **Simulateurs** : Adapter la logique JavaScript selon le sujet
5. **Formulaires** : Vérifier les IDs EmailJS

## 🎯 Personnalisation pour un Nouvel Article

1. **Hero** : Changer titre, highlight, description, badge
2. **Sommaire** : Adapter les sections et leurs liens
3. **Contenu** : Remplacer sections et simulateurs
4. **CTAs** : Adapter les textes et liens/téléphones
5. **Formulaire** : Personnaliser les champs si besoin

---

**Site** : web-starting.fr
**Dernière mise à jour** : 2025-11-25
