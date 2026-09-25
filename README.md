# Dofus Clicker

Clicker web dans l’univers de Dofus, inspiré de PokéClicker : tu cliques les monstres, tu farmes une zone, tu finis son donjon, puis tu descends (Incarnam → Astrub → ensuite Amakna).

## Lancer en local

Node n’est pas requis. À la racine du projet :

```bash
python -m http.server 4173
```

Puis ouvre [http://localhost:4173](http://localhost:4173).

Les modules ES ne s’ouvrent pas correctement en `file://` : il faut un petit serveur HTTP.

## Boucle de jeu (base)

- Clic = dégâts. Les familiers de l’atelier ajoutent des dégâts automatiques.
- XP + kamas sur chaque kill. L’atelier vend clic, auto et PV.
- Zone sauvage : quota de kills → débloque la suite et l'accès à la Crypte de Kardorim.
- Crypte de Kardorim : trois salles enchaînées, avec Kardorim en boss ; une mort relance le donjon.
- Sauvegarde automatique dans `localStorage`.
- Gestion de deux personnages maximum depuis l'onglet Personnages.
- Chaque personnage possède ses caractéristiques, son niveau de puissance et son inventaire (équipements, objets utilisables, ressources et objets de quête).
- Une montée de niveau accorde 5 points de caractéristiques ; les points peuvent être retirés et réattribués.
- Un personnage peut être supprimé depuis la petite poubelle de sa fiche, avec confirmation.
- Trois défis quotidiens proposent chaque jour des objectifs de combat, d'exploration ou de donjon, avec des récompenses en PX et kamas.

## Tests

Si Node.js est installé, lance les tests unitaires avec :

```bash
npm test
```

## Sprites

Voir [SPRITES.md](SPRITES.md). Les sprites d'Incarnam sont chargés depuis `assets/sprites/Incarnam/`.
