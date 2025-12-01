# 💭 Citations Inspirantes

Une application web moderne développée avec Symfony pour partager et découvrir des citations inspirantes au quotidien.

![PHP](https://img.shields.io/badge/PHP-8.4-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-8.0-000000?style=for-the-badge&logo=symfony&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

## 🌟 Fonctionnalités

- **📚 Citation aléatoire** : Découvrez une nouvelle source d'inspiration à chaque visite
- **📋 Collection complète** : Parcourez toutes les citations disponibles
- **✍️ Contribution** : Ajoutez vos propres citations pour enrichir la communauté
- **🎨 Design responsive** : Interface moderne optimisée pour tous les appareils
- **🧭 Navigation intuitive** : Navbar moderne avec indication de page active

## 🚀 Démo

L'application propose plusieurs sections :

- **🏠 Accueil** : Page d'accueil avec hero section et statistiques
- **📖 Citations** : Liste complète de toutes les citations
- **➕ Ajouter** : Formulaire pour contribuer avec de nouvelles citations
- **ℹ️ À propos** : Informations sur le projet et les technologies

## 🛠 Technologies utilisées

- **Backend** : PHP 8.4 + Symfony 8.0
- **Template** : Twig
- **Frontend** : CSS3 avec design moderne (gradients, glassmorphism)
- **Base de données** : Aucune (stockage en mémoire pour ce projet de démonstration)

## 📦 Installation

### Prérequis

- PHP 8.4 ou supérieur
- Composer
- Git

### Étapes d'installation

1. **Cloner le repository**
   ```bash
   git clone https://github.com/HrexD/CreationInspirantes.git
   cd CreationInspirantes
   ```

2. **Installer les dépendances**
   ```bash
   composer install
   ```

3. **Configurer l'environnement**
   ```bash
   cp .env .env.local
   # Éditer .env.local si nécessaire
   ```

4. **Lancer le serveur de développement**
   ```bash
   # Option 1 : Serveur PHP intégré
   php -S localhost:8000 -t public
   
   # Option 2 : Symfony CLI (si installé)
   symfony serve
   ```

5. **Accéder à l'application**
   
   Ouvrez votre navigateur et rendez-vous sur `http://localhost:8000`

## 🎨 Aperçu du design

L'application utilise un design moderne avec :

- **Palette de couleurs** : Dégradés bleu/violet harmonieux
- **Typographie** : Segoe UI pour une lisibilité optimale
- **Effets visuels** : Glassmorphism, ombres et animations fluides
- **Responsive design** : Adaptation automatique à tous les écrans
- **Icônes** : Emojis expressifs pour une interface ludique

### Principales sections

- **Hero Section** : Titre impactant avec call-to-action
- **Citation du jour** : Mise en valeur avec guillemets décoratifs
- **Statistiques** : Cartes avec métriques importantes
- **Fonctionnalités** : Présentation des avantages clés

## 🗂 Structure du projet

```
├── assets/
│   └── styles/
│       └── app.css          # Styles CSS principaux
├── config/
│   └── routes.yaml          # Configuration des routes
├── public/
│   └── index.php           # Point d'entrée
├── src/
│   └── Controller/
│       └── QuoteController.php  # Contrôleur principal
├── templates/
│   ├── base.html.twig      # Template de base
│   └── quote/
│       ├── home.html.twig   # Page d'accueil
│       ├── list.html.twig   # Liste des citations
│       ├── add.html.twig    # Formulaire d'ajout
│       └── about.html.twig  # Page à propos
└── var/                    # Cache et logs
```

## 🚦 Routes disponibles

| Route | URL | Description |
|-------|-----|-------------|
| `app_home` | `/` | Page d'accueil |
| `app_quotes` | `/quotes` | Liste des citations |
| `app_add_quote` | `/add` | Ajouter une citation |
| `app_about` | `/about` | À propos |

## 🎯 Utilisation

### Consulter les citations

- **Page d'accueil** : Découvrez une citation aléatoire
- **Section Citations** : Parcourez toute la collection

### Ajouter une citation

1. Cliquez sur "➕ Ajouter" dans la navigation
2. Saisissez votre citation dans le formulaire
3. Cliquez sur "✨ Publier la citation"

### Navigation

La navbar moderne indique la page active et permet une navigation fluide entre les sections.

## 🛡 Sécurité

Le projet inclut des protections basiques :
- Validation des formulaires
- Échappement automatique des templates Twig
- Configuration sécurisée par défaut de Symfony

## 🔧 Développement

### Commandes utiles

```bash
# Vider le cache
php bin/console cache:clear

# Lister les routes
php bin/console debug:router

# Analyser le projet
composer install --dev
```

### Structure CSS

Le CSS est organisé en sections claires :
- Reset et base
- Navbar
- Sections principales (Hero, Stats, Features, etc.)
- Composants (boutons, cartes, etc.)
- Responsive design

## 🤝 Contribution

Les contributions sont les bienvenues ! Pour contribuer :

1. Forkez le projet
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/nouvelle-fonctionnalite`)
3. Commitez vos changements (`git commit -m 'Ajout d'une nouvelle fonctionnalité'`)
4. Poussez vers la branche (`git push origin feature/nouvelle-fonctionnalite`)
5. Ouvrez une Pull Request

## 📝 License

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👨‍💻 Auteur

**HrexD** - *Développement initial*

## 🙏 Remerciements

- [Symfony](https://symfony.com/) pour le framework robuste
- [Twig](https://twig.symfony.com/) pour le moteur de templates
- La communauté open source pour l'inspiration

---

⭐ N'hésitez pas à mettre une étoile si ce projet vous plaît !
