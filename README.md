# 📰 Le Journal du Lundi

Un site web moderne et responsive pour un journal en ligne, conçu avec HTML5 et CSS3. Ce projet présente une interface élégante et professionnelle pour la lecture d'articles de presse.

## 🚀 Fonctionnalités

- **Design responsive** : Adaptation automatique aux écrans desktop et mobile
- **Navigation intuitive** : Menu de navigation clair avec catégories (Tech, Mode, Politique, Social, Boutique, Blog)
- **Section showcase** : Mise en avant des articles principaux avec images et métadonnées
- **Section publicité** : Zone dédiée aux annonces et inscriptions
- **Articles organisés** : Contenu structuré par catégories avec images et descriptions
- **Section populaire** : Classement des articles les plus lus
- **Authentification** : Système de connexion et d'inscription pour les membres

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique et accessible
- **CSS3** : Styles modernes avec variables CSS et Flexbox/Grid
- **Responsive Design** : Media queries pour l'adaptation mobile
- **Font Awesome** : Icônes vectorielles
- **Google Fonts** : Typographies Cormorant Garamond et Staatliches

## 📁 Structure du projet

```
Medium/
├── css/
│   ├── style.css          # Styles principaux
│   └── style.mobile.css   # Styles pour mobile
├── img/
│   └── img/               # Images des articles
├── index.html             # Page principale
└── README.md              # Documentation du projet
```

## 🎨 Design et UX

### Palette de couleurs
- **Primaire** : `#be2529` (Rouge)
- **Secondaire** : `#0d0d0d` (Noir profond)
- **Ténèbres** : `#333` (Gris foncé)
- **Gris** : `#ddd` (Gris clair)
- **Gris clair** : `#eee` (Gris très clair)
- **Gris indice** : `#555` (Gris moyen)

### Typographie
- **Corps de texte** : Cormorant Garamond (serif)
- **Titres** : Staatliches (cursive)
- **Hiérarchie** : Tailles de police adaptatives (1.6rem à 3rem)

## 📱 Responsive Design

Le site s'adapte automatiquement aux différentes tailles d'écran :

- **Desktop** : Layout en grille avec sidebar et contenu principal
- **Mobile** : Layout en colonne unique avec navigation adaptée
- **Breakpoint** : 700px pour la transition mobile/desktop

### Adaptations mobile
- Navigation en colonne
- Articles empilés verticalement
- Section populaire masquée
- Formulaire d'inscription optimisé
- Logo redimensionné

## 🚀 Installation et utilisation

1. **Cloner le projet**
   ```bash
   git clone [url-du-repo]
   cd Medium
   ```

2. **Ouvrir dans un navigateur**
   - Double-cliquer sur `index.html`
   - Ou ouvrir avec un serveur local

3. **Développement**
   - Modifier `css/style.css` pour les styles principaux
   - Modifier `css/style.mobile.css` pour les styles mobile
   - Tester la responsivité en redimensionnant la fenêtre

## 📝 Structure HTML

### Header
- Logo du journal
- Menu de navigation utilisateur
- Boutons de connexion/inscription

### Navigation
- Catégories principales
- Liens vers les sections

### Showcase
- Article principal en vedette
- Articles secondaires avec images
- Métadonnées (auteur, temps de lecture)

### Publicité
- Section d'inscription à la newsletter
- Formulaire avec validation

### Contenu principal
- Articles organisés par catégories
- Section des articles populaires
- Images et descriptions

## 🎯 Fonctionnalités à venir

- [ ] Système de recherche d'articles
- [ ] Pagination des articles
- [ ] Système de commentaires
- [ ] Partage sur les réseaux sociaux
- [ ] Mode sombre/clair
- [ ] Filtres par catégorie
- [ ] Système de favoris


## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👨‍💻 Auteur

Développé dans le cadre de la formation Dyma - HTML & CSS

---

**Note** : Ce projet est une démonstration de design web moderne et responsive. Les articles et images sont des exemples et ne représentent pas de contenu réel.
