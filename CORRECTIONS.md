# BEE Web — corrections de la version 13.37

Cette version reprend **exactement** les corrections de BEE-fiches 13.37 (édition Android) et de BEE Ordinateur 13.37.
Le détail complet, point par point, se trouve dans `CORRECTIONS.md` du dépôt `bee-fiches`.

## Ce qui a changé ici

- **`index.html`** : c'est la page 13.37 de BEE-fiches, à laquelle on a remis les trois ajouts propres au web,
  sans rien y changer et aux mêmes endroits qu'avant :
  1. les lignes d'en-tête pour l'écran d'accueil (manifeste, icônes, couleur) ;
  2. le style de l'astuce d'installation sur iPhone et iPad ;
  3. l'enregistrement du fonctionnement hors connexion et l'astuce d'installation sur iPhone.

  En dehors de ces trois ajouts, la page est identique, ligne pour ligne, à celle de BEE-fiches 13.37.
  Elle apporte donc : devoirs allégés, situations d'intégration au bon rythme, trois consignes et grille 3 / 6 / 9 / 2,
  fautes d'anglais et « he » génériques corrigés, textes du second cycle dans la fourchette officielle,
  licence non effacée en cas de simple erreur de vérification.
- **`sw.js`** : nom du cache hors connexion `bee-13.37`. C'est ce changement qui fait que les téléphones
  déjà installés remplacent l'ancienne version par la nouvelle et effacent l'ancienne copie.
- **`tests/`** : les mêmes contrôles automatiques que BEE-fiches, adaptés à ce dépôt.

## Vérification

674 fiches générées sans erreur, **20 contrôles sur 20** et **32 essais sur 32** réussis.
Essai en iPhone simulé : l'astuce d'installation s'affiche, le fonctionnement hors connexion s'enregistre
en version 13.37, aucune erreur de page.

## À tester sur un iPhone déjà installé

1. Ouvrir BEE depuis son icône, avec la connexion : fermer puis rouvrir l'application une fois.
2. En haut de la page, la version doit être **13.37**, et la licence doit rester active.
3. Couper la connexion et rouvrir BEE : il doit s'ouvrir quand même.
