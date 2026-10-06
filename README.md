# BE STRONGER — Espace Coach

Application web autonome pour gérer des fiches clients, suivre les séances et les performances, et utiliser des timers d'entraînement.

## Lancer l'application

Ouvrir `index.html` dans un navigateur récent. Aucune installation n'est nécessaire.

## Données et sauvegardes

Les fiches sont conservées dans le stockage local du navigateur (`localStorage`). Elles restent sur l'appareil et le profil de navigateur utilisés. Depuis l'onglet **Clients**, exporter régulièrement une sauvegarde JSON. La restauration remplace les données présentes.

## Publier avec GitHub Pages

1. Créer un dépôt GitHub nommé `be-stronger`.
2. Ajouter `index.html` et ce `README.md` à la racine du dépôt.
3. Dans **Settings → Pages**, choisir **Deploy from a branch**, la branche `main` et le dossier `/ (root)`.
4. Enregistrer : GitHub Pages affichera l'adresse publique du site après le déploiement.

> Les données stockées dans le navigateur ne sont pas synchronisées entre appareils. Ne pas publier de données client dans le dépôt.

## Personnaliser un programme

Dans l’onglet **Programme**, sélectionne un client pour ajouter, renommer ou supprimer ses séances et exercices. Les plans existants gardent le programme par défaut tant qu’ils ne sont pas personnalisés. Les données de progression d’un élément supprimé sont retirées avec lui.
