# Portfolio Luckner JEAN - Data Analytics

Portfolio professionnel moderne avec mode sombre/clair, animations et design responsive.

## 📁 Structure des fichiers

```
portfolio/
│
├── index.html          # Page HTML principale
├── style.css           # Styles CSS
├── script.js           # JavaScript pour interactivité
├── profile.jpg         # Votre photo de profil
└── README.md          # Ce fichier
```

## 🚀 Installation dans VS Code

### Étape 1 : Créer le dossier du projet

1. Ouvrez VS Code
2. Créez un nouveau dossier appelé `portfolio`
3. Ouvrez ce dossier dans VS Code (Fichier > Ouvrir le dossier)

### Étape 2 : Créer les fichiers

Créez ces 3 fichiers dans votre dossier :

1. **index.html** - Copiez le contenu du fichier HTML
2. **style.css** - Copiez le contenu du fichier CSS
3. **script.js** - Copiez le contenu du fichier JavaScript

### Étape 3 : Ajouter votre photo

1. Ajoutez une photo de profil nommée `profile.jpg` dans le même dossier
2. Si vous utilisez un autre nom/format, modifiez la ligne dans `index.html` :
   ```html
   <img src="profile.jpg" alt="Luckner JEAN" class="profile-img">
   ```

### Étape 4 : Personnaliser les informations

#### Dans index.html, modifiez :

- **Section Contact** : Remplacez les liens email, LinkedIn, GitHub
  ```html
  <a href="mailto:vluckner.ljean@gmail.com">votre.email@example.com</a>
  <a href="https://www.linkedin.com/in/luckner-jean-285051152/">Luckner JEAN</a>
  <a href="https://github.com/JL-D24">@votre-profil</a>
  ```

- **Liens des projets** : Ajoutez les URLs de vos projets
  ```html
  <a href="#" class="project-link">Voir le projet →</a>
  ```

## 🎨 Fonctionnalités

### ✅ Déjà inclus :

- **Navigation fixe** avec liens vers les sections
- **Mode sombre/clair** avec bouton de bascule (🌙/☀️)
- **Design responsive** pour mobile, tablette et desktop
- **Animations au scroll** pour les cartes et sections
- **Menu mobile** avec hamburger
- **Formulaire de contact** (à connecter à un backend)
- **Effet parallaxe** sur la section hero
- **Compteur animé** pour les statistiques
- **Animation de frappe** pour le titre

### 🎯 Sections :

1. **Accueil** - Présentation et CTA
2. **À propos** - Bio et statistiques
3. **Compétences** - Technologies maîtrisées
4. **Services** - Ce que vous proposez
5. **Projets** - Portfolio de réalisations
6. **Expérience** - Timeline professionnelle
7. **Contact** - Formulaire et liens

## 🌐 Tester localement

### Option 1 : Extension Live Server (Recommandée)

1. Installez l'extension "Live Server" dans VS Code
2. Clic droit sur `index.html` > "Open with Live Server"
3. Le site s'ouvrira automatiquement dans votre navigateur

### Option 2 : Ouvrir directement

Double-cliquez sur `index.html` pour l'ouvrir dans votre navigateur par défaut.

## 🎨 Personnalisation des couleurs

Dans `style.css`, modifiez les variables CSS :

```css
:root {
    --primary-color: #4a9eff;      /* Couleur principale (bleu) */
    --secondary-color: #10b981;    /* Couleur secondaire (vert) */
    --bg-dark: #0a1628;            /* Fond sombre */
    --bg-light: #1a2744;           /* Fond clair */
}
```

## 📱 Responsive

Le site est entièrement responsive avec 3 breakpoints :

- **Desktop** : > 968px
- **Tablette** : 640px - 968px
- **Mobile** : < 640px

## 🚀 Déploiement

### GitHub Pages (Gratuit)

1. Créez un compte GitHub (si vous n'en avez pas)
2. Créez un nouveau repository appelé `username.github.io`
3. Uploadez vos fichiers (index.html, style.css, script.js, profile.jpg)
4. Activez GitHub Pages dans Settings
5. Votre site sera disponible à `https://username.github.io`

### Netlify (Gratuit)

1. Créez un compte sur [Netlify](https://netlify.com)
2. Glissez-déposez votre dossier `portfolio` sur Netlify
3. Votre site sera en ligne en quelques secondes !

### Vercel (Gratuit)

1. Créez un compte sur [Vercel](https://vercel.com)
2. Importez votre projet
3. Déployez en un clic

## 📧 Formulaire de contact

Le formulaire actuel affiche juste une alerte. Pour le rendre fonctionnel :

### Option 1 : Formspree (Gratuit)

1. Inscrivez-vous sur [Formspree](https://formspree.io)
2. Créez un formulaire et obtenez votre endpoint
3. Modifiez le `<form>` dans index.html :
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
   ```

### Option 2 : EmailJS

1. Inscrivez-vous sur [EmailJS](https://emailjs.com)
2. Configurez votre service email
3. Ajoutez le SDK EmailJS dans index.html

## 🛠️ Modifications courantes

### Changer la police

Dans `style.css`, modifiez la `font-family` :

```css
body {
    font-family: 'Roboto', -apple-system, BlinkMacSystemFont, sans-serif;
}
```

N'oubliez pas d'importer la police dans `<head>` de index.html :

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;700&display=swap" rel="stylesheet">
```

### Ajouter une section

1. Copiez une section existante dans index.html
2. Modifiez l'id et le contenu
3. Ajoutez le lien dans la navigation

## 🐛 Problèmes courants

**La photo ne s'affiche pas**
- Vérifiez que le fichier existe et est nommé correctement
- Vérifiez le chemin dans le `<img src="...">`

**Le JavaScript ne fonctionne pas**
- Ouvrez la console du navigateur (F12)
- Vérifiez les erreurs
- Assurez-vous que script.js est bien lié

**Le menu mobile ne s'ouvre pas**
- Vérifiez que script.js est bien chargé
- Vérifiez les IDs des éléments HTML

## 📞 Support

Pour toute question ou assistance, contactez-moi :
- Email : luckner.ljean@gmail.com
- LinkedIn : [Luckner JEAN](https://www.linkedin.com/in/luckner-jean-285051152/)

## 📄 Licence

Ce portfolio est libre d'utilisation pour votre usage personnel.

---

**Fait avec ❤️ par Luckner JEAN**
