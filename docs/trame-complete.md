# HORS CADRE — Trame complète & suivi de la maquette

> **Ce n’est pas du bruit. C’est une génération qui parle.**
> HORS CADRE est une fiction documentaire interactive située à Grenoble : vivre une manifestation à hauteur d’étudiant, choisir où regarder, qui rejoindre et ce que l’on partage.
> **Document de travail pour faire avancer la maquette.** Le scénario décrit ci-dessous sépare le prototype existant des développements encore proposés.

## Les points d’entrée du projet
- [Scénario V2 — référence actuelle](scenario-v2.md)
- [Arbre Miro](https://miro.com/app/board/uXjVEX1iTNU=/)
- [Notion — carnet de projet, personnages et trame](https://app.notion.com/p/3ff01efc2bc581b987c3e1056f5cfe65)
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

**Étudiant en licence d’histoire · Première manifestation.** Il travaille le week-end dans la restauration ; logement et emploi pèsent sur ses études. Décision d’écriture V1.

Elias est politiquement sensible aux injustices, mais n’a jamais réellement participé à une mobilisation. Il porte un keffieh en signe de solidarité. Il rejoint le cortège pour défendre une cause qui lui tient à cœur, sans savoir ce qu’il va vivre.

Son histoire et sa présence dans la rue existent avant les décisions du joueur. En revanche, sa façon de manifester, sa réaction à un incident et son rapport au fait de filmer se construisent au cours du récit. Il n’est pas présenté d’emblée comme pacifiste, radical ou militant.

Le keffieh est ici un signe de solidarité choisi par le personnage. Il ne sert pas à déduire son origine, sa religion ou ses convictions exactes. Les choix du joueur ne modifient pas rétroactivement ces caractéristiques.

**Phrase d’introduction proposée :** « Je pensais simplement venir manifester. »

[Référence visuelle fournie — keffieh, ambiance uniquement](https://images.openai.com/static-rsc-4/_aAJgwnubpItdRSGkswi8Rl-Vq-fbpplRWQuXM29NIbSneqozeUrxGz6KamnfpFzIQMHVvIugZ3aJbZpFSzZVFyhiHmaP3LzvrKijTiHwVtGIobOLJMgmR2I9k6OBJDDh9Ado5PoIWyQldC0EFmmV9iMlSp-DaAF-PdWJhOgY2o?purpose=inline)

## Distribution et rythme des rencontres

**Un personnage principal jouable : Elias. Six personnages secondaires : Gabriel, Salim, Noé, Louve, Irène et Amandla.**

Noé est le repère stable ; Gabriel et Salim sont des conversations optionnelles à Victor-Hugo. Le joueur peut aussi écouter seul le cortège.

Louve est optionnelle dans suivre ; Irène apparaît dans aider ; Amandla est rencontrée uniquement si un regard extérieur est demandé dans filmer.

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

## 4. Scénario de référence — Elias / V2
[Carnet Notion](https://app.notion.com/p/3ff01efc2bc5816aab85daafb1a46751)
[Arbre de choix dans Miro](https://miro.com/app/board/uXjVEX1iTNU=/)
La page de récit existante a été mise à jour en V2 : elle remplace la V1 pour la prochaine maquette.
- Elias est le protagoniste unique. Le quotidien apparaît dans son téléphone avant le départ.
- Intro jouable : tram, trottinette électrique ou marche, puis Victor-Hugo. Même journée et mêmes informations essentielles.
- Au premier lieu : chercher Noé ou écouter seul ; parler à Gabriel, à Salim ou rester avec Noé est un choix.
- Après la rupture à Grenette : suivre, filmer ou aider.
- Louve est une conversation optionnelle de la branche suivre ; Irène appartient à aider ; Amandla est rencontrée seulement si Elias demande un regard extérieur dans filmer.
- Noé reste l’ami et le contact stable. Tous les secondaires ne sont pas obligés d’apparaître dans une partie.
- Deux réponses du téléphone et une absence de réponse changent le rendez-vous et les dialogues, sans inventer une action passée.
- Quatre conséquences : Le lien, La présence, Le fragment et Le contexte, puis les revendications.
- Seule la branche filmer possède le fichier d’Elias ; aucune branche ne connaît l’origine du verre brisé.
- Quatre dimensions indépendantes, aucun score moral.
**Contrôle documentaire :** 612 combinaisons nominales et dix invariants ; un parcours avec Noé seul existe. Ces nombres décrivent la spécification, pas un jeu déjà développé.
**Médias :** l’inventaire reste sans série du protagoniste explicitement validée. Les plans de transport sont des besoins de production.

[Scénario V2 complet](scenario-v2.md) · [Source de l’arbre](arbre-v2.mmd)

## 5. Archive du prototype antérieur — non canonique

La référence actuelle est le [scénario V2](scenario-v2.md). Les anciens textes avec Inès sont conservés ici uniquement pour retrouver les écrans à migrer ; Elias est le protagoniste de la cible.
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

## 6. Arbre de référence
[Ouvrir le tableau Miro — HORS CADRE / Elias / V2](https://miro.com/app/board/uXjVEX1iTNU=/)
Le diagramme va du choix du trajet au bilan et distingue les choix des conditions de progression. Son code Mermaid reste modifiable dans Miro.
Les branches de personnages sont conditionnelles : Gabriel ou Salim à l’ouverture, Louve dans suivre, Irène dans aider, Amandla dans filmer si un regard extérieur est demandé. Un nœud de condition n’est pas un nouveau choix du joueur.
L’ancien arbre avec Inès appartient à l’historique du prototype et ne décrit plus la cible.

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
### Priorité 1 — scénario V2 prêt pour maquette
[Carnet Notion](https://app.notion.com/p/3ff01efc2bc5816aab85daafb1a46751)
- [x] Elias protagoniste fixe, Noé ami préexistant, cinq autres secondaires conditionnels.
- [x] Introduction tram / trottinette / marche écrite jusqu’à Victor-Hugo.
- [x] Approche du cortège et conversations de Gabriel ou Salim optionnelles.
- [x] Trois branches suivre / filmer / aider écrites jusqu’à leurs conséquences.
- [x] Louve, Irène et Amandla intégrées à des événements conditionnels.
- [x] Téléphone, carte, publication et retrouvailles soumis aux faits vécus.
- [x] Quatre dimensions indépendantes sans score pacifiste/violent.
- [x] Inventaire des ressources accessibles et liste des médias manquants.
- [x] Arbre Miro créé et contrôles documentaires de cohérence effectués.
**Critère :** action, destination et conséquence cohérentes ; pas de souvenir, de personne connue ou de fichier inventés.
**Reste à réaliser :** adaptation complète de Figma, médias utilisables et développement. Le récit écrit n’est pas une preuve que ces réalisations sont terminées.

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
