📝 Todo List App

Une application Todo List simple réalisée avec Angular pour pratiquer le développement frontend et la gestion de tâches.

L’application permet de créer, afficher, compléter et supprimer des tâches, avec une interface utilisateur réactive.

🌟 Fonctionnalités

Ajouter une nouvelle tâche

Marquer une tâche comme terminée

Supprimer une tâche

Interface simple et responsive

Stockage temporaire dans le frontend (local state)

💻 Technologies utilisées

Angular 17

TypeScript

HTML & CSS

Optionnel : Tailwind ou Bootstrap pour le style

🚀 Installation et lancement local

Cloner le dépôt :

git clone https://github.com/Monami2021/todo.git
cd todo


Installer les dépendances :

npm install


Lancer le serveur de développement :

ng serve


Ouvrir dans le navigateur :

http://localhost:4200

📦 Build pour production

Pour générer la version optimisée pour la production :

ng build --configuration production --base-href "/todo/"


Les fichiers seront générés dans :

dist/todo/browser

🌐 Déploiement sur GitHub Pages

Pour déployer l’application :

npx angular-cli-ghpages --dir=dist/todo/browser


L’application sera disponible à :

https://Monami2021.github.io/todo/

🛠 Structure du projet
todo/
├── src/
│   ├── app/
│   │   ├── components/  # Composants Angular
│   │   ├── services/    # Services Angular
│   │   └── app.module.ts
│   ├── assets/          # Images et styles
│   └── index.html
├── angular.json
├── package.json
└── README.md

📌 Remarques

Ce projet est destiné à l’apprentissage et à la pratique d’Angular.

Les données ne sont pas persistées après actualisation (pas de backend).

✨ Auteur

Monami Jerome
