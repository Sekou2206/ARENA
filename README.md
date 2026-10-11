# SAUTI — THE ARENA

Prototype 3D WebGL immersif pour SAUTI, basé sur Three.js et les vidéos du site original.

## Démarrer

Les fichiers sont tous à la racine. Pour tester localement : `python3 -m http.server 8000` puis ouvrir http://localhost:8000.

Pour GitHub Pages, déposer tous les fichiers à la racine du dépôt, puis Settings > Pages > Deploy from a branch > main / root.

La connexion Internet est nécessaire pour charger Three.js et les polices via CDN. La scène 3D est procédurale : aucun modèle 3D externe requis.

## Contrôles

Molette : avancer dans le tunnel, puis se déplacer sur le terrain. Glisser : orienter le regard. Cliquer sur les écrans du tunnel : ouvrir une réalisation. Boutons de navigation : changer de zone. Flèches / ZQSD : déplacements simples.

## À améliorer pour une version finale premium

Remplacer les gradins procéduraux par un stade modélisé sous Blender avec textures PBR, améliorer l'éclairage et l'animation des supporters, ajouter des panneaux LED animés dédiés, développer une navigation libre WASD et joystick avec collisions, optimiser les médias et intégrer les vrais contacts validés de l'agence. Ce livrable est un prototype interactif, pas un rendu photoréaliste final.
