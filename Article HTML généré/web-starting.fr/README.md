# 🎨 Articles HTML Générés - web-starting.fr

Ce dossier contient les articles finaux en HTML pour le site **web-starting.fr**, prêts pour intégration dans WordPress.

## 📁 Nommage des Fichiers

Format recommandé : `[date]-[titre-court]-[sujet].html`

**Exemples** :
- `2024-11-25-cms-choisir-guide.html`
- `2024-12-01-wordpress-vs-shopify.html`
- `2025-01-15-hebergement-web-comparatif.html`

💡 **Astuce** : Utilisez le même nom que l'article brut correspondant en changeant simplement l'extension.

## ✅ Checklist Pré-Publication

### Contenu
- [ ] Titre H1 unique et optimisé SEO
- [ ] Sommaire fonctionnel avec smooth scroll
- [ ] Toutes les sections ont un ID correspondant
- [ ] Texte complet sans placeholder/lorem ipsum
- [ ] CTAs pertinents et bien placés
- [ ] Formulaire de contact visible

### Design & UX
- [ ] Couleurs web-starting.fr (vert #082416 + jaune #e8ff45)
- [ ] Police Montserrat chargée
- [ ] Responsive sur mobile ✓
- [ ] Responsive sur tablette ✓
- [ ] Responsive sur desktop ✓
- [ ] Hero section impactante
- [ ] Highlight boxes bien formatées

### Technique
- [ ] Classe racine `.ws-scope` présente
- [ ] EmailJS configuré (service, template, public key)
- [ ] IDs de formulaire uniques (`#form-cms`, `#name-cms`, etc.)
- [ ] Pas d'erreur dans la console navigateur
- [ ] JavaScript fonctionnel (simulateur, formulaire)
- [ ] Smooth scroll opérationnel
- [ ] Images avec alt text (si applicable)

### SEO & Accessibilité
- [ ] H1 unique
- [ ] Structure hiérarchique H2, H3 respectée
- [ ] Contenu visible sans JavaScript (opacity: 1)
- [ ] Focus clavier fonctionnel
- [ ] Labels de formulaire avec for/id
- [ ] Liens avec texte descriptif

## 🚀 Intégration WordPress

### Méthode Standard

1. **Copier** le code HTML complet
2. Dans WordPress, **éditer** la page/article souhaité
3. **Ajouter** un bloc "HTML personnalisé"
4. **Coller** tout le code
5. **Prévisualiser** sur différents appareils
6. **Publier** ou sauvegarder

### Méthode Avancée (Template PHP)

Pour les utilisateurs avancés, vous pouvez créer un template de page personnalisé :

1. Créer `page-article-custom.php` dans votre thème
2. Y inclure le code HTML
3. Sélectionner ce template dans WordPress

## ⚙️ Configuration Post-Intégration

### EmailJS
Vérifiez que les identifiants EmailJS sont corrects :
```javascript
emailjs.init('EbZUccJ9uKukb5WRE');
emailjs.send('service_btbtgzn', 'template_m06wtf1', ...)
```

### CTAs
Remplacez les liens/téléphones si nécessaire :
```html
<a href="tel:+33641127926">06 41 12 79 26</a>
<a href="#contact-cms">Formulaire</a>
```

### IDs Uniques
Si plusieurs articles sur la même page, suffixer les IDs :
```html
<!-- Article 1 -->
<form id="form-cms-article1">

<!-- Article 2 -->
<form id="form-cms-article2">
```

## 🔧 Modifications Courantes

### Changer les Couleurs

Cherchez et remplacez dans le CSS :
```css
/* Vert foncé */
#082416 → votre couleur
#0a2d1a → votre couleur

/* Jaune fluo */
#e8ff45 → votre couleur
#d4f442 → votre couleur
```

### Ajuster le Responsive

Modifiez les media queries :
```css
@media (max-width: 968px) { }  /* Tablette */
@media (max-width: 640px) { }  /* Mobile */
```

### Changer le Téléphone

Recherchez `06 41 12 79 26` et remplacez partout :
```html
<a href="tel:+33641127926">06 41 12 79 26</a>
```

### Personnaliser le Simulateur

Modifiez la logique dans le JavaScript :
```javascript
function showRecommendation() {
  // Adapter la logique ici
}
```

## 🧪 Tests Recommandés

### Tests Fonctionnels
1. **Sommaire** : Cliquer sur chaque lien
2. **Simulateur** : Tester toutes les combinaisons
3. **Formulaire** : Envoyer un test
4. **CTAs** : Vérifier tous les liens/boutons

### Tests Cross-Browser
- ✓ Chrome/Edge (Chromium)
- ✓ Firefox
- ✓ Safari (desktop et mobile)

### Tests Mobile
- ✓ iPhone (Safari)
- ✓ Android (Chrome)
- ✓ Tablettes

### Tests Performance
- Ouvrir la console développeur (F12)
- Vérifier aucune erreur JavaScript
- Tester le temps de chargement
- Vérifier les animations fluides

## 📊 Analytics et Suivi

### Événements à Tracker

```javascript
// CTA clicks
gtag('event', 'cta_click', {
  'event_category': 'engagement',
  'event_label': 'obtenir_conseils'
});

// Form submission
gtag('event', 'form_submit', {
  'event_category': 'conversion',
  'event_label': 'contact_cms'
});

// Simulator usage
gtag('event', 'simulator_complete', {
  'event_category': 'engagement',
  'event_label': 'cms_choice'
});
```

## 💾 Versioning

Si vous modifiez un article déjà publié :

```
2024-11-25-cms-choisir-guide-v1.html (original)
2024-11-25-cms-choisir-guide-v2.html (modifié le 15/12)
2024-11-25-cms-choisir-guide-v3.html (modifié le 10/01)
```

Ou avec dates de modification :
```
2024-11-25-cms-choisir-guide.html (original)
2024-12-15-cms-choisir-guide.html (mise à jour)
```

## 🆘 Troubleshooting

### Le formulaire ne s'envoie pas
➡️ Vérifier la clé publique EmailJS et les IDs de service/template

### Le sommaire ne fonctionne pas
➡️ Vérifier que les IDs de sections correspondent aux hrefs du sommaire

### Problème d'affichage WordPress
➡️ Vérifier que le thème WordPress ne surcharge pas les styles (all: revert)

### Animations ne fonctionnent pas
➡️ Vérifier les conflits potentiels avec d'autres scripts WordPress

### Le simulateur ne répond pas
➡️ Ouvrir la console (F12) et vérifier les erreurs JavaScript

---

**Site** : web-starting.fr
**Support technique** : contact.capitainepub@gmail.com
**Dernière mise à jour** : 2025-11-25
