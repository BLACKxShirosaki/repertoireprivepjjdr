# Chroniques — Répertoire de personnages de JDR

Site statique autonome, prêt pour GitHub Pages. Aucun paquet à installer, aucune compilation et aucune clé API.

## Contenu

- `index.html` : structure de la page et formulaires.
- `styles.css` : mise en page, sept thèmes et typographies.
- `app.js` : création, édition, affichage et sauvegarde des fiches.
- `assets/images/` : sept illustrations WebP, chacune contenant les deux décors d’un univers.
- `.nojekyll` : indique un site statique sans traitement Jekyll.

## Mise en ligne

1. Décompresser l’archive sur ton ordinateur.
2. Déposer le contenu du dossier dans ton dépôt GitHub en conservant les sous-dossiers. `index.html` doit être à la racine du dossier publié.
3. Dans les réglages du dépôt, ouvrir **Pages**, choisir la publication depuis une branche, puis la branche contenant les fichiers et son dossier racine.
4. Ouvrir l’adresse proposée par GitHub une fois la publication terminée.

Les chemins sont relatifs : le site fonctionne aussi sous une adresse de type `https://utilisateur.github.io/nom-du-depot/`.

## Tes données

Avant de quitter l’ancienne version, exporter la sauvegarde JSON, puis l’importer dans la version hébergée. Le stockage local ne se transfère pas automatiquement d’une adresse à une autre.

Les fiches restent dans le navigateur : elles ne sont ni envoyées ni enregistrées dans GitHub. Chaque visiteur possède ses propres données. Pour présenter tes personnages à d’autres personnes avec des fiches préremplies, il faudra ajouter une fonction de publication des données.

Exporter régulièrement une sauvegarde JSON. Les illustrations intégrées au projet ne consomment pas l’espace de sauvegarde locale. Les portraits et images de fiches importés y sont enregistrés et restent soumis à la capacité du navigateur.

## Images et polices

Les décors sont chargés depuis `assets/images/` et mis en cache par le navigateur. Les polices Google Fonts nécessitent Internet ; des polices de secours sont prévues. Un nouvel univers reprend les décors et la typographie de son thème de départ.

Les illustrations ont été générées pour ce projet puis encodées en WebP. Pour les remplacer, conserver les noms de fichiers et la composition en deux panneaux superposés : en-tête en haut, bas du menu en bas (format 1536 × 1024, panneaux de 1536 × 512).

## Essai local

Ouvrir `index.html` en conservant tout le dossier. Pour tester dans un serveur local, lancer `python -m http.server 8000` depuis ce dossier, puis ouvrir `http://localhost:8000`.
