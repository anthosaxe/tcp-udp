# 🌐 Protocoles TCP et UDP - Site de Présentation

[Le site](https://anthosaxe.github.io/tcp-udp/)

Un site web statique responsive et interactif pour comprendre les protocoles de communication réseau TCP et UDP.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 📋 Table des matières

- [Aperçu](#aperçu)
- [Fonctionnalités](#fonctionnalités)
- [Structure du projet](#structure-du-projet)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Technologies utilisées](#technologies-utilisées)
- [Captures d'écran](#captures-décran)
- [Contribuer](#contribuer)
- [Licence](#licence)

## 🎯 Aperçu

Ce projet est un site web éducatif multipage qui présente de manière claire et visuelle les deux principaux protocoles de la couche transport : **TCP** (Transmission Control Protocol) et **UDP** (User Datagram Protocol).

Le site est conçu pour être :
- 📱 **Responsive** : S'adapte à tous les types d'écrans (mobile, tablette, desktop)
- 🎨 **Moderne** : Design épuré avec Tailwind CSS
- ⚡ **Léger** : Aucune dépendance externe lourde
- 📚 **Pédagogique** : Contenu structuré et facile à comprendre

## ✨ Fonctionnalités

### Navigation fluide
- Menu de navigation sticky
- Menu hamburger responsive pour mobile
- Liens entre toutes les pages
- Animations au scroll

### Contenu riche
- **Page d'accueil** : Introduction aux protocoles de communication
- **Page TCP** : Caractéristiques détaillées, Three-Way Handshake, cas d'usage
- **Page UDP** : Structure du datagramme, avantages, applications
- **Page Comparaison** : Tableau comparatif, arbre de décision, conclusion

### Design interactif
- Cartes avec effets hover
- Animations d'apparition progressives
- Code couleur thématique (bleu pour TCP, vert pour UDP)
- Sections visuellement distinctes

## 📁 Structure du projet

```
tcp-udp-presentation/
│
├── index.html           # Page d'accueil - Introduction aux protocoles
├── tcp.html            # Page dédiée au protocole TCP
├── udp.html            # Page dédiée au protocole UDP
├── comparaison.html    # Page de comparaison et conclusion
│
└── README.md           # Documentation du projet
```

## 🚀 Installation

### Prérequis
Aucun prérequis particulier ! Le projet utilise uniquement du HTML, CSS et JavaScript vanilla.

### Étapes d'installation

1. **Cloner le repository**
   ```bash
   git clone https://github.com/anthosaxe/tcp-udp-presentation.git
   cd tcp-udp-presentation
   ```

2. **Ouvrir le site**
   
   Simplement ouvrir `index.html` dans votre navigateur :
   ```bash
   # Sur Linux/Mac
   open index.html
   
   # Sur Windows
   start index.html
   ```

   Ou utiliser un serveur local (recommandé) :
   ```bash
   # Avec Python 3
   python -m http.server 8000
   
   # Avec Node.js (http-server)
   npx http-server
   ```

   Puis accéder à `http://localhost:8000`

## 💻 Utilisation

### Navigation
- Utilisez le menu principal pour naviguer entre les sections
- Sur mobile, cliquez sur l'icône hamburger pour ouvrir le menu
- Les liens dans le footer permettent également de naviguer rapidement

### Personnalisation
Le site utilise **Tailwind CSS via CDN**, ce qui permet une personnalisation facile :

1. **Modifier les couleurs** : Changez les classes `bg-blue-*`, `text-green-*`, etc.
2. **Ajuster le contenu** : Éditez le texte entre les balises HTML
3. **Ajouter des sections** : Copiez/collez une section existante et modifiez-la

### Ajout d'images
Pour ajouter vos propres schémas et diagrammes :
1. Créez un dossier `images/` ou `media/`
2. Ajoutez vos images
3. Insérez-les dans le HTML avec des balises `<img>`

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Styles personnalisés et animations
- **JavaScript (Vanilla)** : Interactivité (menu mobile, animations scroll)
- **Tailwind CSS** : Framework CSS utility-first (via CDN)

### Tailwind CSS
Le projet utilise Tailwind CSS version CDN pour :
- Grid et Flexbox responsive
- Système de couleurs cohérent
- Utilitaires de spacing et typography
- Classes d'animation

**Sur TCP :**
- Fonctionnement du Three-Way Handshake
- Mécanismes de fiabilité et d'ordre
- Contrôle de flux et de congestion
- Cas d'usage typiques

**Sur UDP :**
- Architecture sans connexion
- Structure du datagramme (8 octets)
- Avantages pour les applications temps réel
- Utilisation dans le streaming et les jeux

**Comparaison :**
- Tableau comparatif détaillé
- Arbre de décision pour choisir le bon protocole
- Exemples concrets d'applications
