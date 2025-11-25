# 🤖 Template de Prompt pour Génération d'Articles HTML

Utilisez ce template pour générer vos articles HTML optimisés pour WordPress avec Claude IA.

---

## 📝 PROMPT À COPIER

```
GÉNÈRE un bloc HTML pour WordPress représentant un article de blog qui est [MÉTIER].
Responsive et mobile first. Ce code sera ensuite intégré à un bloc wordpress.

---

## TEMPLATE DE RÉFÉRENCE

Le code que tu vas générer doit suivre le code template que je vais te fournir ci-dessous. Ce template te servira de :
- Structure HTML de référence
- Styles CSS à reproduire fidèlement
- Architecture JavaScript à respecter
- Contraintes WordPress à maintenir

### CODE TEMPLATE :
```html
[INSÉRER ICI LE CODE HTML DU TEMPLATE DE RÉFÉRENCE]
```

---

## CE QUE JE SOUHAITE

Je souhaite que tu créer également un **sommaire interactif**, qui permette à l'utilisateur de naviguer au sein de l'article de manière fluide et intuitive.

---

## ⚠️ CONTRAINTES WORDPRESS STRICTES

- **Classe racine unique** : `.ws-scope` (pour isolation complète)
- **CSS** : Utiliser `all: revert` (PAS `all: initial`)
- **JavaScript** : IIFE (Immediately Invoked Function Expression) avec isolation de scope
- **Aucun conflit** avec les thèmes WordPress existants
- **Compatibilité** : Doit fonctionner dans un bloc HTML personnalisé WordPress

---

## 🔍 CONTENU SEO-FRIENDLY

- **Contenu visible sans JavaScript** : `opacity: 1`, `transform: translateY(0)` par défaut
- **Structure sémantique complète** : balises HTML5 appropriées
- **H1 unique** : Un seul H1 par article
- **Meta descriptions** : Inclure dans les commentaires si pertinent
- **Alt text** : Toutes les images doivent avoir un texte alternatif descriptif

---

## 📧 EMAILJS INTÉGRÉ

- **Script CDN EmailJS** : Inclus dans le HTML
- **Configuration** :
  - Service ID : `service_btbtgzn`
  - Template ID : `template_m06wtf1`
  - Email destination : `contact.capitainepub@gmail.com`
- **Vérification** : `typeof emailjs` avec fallback approprié
- **Gestion d'erreurs** : Messages clairs pour l'utilisateur

---

## 📋 FORMULAIRE OPTIMISÉ

- **Styles d'autofill webkit** : Corrigés pour cohérence visuelle
- **Labels accessibles** : Utilisation correcte de `for`/`id`
- **Validation côté client** : Validation HTML5 + JavaScript
- **Feedback utilisateur** : Messages de succès/erreur clairs
- **États visuels** : Success, error, loading
- **Protection anti-spam** : Honeypot ou autres techniques

---

## 🎨 DESIGN REQUIS

- **Responsive complet** : Mobile-first approach
- **Breakpoints** : Mobile (<768px), Tablet (768-1024px), Desktop (>1024px)
- **Animations subtiles** : Non-bloquantes, améliorant l'expérience
- **Focus visible** : Pour accessibilité clavier (WCAG)
- **Contraste** : Respecter les normes WCAG AA minimum
- **Typography** : Hiérarchie claire et lisible

---

## 📄 CONTENU DE L'ARTICLE

Je vais te fournir en texte brut la totalité du contenu de l'article ci-dessous.

### INSTRUCTIONS IMPORTANTES :
- **Préserver le contenu** : Laisse le texte tel quel, ne modifie pas le fond
- **Enrichissement visuel** : Tu peux enrichir avec :
  - Photos pertinentes (avec alt text)
  - Simulateurs interactifs
  - Calculateurs
  - Infographies
  - Éléments visuels selon le contexte de l'article
- **CTAs stratégiques** : Ajoute des boutons de Call-To-Action pour convertir l'utilisateur
- **Ton ludique** : L'article doit être complet mais ludique et engageant
- **Lisibilité** : Utilise des paragraphes courts, listes à puces, citations

### CONTENU BRUT :
```
[INSÉRER ICI LE TEXTE BRUT DE L'ARTICLE]
```

---

## ✅ CRITÈRES DE VALIDATION

Le code généré doit être :
- ✅ **100% fonctionnel** : Aucune erreur console
- ✅ **Prêt pour intégration** : Copier-coller direct dans un bloc HTML WordPress
- ✅ **Testé mentalement** : Vérifier la logique de tous les scripts
- ✅ **Accessible** : Navigation au clavier, lecteurs d'écran
- ✅ **Performant** : Pas de ralentissements, animations optimisées
- ✅ **Sécurisé** : Pas de failles XSS ou injection

---

## 📦 LIVRABLES ATTENDUS

1. **Code HTML complet** : Un seul fichier HTML autonome
2. **Commentaires clairs** : Pour faciliter les modifications futures
3. **Structure organisée** :
   - Section HTML
   - Section CSS (dans `<style>`)
   - Section JavaScript (dans `<script>`)
4. **Instructions d'intégration** : Si nécessaire, en commentaire

---

## 🎯 OBJECTIF FINAL

Créer un article de blog professionnel, optimisé, accessible, et prêt à être intégré dans WordPress, qui :
- Informe et éduque le lecteur
- Convertit les visiteurs en prospects (via CTAs)
- Respecte les meilleures pratiques web (SEO, accessibilité, performance)
- Offre une expérience utilisateur exceptionnelle sur tous les appareils
```

---

## 📖 Instructions d'Utilisation

1. **Copier** tout le prompt ci-dessus
2. **Remplacer** `[MÉTIER]` par la thématique de votre article (ex: "plombier", "électricien", "développeur web")
3. **Insérer** le code HTML de votre template dans la section `[INSÉRER ICI LE CODE HTML DU TEMPLATE DE RÉFÉRENCE]`
4. **Insérer** le texte brut de votre article dans la section `[INSÉRER ICI LE TEXTE BRUT DE L'ARTICLE]`
5. **Soumettre** le prompt complet à Claude IA
6. **Récupérer** le code HTML généré
7. **Sauvegarder** le résultat dans `Article HTML généré/`

---

## 💡 Conseils

- **Soyez spécifique** : Plus vous donnez de détails sur le métier/thématique, meilleur sera le résultat
- **Vérifiez le template** : Assurez-vous que le template de référence est complet et fonctionnel
- **Testez localement** : Avant d'intégrer dans WordPress, testez le HTML dans un fichier local
- **Itérez si nécessaire** : N'hésitez pas à demander des ajustements à Claude IA

---

**Version** : 1.0
**Dernière mise à jour** : 2025-11-25
