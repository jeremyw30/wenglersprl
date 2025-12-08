# 📝 Mémo - Commandes Utiles

## 🚀 Serveur Symfony

### Démarrer le serveur
```bash
symfony server:start
```

### Démarrer en arrière-plan
```bash
symfony server:start -d
```

### Arrêter le serveur
```bash
symfony server:stop
```

### Alternative sans Symfony CLI
```bash
php -S localhost:8000 -t public/
```

---

## 🎨 Webpack Encore (Assets)

### Mode développement avec watch (recompile automatiquement)
```bash
npm run watch
```

### Build de développement (une seule fois)
```bash
npm run dev
```

### Build de production (optimisé)
```bash
npm run build
```

---

## 📦 Composer (PHP)

### Installer les dépendances
```bash
composer install
```

### Mettre à jour les dépendances
```bash
composer update
```

### Ajouter un package
```bash
composer require nom/du-package
```

### Ajouter un package de dev
```bash
composer require --dev nom/du-package
```

---

## 📦 NPM (JavaScript)

### Installer les dépendances
```bash
npm install
```

### Ajouter un package
```bash
npm install nom-du-package
```

### Ajouter un package de dev
```bash
npm install nom-du-package --save-dev
```

---

## 🗄️ Base de données

### Créer la base de données
```bash
php bin/console doctrine:database:create
```

### Créer une migration
```bash
php bin/console make:migration
```

### Exécuter les migrations
```bash
php bin/console doctrine:migrations:migrate
```

### Supprimer la base de données
```bash
php bin/console doctrine:database:drop --force
```

---

## 🛠️ Génération de code (Maker)

### Créer un contrôleur
```bash
php bin/console make:controller NomController
```

### Créer une entité (modèle)
```bash
php bin/console make:entity NomEntite
```

### Créer un formulaire
```bash
php bin/console make:form
```

### Créer un CRUD complet
```bash
php bin/console make:crud NomEntite
```

### Créer un utilisateur
```bash
php bin/console make:user
```

### Créer l'authentification
```bash
php bin/console make:auth
```

---

## 🧹 Cache et maintenance

### Vider le cache
```bash
php bin/console cache:clear
```

### Vider le cache de production
```bash
php bin/console cache:clear --env=prod
```

### Réchauffer le cache
```bash
php bin/console cache:warmup
```

---

## 🔍 Debug et infos

### Lister toutes les routes
```bash
php bin/console debug:router
```

### Voir les détails d'une route
```bash
php bin/console debug:router nom_de_la_route
```

### Lister les services
```bash
php bin/console debug:container
```

### Lister les variables d'environnement
```bash
php bin/console debug:dotenv
```

### Voir la configuration
```bash
php bin/console debug:config
```

---

## 🎯 AssetMapper (si besoin)

### Ajouter un package JavaScript
```bash
php bin/console importmap:require nom-du-package
```

### Compiler les assets
```bash
php bin/console asset-map:compile
```

---

## 🔐 Git (via terminal)

### Voir le statut
```bash
git status
```

### Ajouter tous les fichiers
```bash
git add .
```

### Faire un commit
```bash
git commit -m "Message du commit"
```

### Pousser vers GitHub
```bash
git push
```

### Tirer les dernières modifications
```bash
git pull
```

### Créer une nouvelle branche
```bash
git checkout -b nom-de-la-branche
```

---

## 🧪 Tests

### Lancer tous les tests
```bash
php bin/phpunit
```

### Lancer un test spécifique
```bash
php bin/phpunit tests/Chemin/VersTest.php
```

---

## 🌐 Liens utiles

- **Serveur local** : http://localhost:8000
- **Documentation Symfony** : https://symfony.com/doc
- **Documentation Bootstrap** : https://getbootstrap.com/docs
- **Votre GitHub** : https://github.com/jeremyw30/wenglersprl

---

## 📌 Raccourcis PowerShell

### Lancer serveur + watch en même temps
```powershell
# Terminal 1
symfony server:start

# Terminal 2
npm run watch
```
