# Dofus Clicker — sprites

Le jeu charge les sprites selon leur chemin déclaré dans les données. Les créatures d'Incarnam utilisent `assets/sprites/Incarnam/`. S’il n’y a pas de fichier, un placeholder coloré (initiales) s’affiche.

**Format recommandé :** PNG transparent, **256×256** (ou 128×128 pixel-art), sujet centré, fond vide.  
`image-rendering: pixelated` est activé : le pixel-art Dofus passe très bien.

Dépose les fichiers exactement sous ces noms (sans majuscules, tirets comme ci-dessous).

---

## Incarnam — déjà fournis

Les monstres utilisés dans la première version jouable sont déjà présents dans `assets/sprites/Incarnam/` :

`Ronronchon`, `Feu-Follet`, `Tofu-Chimérique`, `Petit-Gloot`, `Plikplok`, `Boufton-Pâlichon`, `Boufton-Orageux`, `Grand-Splatch` et `Kardorim`.

## Priorité 1 — extensions possibles

| Fichier | Usage | Notes |
|---|---|---|
| `player.png` | Héros (Iop / aventurier) | Optionnel pour l’instant (pas encore affiché dans l’arène) |
| `piou-rose.png` | Piou Rose | Vue 3/4, vivant, pas d’UI |
| `piou-bleu.png` | Piou Bleu | Idem |
| `piou-jaune.png` | Piou Jaune | Idem |
| `tofu.png` | Tofu | Blanc, ailes ouvertes si possible |
| `tofu-noir.png` | Tofu Noir | |
| `boufton-blanc.png` | Boufton Blanc | Petit bouftou |
| `boufton-noir.png` | Boufton Noir | |
| `larve-bleue.png` | Larve Bleue | Donjon Incarnam |
| `larve-orange.png` | Larve Orange | Donjon Incarnam |
| `chef-larves.png` | Boss Chef des Larves | Plus imposant / couronne ou taille |

## Priorité 2 — Astrub

| Fichier | Usage |
|---|---|
| `pissenlit-diabolique.png` | Champs d’Astrub |
| `tournesol-affame.png` | Champs d’Astrub |
| `rose-demoniaque.png` | Champs d’Astrub |
| `arakne.png` | Forêt d’Astrub |
| `sanglier.png` | Forêt d’Astrub |
| `chafer.png` | Forêt d’Astrub |
| `bouftou.png` | Donjon des Bouftous |
| `bouftou-royal.png` | Boss du donjon |

## Fonds d’arène (optionnels, 1280×720 ou 16:9)

| Fichier | Zone |
|---|---|
| `bg-incarnam-prairie.png` | Prairie |
| `bg-incarnam-clairiere.png` | Clairière |
| `bg-incarnam-enclos.png` | Enclos des Bouftons |
| `bg-incarnam-donjon.png` | Donjon d’Incarnam |
| `bg-astrub-champs.png` | Champs d’Astrub |
| `bg-astrub-foret.png` | Forêt d’Astrub |
| `bg-astrub-donjon.png` | Donjon des Bouftous |
| `bg-amakna-champs.png` | Teaser Amakna |

Sans ces fonds, la couleur de zone (déjà en code) sert de décor.

## UI (plus tard, pas bloquant)

| Fichier | Usage |
|---|---|
| `icon-kamas.png` | Remplacer le SVG kamas |
| `icon-dungeon.png` | Marqueur donjon sur la carte |
| `icon-lock.png` | Zone verrouillée |

---

Quand tu ajoutes un PNG, **aucun changement de code** n’est nécessaire : recharge la page, le sprite remplace le placeholder.

Prochaine salve de contenu (Amakna) : on te demandera alors `moskito`, `prespic`, `tournesol` sauvage, `milimulou`, etc.
