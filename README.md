# FREHEALTH - Site Web

Site web de présentation pour FREHEALTH, une solution de santé accessible et gratuite pour tous.

## 🎨 Direction Artistique

Le site transmet **confiance, sérieux médical et accessibilité**, sans jamais paraître médical froid ni commercial agressif. L'objectif est de rassurer les investisseurs tout en restant compréhensible et motivant pour le grand public.

### Identité visuelle
- **Style** : Moderne, épuré, humain
- **Palette** : Vert santé (#4CAF50), blanc, gris clair, touches de bleu (#2196F3)
- **Typographie** : Inter (sans-serif), professionnelle, hiérarchie claire

### Structure
- Landing page unique avec sections :
  - Hero section avec slogan
  - Présentation du problème
  - Solution FREHEALTH
  - Pourquoi c'est gratuit
  - Pourquoi investir
  - Équipe / Experts
  - Appel à l'action (soutien, contact, Leetchi)

## 🚀 Installation

Aucune installation nécessaire ! Le site est statique et peut être ouvert directement dans un navigateur.

### Option 1 : Ouvrir directement
Double-cliquez sur `index.html` pour l'ouvrir dans votre navigateur.

### Option 2 : Serveur local (recommandé)
Pour un meilleur développement, utilisez un serveur local :

```bash
# Avec Python
python -m http.server 8000

# Avec Node.js (si vous avez http-server installé)
npx http-server

# Avec PHP
php -S localhost:8000
```

Puis ouvrez `http://localhost:8000` dans votre navigateur.

## 📁 Structure des fichiers

```
cejm-frehealth/
├── index.html      # Structure HTML de la landing page
├── styles.css      # Styles CSS avec palette de couleurs
├── script.js       # JavaScript pour navigation et interactions
└── README.md       # Documentation du projet
```

## 🎯 Fonctionnalités

- ✅ Navigation fluide avec scroll smooth
- ✅ Menu mobile responsive
- ✅ Animations au scroll
- ✅ Design responsive (mobile-first)
- ✅ Sections claires et aérées
- ✅ Appels à l'action visibles

## 📱 Responsive Design

Le site est entièrement responsive et optimisé pour :
- Mobile (< 480px)
- Tablette (480px - 768px)
- Desktop (> 768px)

## 🎨 Personnalisation

### Couleurs
Les couleurs sont définies dans `styles.css` via les variables CSS :
- `--green-primary` : Vert principal (#4CAF50)
- `--blue-primary` : Bleu pour crédibilité médicale (#2196F3)
- `--white`, `--gray-light`, etc.

### Contenu
Modifiez le contenu directement dans `index.html` :
- Remplacez les placeholders `[Nom]` dans la section équipe
- Ajoutez le lien Leetchi dans le bouton "Soutenir sur Leetchi"
- Personnalisez les textes selon vos besoins

## 🔗 Liens à configurer

N'oubliez pas de remplacer les liens suivants :
- Lien Leetchi : `href="#"` dans le bouton "Soutenir sur Leetchi"
- Email de contact : `mailto:contact@frehealth.fr` (modifiez si nécessaire)

## 📝 Notes

- Les images sont actuellement des placeholders SVG. Remplacez-les par de vraies images si nécessaire.
- La typographie utilise Google Fonts (Inter). Une connexion internet est nécessaire pour charger la police.
- Le site est optimisé pour le SEO avec des balises meta appropriées.

## 🌐 Compatibilité

Testé et compatible avec :
- Chrome/Edge (dernières versions)
- Firefox (dernières versions)
- Safari (dernières versions)
- Navigateurs mobiles (iOS Safari, Chrome Mobile)

## 📄 Licence

© 2024 FREHEALTH. Tous droits réservés.

