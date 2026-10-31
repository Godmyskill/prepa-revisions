# Prépa · Mes révisions

Application de révision pour ordinateur et iPhone : physique, chimie et anglais.

- 153 cartes de thermodynamique, avec formules et liens vers 108 pages sources.
- 18 familles chimiques, schémas et fiche source.
- 150 verbes anglais, variantes, notes et 300 fichiers audio.
- Révision, recherche, flashcards par matière et chapitre, mélanges sans répétition, reprise des erreurs.
- Téléchargement des ressources pour réviser hors connexion.

## Utilisation sur iPhone

Ouvrir le site dans Safari, puis **Partager → Sur l’écran d’accueil → Ajouter**. Ouvrir l’application depuis l’icône, aller dans **Hors connexion**, télécharger tout et attendre le message de fin. Avant de partir, vérifier en mode avion une carte, une page source et un son. iOS peut libérer les données stockées : vérifier avant les trajets.

La progression est locale à chaque navigateur. Export et import permettent une sauvegarde et un transfert manuel ; aucune synchronisation automatique n’est activée. Lors d’un changement d’adresse du site, exporter la progression depuis l’ancienne adresse, puis importer dans la nouvelle.

## Hébergement GitHub Pages

Dans les réglages du dépôt : **Pages → Deploy from a branch → main → / (root)**. Le fichier `.nojekyll` permet de servir directement les fichiers statiques. Aucun outil de compilation n’est nécessaire. Tous les chemins sont relatifs pour fonctionner dans un sous-dossier GitHub Pages.

## Modification

Les données se trouvent dans `content.json`, les documents dans `documents.json` et `pages/`, les formules dans `math/` et les sons dans `audio/`. L’interface est dans `index.html`, `style.css` et `app.js`.

Après modification, augmenter la version de cache dans `sw.js`. Mettre à jour `assets.json` si les ressources changent. Publier les fichiers modifiés ; une mise à jour s’active depuis l’application à la demande de l’utilisateur.

Les cours ont été repris des applications d’origine, sans ajout de contenu pédagogique inventé. Les chapitres 2 et 6 de physique sont identifiés comme compléments du polycopié. Les documents présents sont consultables publiquement dans ce dépôt ; aucune licence générale de réutilisation n’est accordée sur les cours de tiers.
