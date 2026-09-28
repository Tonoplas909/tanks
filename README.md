# Tanks!

Recréation du mini-jeu **Tanks!** de Wii Play, jouable dans le navigateur — en solo ou en ligne jusqu'à 4 joueurs.

**Jouer :** https://tonoplas909.github.io/tanks/

## Modes

- **Solo** : les 20 missions de la campagne contre les chars de l'ordinateur.
- **Coopération en ligne** : la campagne à plusieurs, vies partagées.
- **Versus en ligne** : chacun pour soi, premier à 5 manches gagnées.

Pour jouer en ligne, un joueur clique sur **Créer une partie en ligne** et donne le code de 5 lettres aux autres, qui cliquent sur **Rejoindre une partie**. La connexion se fait directement entre navigateurs (WebRTC via [PeerJS](https://peerjs.com/)), sans serveur de jeu.

## Plein écran

Le jeu occupe toute la fenêtre : l'arène s'élargit (ou s'allonge) selon la forme de l'écran, chaque mission restant centrée avec du terrain jouable autour. En ligne, c'est la fenêtre de l'hôte qui fixe la taille de l'arène. Touche **F** pour le plein écran.

## Commandes

| Action | Touche |
|---|---|
| Se déplacer | ZQSD / WASD / flèches |
| Viser | souris |
| Tirer | clic gauche |
| Poser une mine | clic droit / Espace |
| Couper le son | M |
| Plein écran | F |
| Pause (solo) | P / Échap |

## Chars ennemis

Marron (immobile), Gris, Turquoise (roquettes), Jaune (mines), Rose (rafales), Vert (roquettes à double rebond), Violet, Blanc (invisible) et Noir (très rapide).

---

Projet de fan non officiel, inspiré de « Tanks! » — Wii Play (Nintendo, 2006).
