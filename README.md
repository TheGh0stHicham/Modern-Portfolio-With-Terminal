# Portfolio Moderne avec Terminal Interactif Style macOS

Un portfolio web moderne et interactif avec un terminal style macOS qui permet aux visiteurs d'explorer vos compétences, projets et informations de manière ludique et originale.

![Aperçu du Portfolio]([https://via.placeholder.com/800x400?text=Portfolio+Preview](https://i.ibb.co/fZWBtg9/Screenshot-2025-05-06-112503.png))

## 🌟 Fonctionnalités

- **Design moderne et réactif** : s'adapte parfaitement à tous les appareils (desktop, tablette, mobile)
- **Terminal interactif style macOS** : permet aux visiteurs d'interagir de manière amusante avec votre portfolio
- **Commandes personnalisables** : whois, skills, projects, contact et plus encore
- **Easter eggs cachés** : commandes secrètes pour une expérience utilisateur amusante
- **Animations fluides** : animations au défilement pour une expérience immersive
- **Formulaire de contact** : permet aux visiteurs de vous contacter directement
- **Sections complètes** : expérience professionnelle, témoignages et formation

## 🚀 Commandes du Terminal

Le terminal interactif offre plusieurs commandes que les visiteurs peuvent utiliser :

- `help` : Affiche la liste des commandes disponibles
- `whois` : Affiche vos informations personnelles et votre profil
- `skills` : Liste vos compétences techniques et autres
- `projects` : Montre vos projets récents
- `project [nom]` : Affiche les détails d'un projet spécifique
- `contact` : Affiche vos coordonnées
- `clear` : Efface l'écran du terminal
- `ls` / `dir` : Liste les fichiers (affichage stylisé)
- `date` : Affiche la date et l'heure actuelles
- `echo [texte]` : Affiche le texte saisi

### Easter Eggs

Le terminal contient également des commandes cachées pour surprendre les visiteurs :
- `hello` / `hi` : Message d'accueil personnalisé
- `ping` : Répond "pong!"
- `sudo` : Message humoristique sur les droits d'administrateur
- `exit` : Tentative d'échapper au terminal
- `matrix` : Référence au film Matrix
- `coffee` : Offre un café virtuel ☕

## 📁 Structure du Projet

```
portfolio/
│
├── index.html          # Page principale du portfolio
│
├── css/                # Styles CSS (intégrés dans index.html pour ce projet)
│
├── js/                 # Scripts JavaScript (intégrés dans index.html pour ce projet)
│
└── images/             # Images et ressources (à ajouter selon vos besoins)
```

## 🔧 Personnalisation

### Informations Personnelles

1. Modifiez la section héro pour changer votre nom, photo de profil et description
2. Mettez à jour la commande `whois` dans le JavaScript pour afficher vos informations
3. Ajoutez vos compétences dans la commande `skills`
4. Ajoutez vos projets dans la commande `projects`
5. Mettez à jour l'adresse email dans la commande `contact` et dans le gestionnaire de formulaire

### Sections Supplémentaires

1. **Expérience** : Remplacez les éléments de la timeline par votre expérience professionnelle
2. **Témoignages** : Ajoutez vos propres témoignages de clients ou collaborateurs
3. **Formation** : Modifiez pour inclure votre parcours éducatif

### Styles et Couleurs

Vous pouvez facilement personnaliser les couleurs en modifiant les variables CSS dans la section `:root` :

```css
:root {
    --primary: #4B5FF7;    /* Couleur principale */
    --secondary: #FF4B91;  /* Couleur secondaire */
    --dark: #0F1730;       /* Couleur foncée (texte, fond) */
    --light: #F8F9FA;      /* Couleur claire (fond) */
    --terminal-bg: #1D2029; /* Fond du terminal */
    --terminal-text: #D8DEE9; /* Texte du terminal */
    /* Autres couleurs du terminal */
}
```

## 💻 Technologies Utilisées

- HTML5
- CSS3
- JavaScript (Vanilla)
- GSAP (pour les animations)
- Typed.js (pour les effets de frappe)
- Font Awesome (pour les icônes)

## 📧 Formulaire de Contact

Le formulaire de contact est configuré pour envoyer les messages à l'adresse email `test@gmail.com`. En production, vous devrez implémenter un backend pour traiter ces soumissions de formulaire.

Options de backend possibles :
- Service de formulaire comme Formspree ou Netlify Forms
- Script PHP personnalisé
- Service serverless comme AWS Lambda ou Vercel Functions

## 📱 Responsive Design

Le portfolio est entièrement responsive et s'adapte à tous les appareils :

- Desktop : Affichage complet, toutes les fonctionnalités
- Tablette : Layout adjusté, terminal redimensionné
- Mobile : Mise en page empilée, interface adaptée aux écrans tactiles

## 🚀 Déploiement

Pour déployer ce portfolio :

1. Clonez ce dépôt
2. Personnalisez le contenu selon vos besoins
3. Uploadez les fichiers sur votre hébergement web
4. Ou déployez sur des plateformes comme GitHub Pages, Netlify ou Vercel

## 🙏 Crédits

- Polices : Google Fonts (Poppins, Space Mono)
- Icônes : Font Awesome
- Animations : GSAP & ScrollTrigger
- Effet de frappe : Typed.js

---

Créé avec ❤️ par [Hicham Ezzamzami]
