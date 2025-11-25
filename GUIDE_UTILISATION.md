# 🚀 Guide d'Utilisation Rapide

Guide pratique pour générer vos articles HTML en quelques étapes simples.

## 📖 Utilisation en 5 Étapes

### 1️⃣ Préparer votre Article Brut

1. Rédigez votre article sur Google Docs (ou autre)
2. Copiez le texte complet
3. Créez un nouveau fichier dans `Article Brut/`
4. Nommez-le : `[date]-[titre-court].txt`
5. Collez et sauvegardez

**Exemple** : `2024-11-25-choisir-artisan.txt`

---

### 2️⃣ Choisir un Template

1. Allez dans le dossier `Template/`
2. Choisissez le template qui correspond le mieux à votre article
3. Ouvrez-le et copiez **tout le code HTML**

**Templates disponibles** :
- `template-article-base.html` : Template de base polyvalent

---

### 3️⃣ Préparer le Prompt

1. Ouvrez le fichier `PROMPT_TEMPLATE.md`
2. Copiez **tout le contenu**
3. Remplacez les éléments suivants :

#### À Remplacer :

**a) `[MÉTIER]`**
```
Exemple : "plombier" ou "électricien" ou "développeur web"
```

**b) `[INSÉRER ICI LE CODE HTML DU TEMPLATE DE RÉFÉRENCE]`**
```
Collez ici le code complet du template choisi à l'étape 2
```

**c) `[INSÉRER ICI LE TEXTE BRUT DE L'ARTICLE]`**
```
Collez ici le contenu de votre article brut de l'étape 1
```

---

### 4️⃣ Générer avec Claude IA

1. Ouvrez Claude IA (https://claude.ai)
2. Collez le prompt complet préparé à l'étape 3
3. Envoyez
4. Attendez que Claude génère le code HTML complet
5. Copiez le code HTML généré

---

### 5️⃣ Sauvegarder et Intégrer

1. Créez un nouveau fichier dans `Article HTML généré/`
2. Nommez-le : `[date]-[titre-court].html`
3. Collez le code HTML généré
4. Sauvegardez

**Dans WordPress** :
1. Créez une nouvelle page/article
2. Ajoutez un bloc "HTML personnalisé"
3. Collez le code HTML
4. Prévisualiser et publier !

---

## ⚡ Checklist Rapide

Avant de publier dans WordPress, vérifiez :

- [ ] Le H1 (titre principal) est unique et correct
- [ ] Le sommaire fonctionne (cliquez sur les liens)
- [ ] Le formulaire de contact s'affiche
- [ ] Les CTAs (boutons) sont visibles
- [ ] Le design est responsive (testez sur mobile)
- [ ] Aucune erreur dans la console du navigateur

---

## 🎯 Personnalisation EmailJS

**Important** : Avant d'utiliser le formulaire de contact, vous devez configurer EmailJS.

### Configuration initiale :

1. Créez un compte sur [EmailJS](https://www.emailjs.com/)
2. Créez un service email
3. Créez un template d'email
4. Récupérez votre clé publique (Public Key)

### Dans le template HTML :

Remplacez dans la section JavaScript :

```javascript
emailjs.init('YOUR_PUBLIC_KEY'); // Remplacer par votre clé

// Et dans sendForm :
emailjs.sendForm('service_btbtgzn', 'template_m06wtf1', contactForm)
```

**Valeurs à remplacer** :
- `YOUR_PUBLIC_KEY` : Votre clé publique EmailJS
- `service_btbtgzn` : Votre Service ID
- `template_m06wtf1` : Votre Template ID

---

## 💡 Astuces Pro

### Pour enrichir vos articles :

Dans votre texte brut, ajoutez des annotations pour guider Claude :

```
[IMAGE: Description de l'image souhaitée]
[SIMULATEUR: Type de calculateur souhaité]
[CTA: Texte du call-to-action]
[ENCADRÉ: Conseil expert à mettre en avant]
[LISTE: Points à mettre en forme]
```

### Pour des CTAs efficaces :

Placez des CTAs :
- Après l'introduction
- Au milieu de l'article
- Avant la conclusion
- Dans le formulaire de contact

### Pour le SEO :

- Utilisez des mots-clés naturellement dans votre texte brut
- Structurez avec des H2, H3 (titres, sous-titres)
- Ajoutez des listes à puces
- Incluez des questions fréquentes

---

## 🆘 Problèmes Fréquents

### Le formulaire ne fonctionne pas
➡️ Vérifiez la configuration EmailJS (clés, service ID, template ID)

### L'article n'est pas responsive
➡️ Le template de base est déjà responsive. Si vous avez modifié le CSS, vérifiez les media queries.

### Les animations ne fonctionnent pas
➡️ Vérifiez qu'il n'y a pas de conflit avec votre thème WordPress.

### Le sommaire ne fonctionne pas
➡️ Assurez-vous que les IDs des sections correspondent aux liens du sommaire.

---

## 📞 Support

Des questions ? Besoin d'aide ?
- Email : contact.capitainepub@gmail.com
- Consultez le README.md pour plus de détails

---

**Bon développement ! 🚀**
