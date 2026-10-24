# BEE Web — version 13.46

Cette version reprend la page 13.46 de BEE-fiches, comme l'APK et le `.exe` 13.46 ; le détail est dans
`CORRECTIONS.md` du dépôt `bee-fiches` (conduite propre au listening, au speaking et au writing ; échanges et
textes modèles du post-primaire ; Input stage 5 / 4 / 6 ; corrections de pronoms et d'objectifs).

- **`index.html`** : la page 13.46 de BEE-fiches, avec les trois mêmes ajouts propres au web qu'en 13.45, aux mêmes
  endroits (en-tête pour l'écran d'accueil, style de l'astuce iPhone, fonctionnement hors connexion et astuce).
  Vérifié : la différence avec la page Android est exactement celle de la 13.45.
- **`sw.js`** : cache hors connexion `bee-13.46`, pour que les téléphones déjà installés passent à la nouvelle version.
- **`tests/`** : contrôles de la conduite par compétence ajoutés.

Vérification : 674 fiches générées sans erreur, **21 contrôles sur 21** et **32 essais sur 32** réussis.

---

# BEE Web — version 13.41 (branche `correction-grammaire-vocabulaire`)

Cette version reprend la page 13.41 de BEE-fiches (branche `correction-grammaire-vocabulaire`), comme l'APK et le `.exe` 13.41.
Le détail complet se trouve dans `RAPPORT-GRAMMAIRE-VOCABULAIRE.md` du dépôt `bee-fiches` (sections 12 à 27).

## Ce qui a changé ici

- **`index.html`** : la page 13.41 de BEE-fiches, à laquelle on a remis les trois ajouts propres au web, aux mêmes endroits :
  1. les lignes d'en-tête pour l'écran d'accueil (manifeste, icônes, couleur) ;
  2. le style de l'astuce d'installation sur iPhone et iPad ;
  3. l'enregistrement du fonctionnement hors connexion et l'astuce d'installation sur iPhone.

  En dehors de ces ajouts, la page est identique, ligne pour ligne, à celle de BEE-fiches 13.41. Elle apporte notamment :
  interface en anglais (compétences et situations de 6e en français), exercices revus, vrai fichier Word `.docx`,
  rappel de sauvegarde, compétences selon le trimestre, vocabulaire limité aux items pertinents (sept au plus,
  sans remplissage), écran d'activation entier sur ordinateur.
- **Astuce iPhone** : traduite en anglais, comme le reste de l'interface. **Corrigé** : quand elle s'affiche au-dessus
  de l'écran d'activation, elle en cachait le titre et le début des instructions, sans moyen de les faire apparaître ;
  l'écran d'activation est maintenant décalé sous l'astuce.
- **`manifest.webmanifest`** : langue `en`, description en anglais.
- **`sw.js`** : nom du cache hors connexion `bee-13.41`. C'est ce changement qui fait que les téléphones déjà installés
  remplacent l'ancienne version par la nouvelle.
- **`tests/`** : tests de BEE-fiches 13.41, adaptés à ce dépôt.

## Vérification

674 fiches générées sans erreur, **20 contrôles sur 20** et **32 essais sur 32** réussis.
iPhone simulé (page servie par le réseau) : astuce en anglais, écran d'activation entier sous l'astuce, identifiant affiché,
fonctionnement hors connexion enregistré sous `bee-13.41`, fiche générée après activation simulée, aucune erreur de page.
Android simulé : pas d'astuce, écran d'activation normal.

## À tester sur un iPhone déjà installé

1. Ouvrir BEE depuis son icône, avec la connexion ; le fermer puis le rouvrir une fois.
2. En haut de la page, la version doit être **13.45**, et la licence doit rester active.
3. Couper la connexion et rouvrir BEE : il doit s'ouvrir quand même.

## 13.42

La liste des activités à cocher est de nouveau dépliée par défaut, sous un titre visible (elle était repliée derrière
une ligne grise peu visible). Détail : section 28 du rapport de `bee-fiches`. Cache hors connexion `bee-13.42`.

## 13.43

Exercices de vocabulaire : chaque item indique à l'élève le paragraphe, ou une portion de cinq lignes pour un paragraphe
long, où chercher la réponse. Détail : section 29 du rapport de `bee-fiches`. Cache hors connexion `bee-13.43`.

## 13.44

Retours d'inspection sur la 13.43 : coupe « Arn……ud » et mises en gras corrigées, comparatifs complets, règle des
connecteurs composée d'après le texte, *wishes and regrets* et *be / get used to* corrigés, intitulés tronqués rétablis,
6e U6 L1 au présent simple, fonctions et objectifs par séance nettoyés (6e à 3e). Détail : section 31 du rapport de
`bee-fiches`. Cache hors connexion `bee-13.44`. La page est la même que celle de l'APK, plus les ajouts propres au web.

## 13.45

Second retour sur la 13.44 : ponctuation et points de suspension des intitulés de grammaire unifiés, points soudés
séparés (4e U2 L2 répartie entre ses deux séances), séance 4e U6 renommée, règle des causatifs complétée. Détail :
section 32 du rapport de `bee-fiches`. Cache hors connexion `bee-13.45`.
