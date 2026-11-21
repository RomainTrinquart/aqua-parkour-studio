# Aqua Parkour Studio

Prototype interactif 3D d'un parc de parkour aquatique sur lac, inspiré de captures d'une scène Blender. Le site combine une zone de parkour au sol, des pontons, des obstacles sur l'eau et une zone ludique.

## Ouvrir le prototype

Après activation de GitHub Pages (voir ci-dessous) : https://romaintrinquart.github.io/aqua-parkour-studio/

L'application est une page statique `index.html` utilisant **Three.js 0.160.1**, chargé en ligne depuis jsDelivr. Une connexion Internet et un navigateur compatible WebGL sont nécessaires.

## Fonctionnalités

- Vue 3D orbitale avec sélection de modules.
- Deux modes : **Caméra libre** et **Vue participant** (caméra positionnée 1,50 m au-dessus des modules aux points de passage).
- Points de passage déplaçables dans la liste, avec flèches haut et bas.
- Transitions participant simulées : course, saut, franchissement, rebond, plongeon.
- Prévisualisation du parcours, eau animée et export vidéo WebM si le navigateur le permet.
- Diagnostic de démarrage visible au centre de la scène, utile pour les appareils iOS.

## Activer GitHub Pages

1. Aller dans **Settings → Pages** du dépôt.
2. Dans **Build and deployment**, sélectionner **Deploy from a branch**.
3. Choisir la branche **main**, dossier **/(root)**, puis **Save**.
4. Lorsque la publication est effective, ouvrir l'URL ci-dessus dans **Safari** sur iPhone (pas dans l'aperçu HTML de ChatGPT).

Cette activation doit être faite depuis les paramètres GitHub du dépôt ; le simple ajout de `index.html` ne garantit pas que Pages soit déjà activé.

## Statut

Maquette conceptuelle reconstituée à partir de photographies de l'écran Blender. Les dimensions, zones de sol, profondeur d'eau et obstacles ne sont pas des plans techniques validés. Les mouvements sont des animations de caméra, **pas une simulation de sécurité ou de faisabilité physique**.

La prochaine étape sera d'importer des modules Blender exportés au format `.glb` et d'améliorer les déplacements tactiles sur iPhone.
