# Twitcher Francia — version SQLite à plat

Tous les fichiers du projet sont à la racine : `index.html`, `app.js`, `logo.jpeg`, `server.js`, `package.json`, `vite.config.js`, `.env.example` et `.gitignore`.

## Lancer en local
1. Installer Node.js 20 ou plus récent.
2. Dans ce dossier, exécuter `npm install`.
3. Exécuter `npm run build`.
4. Exécuter `npm start`.
5. Ouvrir `http://localhost:3000`.

Le serveur crée automatiquement `data/sauvegarde.db` et `data/uploads/` au premier démarrage. Ces dossiers sont des données générées à l'exécution, pas des dossiers de code à importer. Garder le disque persistant de l'hébergeur activé pour ne pas perdre la base et les médias.

Copier `.env.example` vers `.env` pour la configuration locale. Ne jamais publier `.env` ni les secrets.
