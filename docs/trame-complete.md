# HORS CADRE — Trame complète & suivi de la maquette

> **Ce n’est pas du bruit. C’est une génération qui parle.**
> HORS CADRE est une fiction documentaire interactive située à Grenoble : vivre une manifestation à hauteur d’étudiant, choisir où regarder, qui rejoindre et ce que l’on partage.
> **Document de travail pour faire avancer la maquette.** Le scénario décrit ci-dessous sépare le prototype existant des développements encore proposés.

## Les trois points d’entrée
- [Maquette Figma — écrans et composants](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9)
- [Prototype — du loader à l’expérience](https://www.figma.com/proto/cuFSnI2KEsFVh3iOarpbw9?node-id=58-32596&starting-point-node-id=58%3A32596)
- [GitHub — Mahkalix / HORS-CADRE](https://github.com/Mahkalix/HORS-CADRE)

**Rôle des outils :** Notion porte le récit, les décisions et les critères de validation ; Figma porte les écrans, les composants et le prototype ; GitHub porte la documentation et accueillera le développement. Ces liens ne constituent pas une synchronisation automatique.

État de référence : 2026-10-20. Vérifié à partir du parcours cliquable Figma et du README GitHub.



## 1. Le projet en une minute
**Question centrale :** comment une colère étudiante réelle devient-elle du bruit médiatique avant même d’être entendue ?

Le joueur incarne **Elias, 21 ans, étudiant en licence, à sa première manifestation**. Il porte un keffieh en signe de solidarité, sans que ce vêtement détermine son origine, sa religion ou une idéologie prédéfinie. Il ne peut pas simultanément écouter tout le monde, filmer toute la scène et rester avec son groupe. Ses décisions construisent sa manière d’agir et changent ses relations, les informations accessibles et les scènes suivantes.

**Promesse :** une expérience immersive à choix cliquables, inspirée de la mise en scène des jeux narratifs et de leur arbre de ramifications, avec des vidéos réelles contextualisées à terme. La cible actuelle affichée sur l’accueil est d’environ dix minutes ; la durée devra être vérifiée avec les médias retenus.

**Cadre :** Grenoble, principalement Victor-Hugo, place Grenette, Jardin de Ville et place de Verdun. Les trajets et la journée racontée sont fictifs ; la carte ne présente pas un itinéraire officiel de manifestation.

**Positionnement :** une œuvre engagée sur la jeunesse, les institutions et la fabrication des images. Montrer les tensions et les violences observables sans présumer de leur auteur ni attribuer une culpabilité à partir d’un extrait isolé.

## 2. Ce qui existe et ce qui reste à concevoir
**Déjà maquetté :** trois états de loader, accueil, prologue, cortège, basculement, carte et lieux, messages et réponse envoyée, retrouvailles avec Inès, choix de publication, deux fins, bilan ramifié, pause et sources, aperçu mobile. Cela représente dix-neuf cadres d’écran, dont trois états du loader.

**Déjà structuré :** composants de navigation, choix et embranchements, messagerie, téléphone, carte, boutons, identité et variantes de logo. Les dix-neuf cadres principaux et leurs blocs de contenu utilisent désormais Auto Layout ; les superpositions visuelles conservent leur positionnement absolu.

**Pas encore réalisé :** film interactif jouable sur le web, vidéos intégrées, bande-son, progression persistante, arbre calculé selon le parcours réel et version mobile complète. Le Figma simule des navigations et le défilement du loader. Le bilan affiche encore un exemple de parcours fixe.

**À retenir :** l’ancien README et les documents historiques du dépôt décrivaient une autre version. Ils ne suffisent pas pour connaître l’état actuel de la maquette.

## 3. Elias et les six personnages secondaires

[Fiches complètes : Elias et les six personnages](personnages.md)

## Elias, 21 ans — personnage principal

**Étudiant en licence · Première manifestation.** La discipline de sa licence reste à définir.

Elias est politiquement sensible aux injustices, mais n’a jamais réellement participé à une mobilisation. Il porte un keffieh en signe de solidarité. Il rejoint le cortège pour défendre une cause qui lui tient à cœur, sans savoir ce qu’il va vivre.

Son histoire et sa présence dans la rue existent avant les décisions du joueur. En revanche, sa façon de manifester, sa réaction à un incident et son rapport au fait de filmer se construisent au cours du récit. Il n’est pas présenté d’emblée comme pacifiste, radical ou militant.

Le keffieh est ici un signe de solidarité choisi par le personnage. Il ne sert pas à déduire son origine, sa religion ou ses convictions exactes. Les choix du joueur ne modifient pas rétroactivement ces caractéristiques.

**Phrase d’introduction proposée :** « Je pensais simplement venir manifester. »

[Référence visuelle fournie — keffieh, ambiance uniquement](https://images.openai.com/static-rsc-4/_aAJgwnubpItdRSGkswi8Rl-Vq-fbpplRWQuXM29NIbSneqozeUrxGz6KamnfpFzIQMHVvIugZ3aJbZpFSzZVFyhiHmaP3LzvrKijTiHwVtGIobOLJMgmR2I9k6OBJDDh9Ado5PoIWyQldC0EFmmV9iMlSp-DaAF-PdWJhOgY2o?purpose=inline)

## Distribution et rythme des rencontres

**Un personnage principal jouable : Elias. Six personnages secondaires : Gabriel, Salim, Noé, Louve, Irène et Amandla.**

Gabriel, Salim et Noé sont introduits d’abord, dans des échanges brefs et situés : confrontation, non-violence et organisation. Ces mots sont des repères d’écriture ; ils ne doivent pas apparaître comme trois classes à sélectionner ou trois réponses forcément prévisibles.

Louve, Irène et Amandla apparaissent ensuite à travers des événements précis : désaccord autour d’une action, première confrontation vécue, puis documentation et publication. L’ordre exact de leurs entrées reste à écrire. Ne pas transformer l’ouverture en six fiches de présentation successives.

Elias n’est pas un avatar vide ni une copie du joueur : il conserve un passé et des relations. Les liens préexistants avec les six secondaires restent à préciser avant de finaliser les dialogues.


### Les six personnages secondaires
- **Gabriel, 22 ans, histoire — le révolté :** ancien partisan du dialogue, il considère les manifestations pacifiques insuffisantes et participe parfois à des dégradations. « Quand personne ne nous écoute, comment se faire entendre ? »
- **Salim, 21 ans, droit — le pacifiste :** sa non-violence est un choix politique, nourri par l’expérience des discriminations et des tensions institutionnelles. « Notre colère est légitime. Ce qu’on en fait compte aussi. »
- **Noé, 23 ans, sciences politiques — l’organisateur :** engagé dans un syndicat étudiant, il organise les assemblées et les cortèges tout en affrontant les compromis de la négociation. « Une mobilisation sans organisation risque de s’épuiser. »
- **Louve, 22 ans, sociologie — la révoltée :** issue d’un milieu favorisé, elle questionne sa position sociale et accepte certaines formes d’action directe. « Être neutre face à une injustice, c’est déjà faire un choix. »
- **Irène, 21 ans, psychologie — la pacifiste :** elle manifeste pour la première fois et découvre que rester pacifique ne protège pas de toute confrontation. « On peut être en colère sans vouloir blesser quelqu’un. »
- **Amandla, 23 ans, communication — la militante :** elle documente les manifestations et questionne l’utilité réelle du fait de filmer pour les personnes concernées. « Ce qu’on ne montre pas risque d’être oublié. »

Les biographies détaillées et les références visuelles restent dans les fiches. Les portraits sont des références d’ambiance, pas un casting ni des représentations définitives.

### Continuité avec les écrans actuels
Inès est le repère provisoire de l’ancienne maquette ; elle ne fait pas partie de cette nouvelle distribution. Les sections décrivant le prototype conservent son nom pour distinguer l’existant du scénario cible. Ses fonctions doivent être réparties par réécriture entre les six secondaires.

## 4. Nouvelle trame cible — Elias
Cette section porte la nouvelle direction du récit. Les sections suivantes décrivent le prototype antérieur, encore à adapter.

### Acte 1 — Le rassemblement
Elias arrive dans sa première manifestation à Grenoble. Slogans, conversations, ville et revendications précèdent l’incident. Il découvre Gabriel, Salim et Noé par des actions et des échanges, pas par une sélection de profils idéologiques.

**Voix intérieure proposée :** « Je pensais simplement venir manifester. »

### Acte 2 — La rencontre et la motivation
Un manifestant demande à Elias pourquoi il est venu. Le joueur formule une motivation concrète — cause défendue, personne accompagnée, injustice vécue — sans choisir « pacifiste », « radical » ou « militant ». Les options exactes de dialogue restent à écrire une fois le passé d’Elias défini.

La réponse peut modifier la relation ou la conversation suivante, sans déterminer toute la trajectoire.

### Acte 3 — La rupture
Un bruit de verre brisé interrompt le cortège. Des personnes commencent à courir. Elias ne sait pas exactement ce qui s’est passé.

**Premier vrai choix d’action :**
- **Suivre le groupe** : rester avec ses proches, avec le risque de manquer des informations.
- **Documenter l’incident** : conserver une trace partielle, avec le risque de se séparer du groupe.
- **Tenter d’aider quelqu’un** : agir auprès d’une personne, avec le risque de perdre le fil de la scène.

Ces coûts sont des hypothèses d’écriture à préciser, pas des conséquences déjà simulées dans Figma. Un bruit ou une coupe ne suffit pas à établir qui a commis un acte. Si l’incident est reconstitué, son statut fictif doit être clair.

### Acte 4 — Des rencontres et informations différentes
Le joueur constate les effets de son action : une personne retrouvée, une information manquée, un témoignage entendu ou un plan incomplet. Téléphone et carte servent à poursuivre un objectif situé.

Louve, Irène et Amandla entrent par des événements précis. Elles ne forment pas un deuxième écran obligatoire de présentation. Gabriel et Louve conservent des trajectoires distinctes, tout comme Salim et Irène.

### Acte 5 — Montrer, partager ou préserver le contexte
Le débat sur les images se nourrit de ce qu’Elias a réellement vu et filmé. Amandla peut faire entendre les enjeux de la documentation, sans livrer la réponse attendue.

La branche « filmer » peut rejoindre le choix de montage existant. Les branches « suivre » et « aider » ne doivent pas donner miraculeusement accès au même enregistrement : prévoir une autre source explicitement attribuée ou une conséquence différente.

### Acte 6 — Des conséquences, puis les revendications
Le récit montre ce qui a été préservé ou perdu : relation, information, possibilité d’agir, contexte d’une image. Il redonne ensuite place aux revendications.

Les fins « Le fragment » et « Les voix » sont des supports existants à retravailler ; elles ne constituent pas encore un bilan suffisant des trois nouvelles branches. Éviter une fin qui classe simplement Elias comme violent ou pacifiste.

### Acte 7 — Le bilan de parcours
L’arbre distingue actions, rencontres et informations obtenues. Il révèle ce qui est resté hors du regard d’Elias et permet de rejouer une étape.

**Dimensions indépendantes :** solidarité, confiance envers les institutions, rapport à l’action directe et fidélité aux proches. Ne pas les fusionner en un score moral. Ne pas déduire une position définitive d’un seul choix.

### Photographies à inventorier
Le nombre de vues du même homme au keffieh n’est pas connu. Il faut le renseigner avant de choisir une mise en scène dépendante de ses expressions ou de ses positions. Les images de référence de rassemblement, de rencontre et de confrontation ne sont pas des plans validés de la même histoire.

## 5. Trame du prototype antérieur — écrans à adapter
### A — Le seuil : loader puis accueil
**Ce que l’on vit :** avant même d’entrer dans la rue, des mots traversent l’écran : entendre, filmer, rester, choisir, logement, avenir, dignité, écouter.

**Écran :** HORS CADRE en grand, fond beige papier, écriture brun profond. Deux lignes de mots défilent en sens opposés. Le loader peut être passé. Les chiffres actuels sont une simulation graphique ; ils ne mesurent pas le chargement réel de fichiers.

**Accueil :** la signature annonce le sujet et donne accès à l’expérience, à la carte et aux sources. Le libellé du bouton observé est actuellement « CONTINUER » ; pour une première visite, « Entrer dans l’expérience » serait plus clair, tandis que « Continuer » devrait correspondre à une progression enregistrée.

### B — Avant la rue : donner une raison d’être là
**Intention initiale, non maquettée dans le parcours actuel :** une chambre étudiante, un frigo presque vide, une hausse de loyer, des démarches administratives et un agenda cours/travail. Une notification invite à la mobilisation.

Cette scène explique la colère avant le spectacle. Elle reste une option de scénario : soit un court prologue interactif, soit quelques indices intégrés au téléphone. Ne pas l’ajouter automatiquement à la version actuelle tant que sa durée et sa fonction ne sont pas choisies.

### C — Le prologue : rejoindre Inès
**Version existante :** « Tu étais venu·e pour être entendu·e. » Le joueur rejoint Inès dans le cortège, téléphone chargé, sans savoir encore comment il s’en servira.

**Action :** rejoindre Inès → le cortège.

**Fonction :** établir le lien humain et annoncer que chaque choix déplace le regard. L’écran précise que les archives illustrent une fiction.

### D — Le cortège : entendre avant de choisir
**Version existante :** Inès dit : « Tu vois ? On n’est pas là pour rien. » L’objectif est de rester près d’elle. Le joueur choisit ce qui retient son attention :
- **Rester avec le cortège** → écran de retrouvailles avec Inès.
- **Filmer la scène** → basculement.
- **Ouvrir le message** → téléphone et carte.

**À renforcer :** donner d’abord une scène à écouter ou une personne à rencontrer. Aujourd’hui, « Rester avec le cortège » conduit trop vite à « Tu l’as retrouvée » alors que la séparation n’a pas encore été vécue. Une transition est nécessaire ou le libellé de conséquence doit changer.

### E — Le basculement : le groupe se disperse
**Version existante :** un cadre d’enregistrement, douze secondes filmées, le groupe qui se disperse et un message d’Inès : « T’es où ? On s’est perdus. »

Deux actions :
- **Continuer à filmer** → décision de publication.
- **Rejoindre Inès** → téléphone, puis point de rendez-vous.

**Conflit :** garder une trace ou chercher son amie. Le joueur ne doit pas recevoir une explication de la « bonne réponse » avant de choisir.

**À écrire avec les médias :** ce qui déclenche la dispersion, ce que la caméra montre réellement et ce qu’elle ne permet pas de conclure. Les violences de manifestants ou de policiers ne peuvent être écrites comme des faits réels avant la sélection et la vérification des séquences correspondantes.

Le faux compte à rebours a été retiré du desktop ; le texte mobile contient encore « 00:08 » et doit être harmonisé.

### F — Le téléphone : reprendre contact
**Conversation existante :**
1. Inès propose d’abord la place Victor-Hugo.
2. Le joueur répond qu’il sort du tram.
3. Inès annonce que le groupe a avancé vers Grenette et propose le Jardin de Ville si le groupe se perd.
4. Une position partagée ouvre la carte.
5. Deux réponses rapides : « J’arrive ! » et « Restez ensemble ».
6. L’état envoyé confirme : « J’arrive au Jardin de Ville. »

**Fonction :** faire du téléphone un outil du récit, pas un menu décoratif.

**À corriger :** la conversation mélange actuellement des messages antérieurs et l’instant présent. Ajouter des heures ou un séparateur clair. Définir l’effet de chaque réponse, au lieu de proposer deux formulations qui arrivent presque au même résultat.

### G — La carte de Grenoble : retrouver une direction
**Victor-Hugo :** point de départ et repère de la rencontre.
**Grenette :** entrée dans le cortège et les paroles collectives.
**Jardin de Ville :** rendez-vous avec Inès.
**Verdun :** accès actuel à la scène de basculement ; sa place exacte dans la chronologie reste à décider.

La carte est cliquable et s’appuie sur une géométrie OpenStreetMap stylisée. Elle doit aider le joueur à retrouver son objectif, pas lui proposer un tableau de surveillance. Distinguer les lieux visités, accessibles et encore inconnus ; ne pas laisser une navigation libre contredire les événements déjà vécus.

### H — Retrouver Inès : le lien avant l’image
**Version existante :** « Tu l’as retrouvée. Tu n’as pas tout filmé. » Le groupe se reforme à l’écart ; ce qui s’est passé derrière le joueur reste hors de son cadre.

**Action :** continuer ensemble → fin « Les voix ».

**Conséquence :** le lien est préservé, mais le joueur ne dispose pas d’un enregistrement complet. Ce manque doit être ressenti sans devenir une punition.

**À préciser :** cette branche rejoint actuellement la même fin que le partage d’un plan complet. Conserver éventuellement un écran final commun sur les revendications, mais personnaliser le bilan pour ne pas laisser croire que le joueur a filmé ce qu’il n’a pas vu.

### I — Ce que tu montres : choisir un montage
**Version existante :** « 12 secondes. Toute l’histoire ? » Le joueur possède un extrait de douze secondes et un plan complet annoncé de deux minutes trente-quatre.

Deux actions :
- **Publier les 12 secondes** → fin « Le fragment ».
- **Partager le plan complet** → fin « Les voix ».

**À renforcer :** permettre de comparer concrètement les débuts et les fins des deux versions avant de publier. La durée du plan complet reste une donnée fictive de maquette et doit être ajustée aux médias disponibles.

Un plan plus long n’est pas automatiquement neutre ou complet : le cadrage, le point de vue et les informations manquantes doivent rester perceptibles.

### J — Fin 1 : le fragment
L’extrait circule ; la scène est commentée pour son spectacle, les revendications disparaissent derrière les réactions.

**Phrase existante :** « On a vu ton image. Qui a entendu vos voix ? »

**À concevoir :** une montée de commentaires et de reprises médiatiques fictives clairement identifiées. Montrer des transformations concrètes du récit sans inventer un faux article attribué à un vrai média.

**Sorties :** voir le parcours ou revenir au choix de montage.

### K — Fin 2 : les voix
Le rythme redescend. Les demandes réapparaissent : un logement digne, étudier sans s’épuiser, être représenté et pouvoir envisager la suite.

**Phrase existante :** « Derrière le bruit, il y avait des demandes. »

**Convergence proposée :** personnaliser l’entrée de cette fin selon que le joueur a retrouvé Inès ou partagé son plan, puis conserver une restitution commune des revendications.

La formulation d’origine « Après tout ce bruit, qu’avez-vous réellement entendu ? » peut servir de dernière question ; elle n’est pas encore matérialisée comme interaction finale.

### L — Après le film : voir ce qui est resté hors cadre
L’arbre inspiré des jeux narratifs révèle les étapes suivies, les autres possibilités et les passages non explorés. Crochets ouverts, connecteurs fins et vignettes sur les fins reprennent la direction des références.

**Existant :** nœuds cliquables pour rejouer des étapes, chemin bleu et branches discrètes.
**À développer :** alimenter l’arbre avec le vrai parcours du joueur ; décider quand les scènes inconnues peuvent être révélées ; définir ce qui est réinitialisé quand on rejoue une étape.

### M — Pause, sources et sortie
Pause, sous-titres, transcription, son, mouvement réduit et reprise de scène doivent rester accessibles sans compter comme des décisions narratives.

**Existant :** page pause et sources. Le bouton de reprise revient actuellement au basculement, indépendamment de l’écran d’origine.
**À corriger :** reprendre à la scène et au moment réellement quittés.

## 6. Carte des embranchements du prototype antérieur
```mermaid
flowchart TD
  L["Loader"] --> A["Accueil"]
  A --> P["Prologue : rejoindre Inès"]
  P --> C["Le cortège"]
  C -->|"Rester avec le cortège"| R["Retrouver Inès"]
  C -->|"Filmer la scène"| B["Le basculement"]
  C -->|"Ouvrir le message"| T["Téléphone"]
  B -->|"Continuer à filmer"| M["Choix de publication"]
  B -->|"Rejoindre Inès"| T
  T --> E["Réponse envoyée ou position partagée"]
  E --> J["Jardin de Ville"]
  J --> R
  R --> V["Fin : Les voix"]
  M -->|"Publier les 12 secondes"| F["Fin : Le fragment"]
  M -->|"Partager le plan complet"| V
  F --> X["Bilan de parcours"]
  V --> X
  F -->|"Revenir au montage"| M
```

Ce schéma décrit le parcours principal ; la carte, la pause, les sources et certains raccourcis de navigation donnent aussi accès à d’autres écrans. Il ne représente pas encore un moteur narratif avec prérequis.

## 7. Les écrans à ouvrir pendant la conception
| Écran | Figma | Travail prioritaire |
| --- | --- | --- |
| Loader | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=58-32596) | Distinguer animation d’attente et véritable chargement ; mouvement réduit. |
| Accueil | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=26-38621) | Clarifier commencer ou reprendre. |
| Prologue | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-370) | Choisir la place du quotidien étudiant. |
| Cortège | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-388) | Faire entendre des motivations avant le choix. |
| Basculement | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-421) | Écrire le déclencheur avec une séquence vérifiée. |
| Carte / Grenette / Jardin | [Carte](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=22-19352) · [Grenette](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=22-19353) · [Jardin](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=33-91423) | Définir accès, objectifs et chronologie. |
| Messages | [Conversation](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=22-19354) · [Envoyé](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=33-97995) | Heures, réponses distinctes, retour dans la scène. |
| Retrouvailles | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-464) | Adapter la conséquence au chemin suivi. |
| Publication | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-505) | Comparer les deux montages. |
| Les deux fins | [Le fragment](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-533) · [Les voix](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-551) | Développer les conséquences sans score moral. |
| Arbre de parcours | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-566) | Faire correspondre chaque liaison au vrai scénario. |
| Pause et sources | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-602) | Reprise contextuelle et crédits par média. |
| Mobile | [Ouvrir](https://www.figma.com/design/cuFSnI2KEsFVh3iOarpbw9?node-id=8-661) | Décliner tout le parcours et supprimer le minuteur résiduel. |

## 8. Direction artistique à conserver
- **Fonds : beige papier** — token actuel #DEDCD1.
- **Écriture : brun profond** — #29231F.
- **Accent : bleu** — #4760FF, pour actions et chemin suivi.
- **Textes et repères : Martian Mono Light.**
- **Titres : Ash est la direction demandée.** Le fichier contient encore plusieurs familles et des mots-symboles vectoriels ; l’uniformisation typographique reste à terminer. Le connecteur ne charge pas actuellement certaines polices locales.
- **Logo :** lettrage original en vecteurs, avec formats complet, compact et H/C ; choisir le format selon la place disponible.
- **Image :** documentaire, désaturée, minérale, beige/gris, avec contraste retenu. Les références de L’Arène servent à l’ambiance et ne constituent pas des médias à réutiliser.
- **Interface :** peu d’éléments simultanés ; priorité à la scène, au message ou à la décision du moment.
- **Structure :** Auto Layout pour les contenus, positions absolues pour les superpositions, la carte et les décors.

## 9. Composants nécessaires pour continuer
**Existants :** boutons, choix narratifs avec états, nœuds de parcours à crochets, navigation film et console, rail, cartes de lieux, repères, téléphone, bulles reçues/envoyées, réponses rapides, position partagée, saisie en cours, confirmation envoyée et variantes du logo.

**À compléter ou vérifier :**
- Lecteur vidéo : lecture, pause, sous-titres, transcription, son, reprise et erreur de chargement.
- Choix : repos, focus clavier, sélection, confirmation, indisponible et libellé long sur mobile.
- Conversation : chronologie, messages groupés, réponse choisie, position et état de livraison.
- Carte : lieu actuel, accessible, visité et verrouillé, avec alternative en liste.
- Bilan : étape suivie, actuelle, possible, inconnue et fin ; vignette et connexion réutilisables.
- Restitution des revendications : citation sourcée, texte fictif ou parole documentaire clairement distingués.

## 10. Médias et statut documentaire
Les photographies déjà utilisées sont des archives illustratives, pas les événements du scénario :
- [Grenoble, 7 septembre 2024 — Haldu, CC0](https://commons.wikimedia.org/wiki/File:Manifestation_du_7_septembre_2024_%C3%A0_Grenoble_(1).jpg)
- [Grenoble, 15 mars 2023 — David Monniaux, CC BY-SA 4.0](https://commons.wikimedia.org/wiki/File:Grenoble_manif_IMG_3612.jpg)
- [Carte — contributeurs OpenStreetMap, ODbL](https://www.openstreetmap.org/copyright)

Pour chaque future vidéo, consigner la source, l’auteur, la date, le lieu, le contexte, les droits, la durée, les coupes et la fonction narrative. Un lien accessible sur le web ne suffit pas à établir un droit de réutilisation. Prévoir un média de remplacement si une séquence ne peut pas être utilisée.

Les messages d’Inès, les personnages, les commentaires, la diffusion de l’extrait et les conséquences sont fictifs. Les faits d’une archive ne sont pas modifiés par le choix du joueur.

## 11. Les anciennes idées à décider, sans les perdre
- **Chambre étudiante :** contextualiser le quotidien ; choisir si elle appartient au parcours court.
- **Trois regards simultanés — rue, réseaux, médias :** possible dispositif du dernier chapitre, pas trois colonnes permanentes dès le départ.
- **Faire taire :** couper le bruit et révéler les demandes ; possible interaction de fin, encore absente du prototype.
- **Écouter :** laisser une parole se dérouler entièrement ; prévoir une alternative accessible au fait de rester immobile.
- **BRUIT DE FOND :** ancien nom envisagé ; le nom de travail retenu est HORS CADRE.
- **Témoignages réels et vidéos :** objectif éditorial, pas contenu déjà intégré.

## 12. Ordre de travail pour la prochaine version
### Priorité 1 — verrouiller le récit avant de multiplier les écrans
- [x] Fixer Elias comme personnage principal et les six autres comme secondaires.
- [ ] Réécrire l’ouverture avec Gabriel, Salim et Noé seulement.
- [ ] Détailler les trois branches : suivre, filmer et aider.
- [ ] Prévoir les entrées progressives de Louve, Irène et Amandla.
- [ ] Définir les quatre dimensions narratives sans score pacifiste/violent.
- [ ] Inventorier les photographies disponibles du même protagoniste.
- [ ] Choisir si le quotidien étudiant est montré avant la rue ou dans le téléphone.
- [ ] Définir le déclencheur de la dispersion et le rôle exact de Verdun.
- [ ] Corriger le raccourci cortège → retrouvailles.
- [ ] Écrire une conséquence propre à la branche Inès et une conséquence propre au plan complet.
- [ ] Définir précisément ce que changent les deux réponses du téléphone.
**Critère de fin :** chaque choix possède une action, une destination et une conséquence cohérentes ; aucun écran ne suppose une action que le joueur n’a pas faite.

### Priorité 2 — construire une séquence complète et crédible
- [ ] Détailler cortège → basculement → téléphone ou publication → conséquence.
- [ ] Sélectionner des médias candidats et renseigner leur contexte et leurs droits.
- [ ] Écrire les dialogues et sous-titres, en distinguant fiction et témoignage.
- [ ] Prototyper la comparaison entre extrait et plan long.
**Critère de fin :** la séquence se comprend sans explication orale du concepteur et fonctionne aussi sans son.

### Priorité 3 — rendre le parcours cohérent dans Figma
- [ ] Reprise de pause à la bonne scène.
- [ ] Accès à la carte compatibles avec la progression.
- [ ] Arbre fidèle à chaque embranchement ; état d’exemple explicitement identifié tant qu’il reste statique.
- [ ] Accueil : distinguer commencer, continuer et rejouer.
- [ ] Mobile : retirer « 00:08 » et décliner les écrans manquants.
**Critère de fin :** parcourir chaque branche sans impasse ni retour incohérent.

### Priorité 4 — finaliser le système visuel
- [ ] Uniformiser Ash pour les titres, selon les possibilités réelles du fichier.
- [ ] Vérifier tous les composants en largeur réduite et avec des textes longs.
- [ ] Vérifier contraste, focus visible, navigation clavier et mouvement réduit.
- [ ] Relier une version de maquette validée à une version de documentation et, ensuite, à une version du code.
**Critère de fin :** les mêmes règles de mise en page, de couleur et d’interaction se retrouvent sur tous les écrans.

## 13. Comment utiliser cette page ensemble
Pour chaque modification : noter l’écran concerné, le problème constaté, la décision retenue, le lien Figma et ce qui permet de considérer le point comme terminé. Ne pas cocher une tâche de développement parce que son écran existe dans Figma.

**Prochaine séance recommandée :** travailler le cortège et la dispersion. C’est là que le projet doit faire ressentir une colère humaine avant de demander au joueur de choisir son cadrage.
