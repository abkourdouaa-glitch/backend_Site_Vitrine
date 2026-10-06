Site Vitrine ISAG - Backend

Backend Laravel du site vitrine du centre ISAG (présentation des formations, actualités et services, et communication avec les étudiants et visiteurs).

Le frontend (React.js) est ici : https://github.com/abkourdouaa-glitch/Site_Vitrine

Rôle du backend
Gestion des routes et de la logique côté serveur
Fourniture des données au frontend via l'API
Base de données gérée avec les migrations Laravel
Technologies
PHP / Laravel
MySQL
Git et GitHub

Installation
# 1. Cloner le dépôt
git clone https://github.com/abkourdouaa-glitch/backend_Site_Vitrine.git
cd backend_Site_Vitrine

# 2. Installer les dépendances
composer install

# 3. Configurer l'environnement
cp .env.example .env
php artisan key:generate
