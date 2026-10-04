# Fullmotiv — le jeu de padel

Jeu de padel en 2 contre 2, en 3D low poly, jouable dans le navigateur sur ordinateur et sur smartphone. Tout tient dans un seul fichier : `index.html` (Three.js r128 chargé depuis cdnjs).

## Lancer le jeu

Ouvrez `index.html` dans un navigateur récent. Aucune installation ni étape de build.

## Modes

- **Match en 2 contre 2** (terrain 20 × 10 m) : vous jouez au drive avec un partenaire IA au revés, contre deux joueurs IA.
- **Match en 1 contre 1** (terrain 20 × 6 m, format simple de la FIP) : vous affrontez un joueur IA.
- Les deux formats se jouent en match rapide (1 set de 4 jeux) ou match complet (2 sets gagnants de 6 jeux), point en or ou avantages, 3 niveaux d'adversaires.
- **Entraînement vitres** : des balles envoyées contre votre vitre de fond pour apprendre la sortie de vitre.

## Commandes

| Action | Ordinateur | Smartphone |
|---|---|---|
| Se déplacer | ZQSD / WASD / flèches | Joystick (pouce gauche) |
| Volée / drive | L ou Espace | VOLÉE |
| Lob | J | LOB |
| Smash (bandeja depuis le fond) | K | SMASH |
| Viser | Gauche / droite au moment de la frappe | Joystick |
| Power-up | E | Bouton éclair |
| Pause | Échap ou P | Bouton pause |

Au service : L à plat, K rapide, J sûr.

## Règles appliquées

Service à la cuillère en diagonale (2 essais, let), retour après rebond, faute si la balle touche une paroi adverse avant le rebond ou votre propre grillage, point au double rebond, por 3 / por 4, rotation du service, changement de côté, tie-break en 7 points. Le détail est dans l'écran **Règles & touches** du jeu.

Simplifications : la caméra reste du côté du joueur au changement de côté, pas de sortie par les portes, une balle qui touche un joueur n'est pas comptée.

## Personnaliser les sponsors

Les marques sont définies en haut du script, dans `SPONSORS` (logos et couleurs) et `SLOTS` (emplacements sur le terrain). Fullmotiv est le sponsor principal ; les autres marques sont fictives.
