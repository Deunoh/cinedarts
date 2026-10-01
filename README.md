# Cinédarts

Appli de score pour fléchettes.
 Un seul fichier HTML, aucune dépendance ni build : on ouvre `index.html` dans un navigateur et c'est parti.

## Lancer l'appli

Aucune installation requise.

```bash
open index.html
```

Ou double-clique simplement sur `index.html` dans le Finder.

### Plein écran (⛶, tous OS / tous navigateurs)

Un bouton **⛶** est disponible en jeu, à côté de "Annuler" : il bascule l'appli en plein écran via l'API standard du navigateur. Fonctionne sur Chrome, Brave, Edge, Firefox, Safari, quel que soit l'OS — pas de script ni d'installation nécessaire.

## Modes de jeu

- **301 / 501** — Score de départ configurable (301, 501 ou 701), avec ou sans règle du double pour terminer.
- **Around the Clock** — Toucher les numéros 1 à 20 dans l'ordre, puis le bull. Bonus optionnel : double = +2, triple = +3.
- **Killer** — Chaque joueur défend un numéro, devient "tueur" en touchant son double, puis élimine les vies des autres. Un **mode débutant** permet de devenir tueur avec un simple toucher (double non requis).

## Joueurs

- De **1 à 8 joueurs**.
- Le mode **1 joueur** (entraînement) est disponible pour 301/501 et Around the Clock.
- Killer nécessite un minimum de **2 joueurs** (passer sur Killer avec 1 joueur sélectionné remonte automatiquement le compteur à 2).
- **2 joueurs par défaut** au lancement de l'appli.

## Contrôles clavier en jeu

Tout se joue au **pavé numérique** (fonctionne même Verr Num désactivé) :

- **0-20** (ou **25** pour un Bull) puis **Entrée** pour valider un lancer.
- **+** Double · **\*** Triple (réappuyer sur le même multiplicateur revient à Simple).
- **/** Bull 25 · **+** puis **/** Bull 50 (validé immédiatement).
- **-** pour "Manqué" (validé immédiatement).
- **⌫** (retour arrière) efface pas à pas : d'abord les chiffres tapés, puis le Double/Triple (retour au Simple), puis annule le dernier lancer.
- Exemples : `* 3 Entrée` = Triple 3, `+ /` = Bull 50.

Les raccourcis du clavier principal restent disponibles : **S** / **D** / **T** (multiplicateur), **M** (manqué).
- **Échap** efface la saisie en cours.

## Autres fonctionnalités

- Annulation du dernier lancer (bouton "Annuler" ou raccourci clavier).
- Règles de chaque mode consultables en jeu (bouton "?").
- Rejouer une partie avec les mêmes joueurs depuis l'écran de victoire.
