# Suivi entraînement — Semi de Casteljaloux (21,11 km)

Document de passation. À joindre en début de nouvelle conversation pour reprendre le suivi.
Le plan lui-même est dans **`index.html`**, qui s'ouvre directement sur la séance du jour. Ce fichier ne contient que ce que le HTML ne dit pas : les données brutes, les raisonnements, et la méthode COROS.

---

## État au 27/08/2026

| | |
|---|---|
| **Course** | Dimanche **22/11/2026** confirmé · 21,11 km · 139 m D+ · deux boucles · départ ~9h |
| **Objectif** | **1h48 central**, 1h45 plafond du bon jour. Révisé à la baisse le 17/08 (voir Pronostic) |
| **Allure course** | 5'02 à 5'07/km. Recalée définitivement après le 10 km du 04/10 |
| **Seuil MESURÉ le 13/08** | **4'42/km à FC 162.** La donnée qui pilote tout |
| **VMA** | **≈ 15,8 km/h** (15,5 à 16,1), déduite du 16/08. Question close, aucun retest |
| **FC max** | **180**, mesurée le 16/08. À corriger dans COROS si ce n'est pas fait |
| **Où on en est** | **S6, première semaine de phase 2 (seuil)**, démarrée le 24/08. **Première séance de seuil réalisée le 27/08** (3 × 8' : 4'58/FC150 · 4'46/FC156 · 4'44/FC162), bloc 3 dans les deux cibles à la fois. Le bloc tient |
| **Vigilance n°1** | TFL genou gauche. **Test du 23/08 passé sans aucune sensation**, une première sur une longue avec finish. Surveillance et renfo maintenus à l'identique |
| **Vigilance n°2** | **Hanche droite latérale, nouveau le 27/08.** Gêne isolée en toute fin de seuil, autre structure et autre côté que le genou. Surveiller, aucun changement de plan (voir section dédiée) |

**Quatre règles à ne jamais perdre**
1. La barre monte quand la course descend, et inversement. Jamais les deux la même semaine.
2. La FC commande la décision, l'allure commande l'exécution.
3. La sortie longue est plafonnée en **durée**, jamais en distance (1h50, sauf S14 et S16 à 2h00).
4. Les séances se courent aux allures **actuelles**, jamais à celle de l'objectif.

**Attention aux versions antérieures** : toutes les allures d'avant le 13/08 (seuil 4'57, allure semi 5'12) viennent d'une estimation COROS fausse de 15 s/km. Ne jamais les reprendre.

---

## Profil coureur

- Base réelle avant le plan : plateau à **27-31 km/semaine** sur 3 semaines (29/06 au 19/07), 3 sorties, plus longue 13,5 km.
- **Navettes salle 2 × 2,2 km, irrégulières.** Il ne fait pas systématiquement l'aller-retour et jamais le retour les jours de jambes. Entre 0 et 9 km par semaine. **Elles se comptent quand elles sont faites, elles ne se planifient pas** et n'entrent pas dans les volumes affichés. Le retour monte de 37 m et sort à FC ~146 : à ralentir sous 140 si possible, mais correction mineure (voir Intensité grise).
- **Musculation : 3 séances, non négociables.** Jambes le lundi (5 exercices, thruster compris), pec-dos le mercredi, épaule-bras le vendredi. Hyrox Sprint en septembre et Hyrox duo en février : c'est un objectif parallèle, pas une variable d'ajustement. **Seul réglage : la charge ondule sur 3 semaines** (lourde / moyenne / légère), les exercices ne bougent jamais.
- Renfo moyen fessier 3×/semaine, fiche dans `renfo-moyen-fessier.html`.
- Hyrox le jeudi 19h, reprise le 27/08. Hyrox Sprint en double en septembre, **date non confirmée**.
- Montre COROS Pace 4. Route et goudron plat principalement.

## Données physiologiques validées

- **Seuil : 4'42/km à FC 162.** Mesuré au CLM 30 min du 13/08 (20 dernières minutes : 4258 m, FC moy 162, pic 168, allure ajustée 4'46). Bloc complet de 30' : 6209 m soit 4'50 de moyenne. **Valeur probablement conservatrice** : négatif split massif 5'09 / 4'48 / 4'34, le premier tiers a été perdu à chercher l'allure. À pacing correct le test aurait donné ~6320 m, soit un seuil vers 4'38-4'40.
- **FC max 180**, relevée au demi-Cooper du 16/08 (pic en 3 minutes d'effort maximal). Remplace le 178 de juillet. Sans effet sur les zones, ancrées sur le seuil et non sur ce maximum.
- **VMA ≈ 15,8 km/h**, fourchette 15,5 à 16,1. Le demi-Cooper du 16/08 a été interrompu à 3'09 (départ à 16,6 km/h, l'allure d'un 1655 m), mais 869 m en 189 s reste exploitable : un effort maximal de 3 minutes se court à environ 105 % de VMA.
  - **Réserve à connaître** : l'effort ayant été *interrompu*, ce n'est pas un 3 minutes maximal valide, c'est un effort qu'il ne pouvait pas tenir. Le chiffre est un plafond mou. Il est confirmé par ailleurs par le test du 17/07 (6 min max, 1497 m, allure ajustée 3'51 soit 15,6 km/h), ce qui suffit pour l'usage qu'on en fait.
  - **Erreur de méthode à ne pas refaire** : le document précédent justifiait la valeur de 15,8 par le fait qu'elle donnait un rapport seuil/VMA de 81 %, « exactement la fourchette attendue ». Le rapport était censé être le résultat, pas l'argument. Raisonnement circulaire. La conclusion tient parce que deux tests indépendants concordent, pas grâce à ce raisonnement.
- **Seuil = 81 % de VMA** (12,77 sur 15,8). Fourchette normale pour un coureur à faible volume. Le repère de 16,5 km/h (piste 2025) et le chiffre de 77 % qui en découlait sont **périmés** : ils traînaient encore dans le HTML jusqu'au 17/08.
- **VO2max COROS : 53.** Indice calculé sur les courses réelles, cohérent, n'infirme rien.
- **Cadence** : 168 pas/min en footing à 6'30 (foulée 0,93 m, contact 269 ms), 183 au seuil (1,16 m, 220 ms), 186 à 4'34, 193 en effort max. La mécanique se transforme correctement quand l'allure monte, **il n'y a aucun problème de cadence en soi**. Voir la nuance TFL plus bas.

## Pronostic (révisé le 17/08)

Le pronostic de 1h45 « scénario central » posé le 13/08 reposait sur une chaîne à trois maillons dont le deuxième n'a jamais été mesuré : seuil mesuré → **hypothèse** d'un 10 km en 47'20-48'00 → Riegel.

Riegel appliqué directement aux données du CLM :

| Source | 10 km | Semi |
|---|---|---|
| 20 dernières minutes (4258 m / 20') | 49'26 | **1h49'05** |
| Bloc de 30' complet (6209 m) | 49'43 | 1h49'42 |
| Pacing corrigé hypothétique (~6320 m) | 48'48 | 1h47'39 |
| Hypothèse du plan précédent | 48'00 | 1h45'54 |

**La prédiction COROS (49'30 / 1h51), déclarée « périmée » le 13/08, est en fait reproduite par ses propres données.** Le CLM a invalidé l'estimation COROS du *seuil*, fausse de 15 s/km. Il n'a jamais invalidé son estimation de *chrono*, qui sort d'un autre modèle. Les deux ont été confondus.

Contre-vérification par la fraction de vitesse seuil tenable sur 21 km : 1h45 = 94 % du seuil, 1h48 = 92 %, 1h50 = 90 %. Pour une première préparation, plus longue sortie 17 km, jamais couru au-delà de 10 km en compétition, **90 à 92 % est la fourchette honnête**.

**Retenu : 1h48 central, 1h45 plafond, 1h50 mauvais jour et ce n'est pas un échec.** Le 10 km du 04/10 tranche. Conversion Riegel 10 km → semi : 47'00 → 1h43'40 · 48'00 → 1h45'55 · 49'00 → 1h48'10 · 50'00 → 1h50'20, en sachant qu'elle sur-prédit d'environ 2 minutes chez quelqu'un qui n'a jamais couru la distance.

Référence historique : **53'00 sur 10 km en août 2025** (5'18/km), couru à fond.

## Décisions structurantes et leur historique

| Date | Décision |
|---|---|
| 03/08 | Objectif ramené de 1h42 à sous 1h48. Longue sans finish jusqu'à S5. Charge totale chiffrée pour la première fois : 8 à 9 séances/semaine |
| 05/08 | **Consigne de cadence abandonnée** : fenêtre de 2 pas/min ingérable, la cadence est une variable dépendante, aucun effet mesuré. Remplacée par les lignes droites |
| 13/08 | Seuil mesuré. Toutes les zones recalculées. **Suppression des séances VO2max** |
| 14/08 | Phase 2 écrite en détail. Zone « allure semi » ajoutée (148-156) |
| 16/08 | Règle de cible posée : la FC commande, l'allure exécute |
| **17/08** | **Revue critique complète. Sept changements, voir ci-dessous** |
| 20/08 | **Descentes du 22/08 retirées.** La côte du jeudi a été redescendue en courant 4 fois sur 5 : la dose d'habituation était déjà prise, et rien ne doit brouiller le test du 23. L'habituation reprend au 29/08 comme prévu |
| **24/08** | **Test TFL passé.** Première longue avec finish sans aucune sensation, trois jours après 1,7 km de descente courue à 8 %. Aucun changement au plan : le renfo est ce qui produit ce résultat, il ne se relâche pas. Kiné toujours écarté |
| 25/08 | **Stratégie de ravitaillement posée.** Objet réel : entraîner l'estomac, pas nourrir les longues. Premier gel test le 30/08. Horaire de course à répéter à partir de mi-octobre |
| 27/08 | **Divergence artifact/dépôt corrigée.** L'artifact publié contenait depuis le 25/08 des mises à jour jamais reversées dans `index.html` ni donc dans GitHub Pages : la permutation S7/S8 pour le Puy du Fou, du texte affiné sur S5-S6 (parcours plat à Villandraut, finish du 23/08 en montée, etc.), et une section « Reste à traiter » enrichie (nutrition traitée, recommandations de chaussures détaillées : Saucony Endorphin Speed ou Asics Magic Speed en paire d'allure, Pegasus/Ghost/Gel-Cumulus ou Hoka Clifton/Mach si le genou redevient un sujet). **Benjamin suivait donc un plan obsolète sur son téléphone depuis deux jours.** Contenu de l'artifact repris comme base, séance épaule-bras du jeudi appliquée par-dessus, tout republié en un seul geste (dépôt + artifact) |
| 27/08 | **Première séance de seuil de la phase 2 réalisée** (3 × 8' : 4'58/FC150 · 4'46/FC156 · 4'44/FC162, cible 4'42-4'50 à FC 155-163). Bloc 1 sous la cible des deux côtés à la fois, pas juste une allure dure à trouver. Bloc 3 dans les deux cibles, pic FC 167 léger dépassement du plafond 165. Conforme à sa signature de pacing (négatif split), pas un problème. **Nouvelle gêne hanche droite latérale** en toute fin, isolée : surveillance sans changement de plan, voir la section dédiée |
| 27/08 | **Séance épaule-bras avancée au jeudi**, en plus du seuil. Benjamin est encore à Toulouse avec accès salle le 27, puis part à Villandraut où la salle manque. Le vendredi 28/08 ne perd donc plus sa séance haut du corps, seul le renfo fessier (élastique) reste prévu ce jour-là |
| 26/08 | **Seuil du 27/08 maintenu**, malgré la sensation au genou en fin de footing du 26. Le pattern posé le 17/08 tient : c'est la lenteur et la fatigue qui provoquent la compression, pas la vitesse. Le seuil est justement le format où le genou n'a jamais parlé depuis le 13/08. Pas de substitution par une séance jambes non planifiée, qui casserait l'ondulation du bloc sans bénéfice identifié |
| 25/08 | **S7 et S8 permutées.** Le week-end du Puy du Fou (4 au 6/09) tombait sur la longue 1h50 + 5 km de finish. La décharge prévue en S8 remonte sur la semaine du déplacement, la montée descend au 7-13/09. Trajectoire de volume : 41, 44, **31**, 46, 46, 50, 32, soit un cycle 2+1 puis 3+1. Sept jours entre longues au lieu de quatorze. **Hyrox du 03/09 retiré** à la demande de Benjamin, le jeudi devient la séance épaule-bras avancée du vendredi |

### Les sept changements du 17/08

1. **Objectif ramené à 1h48 central** (voir Pronostic). Le 1h45 remis au rang de plafond.
2. **Course ramenée à 4 sorties structurées** (mardi, mercredi, samedi, dimanche) jusqu'à la fin du Hyrox, 5 ensuite quand le jeudi se libère. Volume planifié 44 à 53 km. Les navettes sortent du volume affiché : elles sont trop irrégulières pour servir de base.
   - *Correction du 17/08 au soir* : la première version de cette revue comptait 13 km de navettes par semaine comme un acquis et en déduisait que la sortie longue tombait à 30-33 % du volume. Faux. À 4 sorties, la longue pèse **35 à 38 % et c'est normal** : le repère de 30-35 % suppose 5 à 6 sorties. Il n'y a rien à corriger de ce côté.
3. **Musculation maintenue à 3 séances, contenu inchangé.** La première version proposait de descendre à 2 séances et de réduire la séance jambes à 3 exercices : refusé, à juste titre. Le travail de force améliore l'économie de course chez le coureur de fond et les objectifs Hyrox sont réels. **Le réglage est la charge, pas le contenu** : ondulation sur 3 semaines, semaine légère quand le volume de course est au pic ou qu'un test approche, semaine lourde en décharge de course.
4. **Règle Hyrox ajoutée** : le WOD du jeudi décide du dimanche. Jambes lourdes → longue sans finish. Dominante course → longue normale. Léger → semaine normale.
5. **VMA courte réintroduite**, format 2 × 8 × 30 s / 30 s à 3'50-3'55, en **remplacement** de la séance de seuil, uniquement en semaine de décharge (09/09 et 28/10). Motif : la décision « aucun VO2max » du 13/08 avait été prise sur une VMA de 16,5 et un seuil à 77 %, chiffres corrigés trois jours plus tard à 15,8 et 81 %. La décision n'avait jamais été revisitée. Et le Hyrox, seule source de travail rapide, s'arrête mi-octobre.
6. **Descentes avancées d'octobre à août.** Le plan écrivait lui-même que marcher les descentes « ne prépare à rien » puis reportait l'exposition à octobre. 2 × 200 m à 2-3 % dès le 22/08, progressif.
7. **Post-décharge : retour au niveau précédent, pas un record.** L'ancien plan faisait de S9 un record de volume ET la séance de seuil la plus dure du bloc, quatre jours après une décharge.

### L'arbitrage course / musculation (posé le 17/08)

Quatre journées chargent les jambes : la barre le lundi, le seuil le mercredi, le Hyrox le jeudi, la longue le dimanche. Trois sont non négociables. C'est donc le dimanche qui absorbe, via la règle Hyrox, et c'est le volume de course qui plafonne à 4 sorties.

**Ce qui n'est pas un arbitrage** : retirer de la musculation. La littérature sur l'entraînement concurrent est constante, le travail de force améliore l'économie de course chez le coureur de fond sans dégrader les qualités aérobies quand les séances sont espacées. Le coût vient de la proximité entre force lourde et course dure, pas de la force elle-même.

**Ondulation de la séance jambes, alignée sur le bloc de course :**

| Semaines lourdes | Semaines moyennes | Semaines légères |
|---|---|---|
| S5, S6, S9, S12, S15 | S7, S10, S13 | S8, S11, S14 |

**S16 et S17 sans séance jambes** (Maroc), S18 sans séance jambes (semaine de course). La dernière séance chargée est donc celle du 26/10, en S15. Reprise normale dès le lundi 23/11.

**La semaine du Hyrox Sprint prime sur tout** : séance jambes en préparation spécifique, longue du dimanche sans finish, seuil du mercredi ramené à 2 × 8'. Date encore inconnue, elle tombera entre S6 et S10.

### L'intensité grise, et ce que j'avais surdimensionné

Définition, pour mémoire : l'entraînement utile se répartit entre le **facile** (nettement sous 140, construit sans fatiguer) et le **dur** (au-dessus de 155, déplace le seuil). Entre les deux, environ 140 à 152, une bande où l'effort fatigue presque autant que le dur sans produire son adaptation. On paie le prix sans acheter le produit.

Le retour de salle à FC 146 est dans cette bande, mais l'affirmation « 13 km d'intensité grise par semaine » posée le 17/08 était fausse : seul le retour est concerné, il n'est pas fait toutes les semaines, et cela représente au plus une demi-heure hebdomadaire. Correction gratuite donc à faire, mais mineure.

Là où le principe compte : les footings du mardi et du samedi et la base de la sortie longue. Sur ce point Benjamin est déjà exemplaire, FC 121 à 135 sur toutes les sorties enregistrées depuis juillet.

### Contraintes de calendrier connues

**17 et 18 août, pas d'accès à la salle, et pas de côte sur place.** S5 réorganisée : séance jambes glissée du lundi au mercredi 19, côtes longues maintenues au jeudi 20, **mardi 18 en journée creuse** (repos course, 5 km très facile en option). Une seule séance dure dans la semaine et tout le reste sert le test du dimanche 23.

*Version intermédiaire écartée* : les côtes longues avaient d'abord été avancées au mardi pour dégager quatre jours faciles avant le test. Mauvais arbitrage, corrigé le jour même : ça créait un enchaînement footing lundi, qualité mardi, jambes lourdes mercredi, soit trois jours chargés d'affilée, et ça ignorait l'absence de relief sur place. Trois jours entre la qualité du jeudi et la longue du dimanche suffisent.

**4 au 6 septembre, Puy du Fou en famille (S7).** Petit footing le matin possible, **aucune sortie longue**. Tombe sur le week-end de la longue 1h50 + 5 km de finish. Solution retenue : permuter les structures de S7 et S8, la décharge prévue en S8 remontant sur la semaine du déplacement. Voir la décision du 25/08.

**28 au 30 août, week-end à Villandraut.** Terrain **plat**, aucune descente disponible, et pas de salle donc pas de séance épaule-bras. Course possible sans limite. Conséquences : les 2 × 200 m en descente du 29/08 sont **annulés, non reportés** — le 05/09 prévoit déjà 3 × 200 m et reprend le protocole. Le plat est en revanche une bonne nouvelle pour le finish de la longue du 30, celui du 23 ayant été couru en côte.

**2 au 11 novembre, vacances au Maroc, côte.** Course possible, musculation improbable. Impact réel : quasi nul. S16 était déjà réglée sur jambes légères et S17 sur entretien. **La dernière séance jambes chargée devient celle du 26/10 (S15)**, et il n'y a pas de reprise avant le lundi 23/11.

Ce qui change dans le plan :

| Jour | Avant | Après |
|---|---|---|
| Lun 02/11 | Muscu jambes légère | Voyage, repos ou 5 km |
| Ven 06/11 | Haut du corps | Repos course + renfo complet |
| Lun 09/11 | Muscu jambes entretien | Footing 5 km très facile |
| Mer 11/11 | Séance qualité | Voyage retour, repos complet |
| Jeu 12/11 | Repos complet | **Séance qualité, décalée** |

Consignes spécifiques au séjour, toutes dans le HTML : courir tôt (20 à 24 degrés là-bas contre 8 à 12 le jour de la course), **piloter les blocs rapides à la FC 148-156 et non au chrono** en acceptant 5 à 10 s/km de moins, jamais de course sur le sable, blocs rapides en aller-retour si le vent de mer souffle, boire davantage.

**Seul objet indispensable dans la valise : l'élastique du bloc moyen fessier.** Sans matériel, version de repli : gainage latéral, pelvic drop sur une marche, abduction couchée sur le côté au poids du corps, pont fessier unipodal. Même dosage, même fréquence.

### Le point aveugle de la surveillance

Vérifié le 17/08 sur COROS (codes 100-103, 400, 402, 1200, 9999, du 20/07 au 17/08) : **19 activités, toutes de la course. Zéro musculation, zéro Hyrox.** L'application de musculation n'exporte pas. Donc quand COROS affiche « Optimized » ou un ratio de charge à 0,82, il valide un peu plus de la moitié de l'entraînement réel.

**Palliatif manuel, à tenir** : chaque dimanche soir, une ligne dans ce fichier avec le nombre de séances non courues de la semaine et une note de fatigue des jambes sur 5. Deux semaines de suite à 4 ou 5 → couper une musculation, pas un footing.

## Genou gauche / bandelette ilio-tibiale

**Trajectoire du symptôme, seul indicateur qui compte** :

| Date | Séance | Apparition |
|---|---|---|
| 26/07 | 12,64 km | derniers km |
| 02/08 | 16,62 km avec finish | **km 7-8** (~48 min) |
| 09/08 | 17,03 km sans finish | **3 derniers km** (~85 min) |
| 13/08 | CLM, 55 min dont 30 au seuil | **rien** |
| 16/08 | Demi-Cooper, 3 min à 16,6 km/h | **rien** |
| 20/08 | Côtes 5 × 3' à 8 %, dont ~1,7 km de descente courue | **rien** |
| 22/08 | Footing 6 km seul, descentes retirées | **rien** |
| **23/08** | **16,14 km avec finish, 1h41** | **rien** |
| **26/08** | 9,36 km, footing + test cadence, fin en côte + ligne droite | **sensation désagréable**, en toute fin (côte du retour + dernière ligne droite courue en côte) |
| **27/08** | Seuil 3 × 8' à 4'42-4'50 | **rien au genou gauche.** Le seuil reste le format muet, comme prévu par la lecture mécanique. La gêne du jour est apparue à la *hanche droite*, autre structure, voir section dédiée |

**Lecture du 26/08** : le schéma est cohérent avec la lecture mécanique du 17/08, pas un nouveau signal. Deux jambes fatiguées différemment sur cette sortie : 15 premières minutes en **descente rapide** (2,5 km à 5'58/km pour seulement FC 127, la pente masque l'effort en fréquence cardiaque mais charge davantage mécaniquement), puis fin de séance sur jambes déjà sollicitées avec une **côte** et un sprint de 20 s dedans (FC pic 163 sur les 10 dernières minutes, cadence retombée à 162 juste avant, signe de fatigue). Aucune sensation pendant les 30 minutes de travail de cadence au milieu, sur terrain plat. **Pas de douleur qui modifie la foulée** : règle de tri, on continue en surveillant, pas de déclenchement kiné.

**Attribution prudente** : l'amélioration du 09/08 vient surtout de la charge réduite (plus court, sans finish, plus lent). Le bloc renfo n'avait qu'une semaine, il en faut 3 à 4. La sensation est repoussée, pas résolue.

**Lecture mécanique ajoutée le 17/08.** Le plan concluait « c'est la durée, pas l'allure ». C'est à moitié vrai. Le syndrome est une **compression** autour de 30° de flexion du genou : courir lentement fait passer plus de temps près de cet angle avec un temps de contact plus long, et courir vite provoque généralement moins. Le pattern de Benjamin (rien à 4'42 ni à 3'37, tout à 6'20) colle exactement. Son allure facile à 6'20-6'30, cadence 168, contact 269 ms, est à peu près la condition la plus provocante possible.

**Conséquence : la question cadence est rouverte, mais étroitement.** L'abandon du 05/08 restait juste sur ses propres termes (économie de course, fenêtre ingérable). Mais le ré-entraînement de cadence pour la bandelette est une intervention *de course lente*, et c'est un des leviers les mieux documentés. **Test le 23/08 : sur les 20 dernières minutes de la longue, monter vers 176 pas/min. Pas de fenêtre à tenir, pas de surveillance montre.**

**Décision du 17/08 : pas de kiné pour l'instant.** Surveillance et renfo appliqué correctement. Déclencheur d'un rendez-vous : douleur latérale croissante qui modifie la foulée.

**Règle de tri** : sensation = continuer en surveillant. Douleur latérale croissante qui modifie la foulée = arrêt.

**Renfo, bloc de référence (4 exercices)** : monster walk, abduction debout élastique, pelvic drop, gainage latéral. Lundi complet, mercredi et vendredi version courte (pelvic drop + gainage), dimanche monster walks en activation. Clamshell optionnel, doublon.
**Renfo confirmé le 24/08** : Benjamin exécute bien le bloc de 4 exercices (élastique), pas une séance de salle. C'est ce bloc, et lui seul, qui a produit le résultat du 23/08.
**À partir de S9 (mi-septembre), charger le bloc maison** : fentes bulgares au poids du corps 3 × 8/jambe et step-down excentrique 3 × 10/jambe sur une marche. **Dans le bloc maison, pas dans la séance de salle**, qui ne bouge pas. Un bloc élastique en endurance a fait ce qu'il pouvait faire au bout de 6 semaines.

Le step-up existant devient un exercice de moyen fessier sans changer l'exécution : surveiller que le bassin du côté libre ne descend pas et que le genou d'appui ne rentre pas.

## Hanche droite latérale (nouveau, 27/08/2026)

Première apparition d'une **gêne latérale à la hanche droite**, en toute fin de la séance seuil du 27/08 (3 × 8'). C'est un signal **distinct du genou gauche** : autre côté, plus haut, structures différentes (autour du grand trochanter, soit le moyen fessier, le tenseur du fascia lata proximal, ou la bourse). **Ne pas le confondre avec la bandelette gauche**, c'est une ligne de surveillance séparée.

**Lecture prudente au 27/08** : un seul épisode, en fin de séance dure, décrit comme une **gêne** et non une douleur. Par la règle de tri déjà en place (gêne ou sensation = continuer en surveillant ; douleur latérale croissante qui modifie la foulée = arrêt), c'est **surveiller, pas alerter**. Aucun changement au plan pour un épisode isolé.

**Ce qui rassure** : le bloc moyen fessier (monster walk, abduction élastique, pelvic drop, gainage latéral) travaille déjà **les deux côtés**. Le côté droit est donc déjà chargé en renfo, rien à ajouter dans l'immédiat.

**À caractériser à la prochaine occurrence** (questions posées à Benjamin le 27/08, réponses à consigner) : localisation exacte (sur l'os saillant = moyen fessier ou bourse ; plus en avant et mou = tenseur du fascia lata), moment d'apparition (seulement fin de séance dure, ou aussi footing lent), persistance après l'effort, et gêne à s'allonger sur ce côté la nuit.

**Déclencheur d'attention** : si la gêne réapparaît sur le **footing lent du 29/08** (donc hors effort dur) ou sur la **longue du 30/08**, elle devient un motif de suivi actif et entre dans le plan. Un épisode unique en toute fin de séance seuil, non.

## Nutrition et ravitaillement

**Décidé le 25/08.** Le sujet n'est pas de nourrir les sorties longues, c'est d'**entraîner le tube digestif** avant la course. Le semi durera 1h48, soit la durée des sorties longues, mais à 5'05/km au lieu de 6'30 : la dépense glucidique y est bien supérieure et l'oxydation des lipides ne compense plus. Un gel jamais testé pris à allure de course est un moyen fiable de se fabriquer des troubles gastriques au km 15.

Repères : les réserves de glycogène couvrent 90 à 120 min d'effort. Consensus de 30 à 60 g de glucides par heure entre 1h et 2h30. Les longues actuelles, plafonnées à 1h50 et courues à FC 132, passent sans apport, ce que confirment les sorties enregistrées (aucune fringale sur 1h41 le 23/08).

**Progression retenue :**

| Quand | Protocole | Objet |
|---|---|---|
| Dès le 30/08, longues avec finish | **1 gel (~25 g) vers la 50e minute**, avec de l'eau | Tolérance, rien d'autre |
| À partir de S13 (longues avec 8 à 12 km à allure course) | 2 prises, vers 45 min et 1h20 | Le besoin devient réel |
| S14 (25/10) et S16 (08/11), longues de 2h00 | 2 à 3 prises | Figer le protocole définitif |
| Course, 22/11 | 2 à 3 gels vers 40 min, 1h05 et 1h25 | Exécution de ce qui a été répété |

**Règle** : toujours tester avec le produit exact prévu pour la course. Même marque, même goût, même texture. La tolérance est très individuelle.

**Horaire, point à ne pas oublier** : Benjamin part courir vers 10h15-10h30, y compris le dimanche. Le départ de la course est à **9h**, soit un petit-déjeuner vers 6h30-7h, une heure et demie plus tôt que son habitude. À partir de la mi-octobre, caler **au moins deux longues sur l'horaire de la course**, avec le même petit-déjeuner. La sortie du 03/11 au Maroc est déjà prévue tôt le matin.

## Séances réalisées

| Date | Séance | Distance | Allure | FC | Note |
|---|---|---|---|---|---|
| 22/07 | Test FC max côte | 6,5 km | — | 132 (pic 178) | Validé |
| 26/07 | Longue S1 | 12,64 km | 6'26 | 132 | 1re sortie disciplinée |
| 28/07 | Côtes courtes S2 | 8,03 km | 5'56 | 141 | |
| 29/07 | Footing court | 4,25 km | 5'39 | 129 | |
| 31/07 | Footing facile | 8,75 km | 6'10 | 135 | Pile au plafond |
| 02/08 | Longue + finish (NovaBlast) | 16,62 km | 6'23 | 132 | Record distance. TFL km 7-8 |
| 04/08 | Footing + test cadence | 8,46 km | 6'30 | 124 | Cadence inchangée à 168 → consigne abandonnée |
| 06/08 | Côtes longues 4 × 3' | 8,38 km | 6'40 | 134 | Descente marchée |
| 07/08 | Footing récup (non planifié) | 6,54 km | 7'11 | 121 | Ajouté un jour de repos |
| 09/08 | Longue sans finish | 17,03 km | 6'21 | 132 | 1h48. TFL sur 3 derniers km seulement |
| **13/08** | **Contre-la-montre de 30 minutes** | 10,09 km | 5'27 (bloc 4'50) | 144 | **Seuil 4'42 à FC 162.** Charge 180 |
| 16/08 | Demi-Cooper **avorté à 3'09** | 3,28 km | 3'37 sur le bloc | 169 sur le bloc | **Pic 180 = FC max.** VMA ≈ 15,8. Genou RAS |
| 18/08 | Footing + 5 lignes droites (séance du lundi 17, décalée) | 9,48 km | 6'07 (base à 127) | 129 | Base impeccable, cadence 171 et contact 261 ms. Lignes droites justes : 4'05-4'22 de moyenne sur 20 s, foulée 1,28 m. **Récupérations trotées au lieu d'être marchées**, 196 puis 253 m, FC montée à 149 sur la dernière |
| 20/08 | Côtes longues 5 × 3' (dernière de la prépa) | 7,84 km | 6'54, D+ 229 m | 133 | Blocs à FC 147, 154, 155, 155, 157 : pile dans la cible 155-163. **Pente réelle 8 %**, le plan en prévoyait 3 à 6. **Descente courue 4 fois sur 5**, 2'30 étant insuffisant pour 450 m à 8 % : ~1,7 km de descente non planifiée trois jours avant le test. Bonnes sensations, genou muet |
| 22/08 | Footing seul | 6,05 km | 6'09 | 135 | Descentes retirées comme décidé le 20/08. **Le nom de la séance sur COROS est celui du programme initial, pas de son contenu réel** : ne jamais déduire le contenu d'une séance de son titre |
| **23/08** | **Longue + finish. LE test TFL** | 16,14 km | base 6'33 (FC 132) · finish 3,63 km à 5'17 (FC 158) | 137 | **Aucune sensation au genou.** Finish : 2 derniers km à 5'02-5'03 corrigés de la pente, mais FC 165 et pic 168. Cadence 179 sur le finish, donc **test cadence non concluant**, à refaire en course lente |
| 26/08 | Footing + test cadence 176 | 9,36 km | 6'04 (15' d'ouverture en descente à 5'58, FC 127 seulement) | 137 | Cadence moy 171, blocs et lignes droites entre 176 et 181 : **cible tenue**. Fin en côte + 1 ligne droite en côte, FC pic 163. **Sensation désagréable au genou gauche en toute fin**, voir tableau TFL |
| **27/08** | **Seuil 3 × 8', première de la phase 2** (+ épaule-bras) | 10,06 km | bloc 1 : 4'58 · bloc 2 : 4'46 · bloc 3 : 4'44 | bloc 1 : 150 (pic 158) · bloc 2 : 156 (pic 165) · bloc 3 : 162 (pic 167) | Cible 4'42-4'50 à FC 155-163. **Bloc 1 sous la cible des deux côtés** (allure et FC), pas seulement une allure dure à trouver. **Bloc 3 dans les deux cibles à la fois**, allure et FC, mais pic 167 dépasse le plafond mental de 165. Meilleur km 4'42 (= seuil mesuré). **Gêne à la hanche droite latérale en toute fin**, non mesurable par COROS. COROS étiquette la séance « Performance: Poor », lecture algorithmique à ne pas sur-interpréter (tire sans doute sur le bloc 1 sous-effort) |

### Volume hebdomadaire

Colonnes en **volume utile hors navettes**. À partir de S5, les volumes du plan sont ceux des **sorties structurées**, même convention : les navettes s'ajoutent quand elles sont faites, entre 0 et 9 km.

| Semaine | Utile | Sorties | Plus longue |
|---|---|---|---|
| 29/06-05/07 | 23,2 | 3 | 10,0 |
| 06/07-12/07 | 27,0 | 3 | 10,7 |
| 13/07-19/07 | 31,4 | 3 | 13,5 |
| S1 20-26/07 | 19,1 | 2 | 12,6 |
| S2 27/07-02/08 | 37,6 | 4 | 16,6 |
| S3 03-09/08 | ~40 (33 visés) | 5 | 17,0 |
| S4 10-16/08 | ~10 (décharge + 2 tests) | 4 | 10,1 |
| S5 17-23/08 | **39,5** | 4 | 16,1 |

**Palliatif manuel, S5** : 3 musculations non faites sur 3 (jambes, pec-dos, épaule-bras), remplacées par un benchmark CINDY le vendredi. Course : 4 sorties sur 4. **Fatigue des jambes : 1/5**, déclarée le 24/08, aucune fatigue résiduelle. La seule lourdeur ressentie était aux genoux en fin de longue le 23, le reste des jambes peu marqué. Aucun déclencheur de la règle « deux semaines à 4 ou 5 ».

**Musculation en S5** : pas de séance jambes à la barre, mais un benchmark CINDY (AMRAP 20', ~250 air squats) le **vendredi 21/08, deux jours avant le test**. S5 n'était donc pas une semaine sans charge musculaire, et le test du 23/08 a été passé sur des jambes déjà marquées. Cela **renforce** sa lecture, et explique la lourdeur des deux genoux signalée en fin de longue — fatigue des quadriceps, sans rapport avec le TFL.

**État physiologique au 17/08** : récupération 100 %, FC repos stable 42-45, ratio de charge 0,82 (« Maintaining »), VFC baseline 74-75 avec plage normale 68-80. Deux nuits sous la plage la semaine des tests (63 le 13/08, matin du CLM ; 66 le 15/08). La décharge S4 a fonctionné.

## Tests : protocoles et leçons

**Contre-la-montre de 30 minutes** — échauffement 15' puis **3 laps de 10'** puis retour au calme 10'. Lecture : allure et FC moyennes des **20 dernières minutes**. Les 10 premières sont ignorées, ce qui absorbe un départ mal calé. Le découpage en trois laps donne la dérive segment par segment : à conserver tel quel pour le retest.
Pacing corrigé pour un prochain CLM : 0-10' à 4'45, 10-20' à 4'40, 20-30' tout ce qui reste. Ne pas dépasser 165 avant la 10e minute. Route plate, pas de piste (quinze tours font trente virages à gauche, hanche intérieure en adduction, mauvais pour la bandelette).

**Leçon de pacing, valable partout** : deux tests, deux erreurs opposées (27 s/km trop lent le 13/08, trop rapide le 16/08). Cause commune, l'absence de repère externe au départ.
- Sur piste : courir **au temps par tour de 400 m**, jamais à l'allure de la montre. 96 s = 1500 m · 93 s = 1550 · 90 s = 1600 · 87 s = 1650.
- Sur route : afficher **l'allure moyenne du lap** et la FC, jamais l'allure instantanée qui réagit trop lentement. Se caler sur la FC dans les 5 premières minutes.

**Aucun test programmé d'ici le 10 km du 04/10.** Le 10 km est un meilleur test que tout ce qu'on pourrait construire.

## Récupération des données COROS (pour l'assistant)

Connecteur **en lecture seule**. Outils à charger via `tool_search` avant usage (deferred).

- **`querySportRecords`** — liste les séances. `startDate`/`endDate` (AAAAMMJJ), `limit` (max 20), `sportTypeCodes` (course = `[100]`, tout = omettre), `minDistanceKm`. Renvoie distance, allure, FC moyenne, le **`labelId`** et la **Time Window** (timestamps Unix).
- **`getActivityDetail`** — `labelId` + `sportType` (100). Allure ajustée, meilleur km, cadence, foulée, puissance, charge, effets aérobie/anaérobie, dénivelé. **Ne donne pas le pic de FC.**
- **`queryCustomActivityLapData`** — pic de FC (`maxHr`) sur une fenêtre précise. `labelId`, `sportType`, `startTimestamp`, `endTimestamp`. Indispensable pour valider un effort maximal.
- **`querySleepHrv`** — VFC nocturne. Utiliser l'évaluation officielle (moyenne, plage normale, baseline), pas la moyenne des points bruts. Les dates sont des **jours de réveil**.
- **`queryRecoveryStatus`**, **`queryRestingHeartRate`**, **`queryTrainingLoadAssessment`** — état instantané, FC repos, ratio de charge.

**Méthode pour analyser une séance** : `querySportRecords` sur la date → récupérer `labelId` et Time Window → `getActivityDetail` → si effort intense, `queryCustomActivityLapData` sur la fenêtre finale pour le pic de FC.

**Piège à connaître** : `queryTrainingLoadAssessment` ne voit que la course. Voir « Le point aveugle de la surveillance ».

Départs habituels autour de 43.597, 1.466 (domicile Toulouse). Les navettes apparaissent comme des runs de 2,1 à 2,2 km.

## Documents du repo

Le repo est publié en GitHub Pages sur **<https://bensaintsever.github.io/prea-semi-benja/>**, et le plan est une **application web installable** (PWA).

| Fichier | Rôle |
|---|---|
| `index.html` | **Le plan.** S5 à S18 jour par jour, s'ouvre sur la séance du jour. Document de référence |
| `manifest.webmanifest` | Métadonnées de l'application installable : nom, icônes, couleurs, mode plein écran |
| `sw.js` | Service worker. Réseau d'abord pour les pages, cache en secours. Rend le plan lisible hors ligne |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | Icônes de l'application |
| `Suivi_Semi_Toulouse.md` | Ce fichier. Mémoire de passation, données brutes, raisonnements, méthode COROS |
| `renfo-moyen-fessier.html` | Fiche d'exécution des 4 exercices, schémas et erreurs classiques |
| `211_km_officiel_2025-...gpx` | Tracé officiel. Malgré le nom, **c'est bien le parcours 2026** (fiche Openrunner modifiée le 01/07/2026) |
| `Plan_Semi_Toulouse_Phase1_2.pdf` | **Obsolète**, vise encore Toulouse au 1er nov. À supprimer |

## Application installable (PWA)

Mise en place le 17/08. Le plan s'installe sur téléphone et fonctionne **sans réseau**.

- **Android et Chrome bureau** : un bouton « Installer l'application » apparaît dans l'en-tête quand le navigateur le propose.
- **iPhone** : Safari, bouton Partager, « Sur l'écran d'accueil ». Il n'existe pas d'API d'installation sur iOS, c'est la seule voie.
- Une pastille orange **« hors ligne, plan en cache »** s'affiche dans l'en-tête quand il n'y a pas de réseau.

**Stratégie de cache** : réseau d'abord pour les pages, donc le plan affiché est toujours à jour dès qu'il y a du réseau, et le cache ne sert que de secours. Les ressources (icônes, manifeste, fiche renfo) sont servies depuis le cache en priorité.

**Contenu mis en cache** : `index.html`, `renfo-moyen-fessier.html`, le manifeste et les trois icônes. Le GPX et le PDF ne le sont pas, trop lourds pour un gain nul.

**Pour l'assistant, à ne pas oublier** : `sw.js` contient une constante `VERSION` calculée à partir du contenu de `index.html`. **Toute modification du plan impose de régénérer `sw.js`**, sinon les téléphones déjà installés continuent de servir l'ancienne version depuis leur cache. Le changement de version purge automatiquement les caches précédents.

**Cas d'usage principal** : le séjour au Maroc du 2 au 11 novembre. Le plan reste consultable sans données mobiles, y compris la fiche des exercices de renforcement.

## Conventions de rédaction

- Ne jamais utiliser la syntaxe `--`.
- Écrire « pas/min », jamais « spm ». **Expliciter les sigles** : écrire « retour au calme » et non « RAC », « échauffement » et non « éch », « contre-la-montre » et non « CLM ». Un glossaire est en tête de la section Zones du HTML, il fait foi.
- Le HTML est le document vivant, ce `.md` est la mémoire. Ne pas dupliquer le contenu du plan ici.

---

## Annexe — sujets non traités

**Nutrition de course** (ouvert depuis le 03/08). Départ 9h, 1h48 d'effort. Petit-déjeuner à fixer et tester sur les longues de S14 et S16, décision gels et boisson.
**Chaussures.** Une seule paire vivante : **NovaBlast 5**, drop ~8 mm, mises en service **fin juillet** après une transition d'une semaine et demie. Pegasus 38 mortes (800-1200 km).

**Compteur au 24/08/2026 : ~156 km.** Estimation par cumul des sorties COROS depuis le 26/07, navettes comprises. Borne haute assumée : pour l'usure, mieux vaut surestimer. COROS n'expose aucun suivi d'équipement via MCP, le compteur se tient donc à la main ici. Fourchette réelle 120 à 156 km selon la part des sorties de transition.

**Projection.** Le plan prévoit 543 km de S6 à S18. Avec une seule paire, les NovaBlast arriveraient au jour de la course à **~700 km**, soit la limite haute de leur durée de vie (600 à 800 km). **Il ne faut donc pas courir le semi avec cette paire.**

**Achat calé au 26/09/2026** (anniversaire). Décidé le 25/08. La NovaBlast aura alors 372 km, en pleine forme, et **le 10 km du 04/10 se courra avec elle** : huit jours sont trop courts pour découvrir une plaque sur une course à fond, a fortiori avec une bandelette sous surveillance. Rodage de l'Endorphin à partir du 06/10, puis sur les blocs à allure course de S13 et S14. Elle arrivera au 22/11 avec 80 à 115 km, rodée et fraîche. La NovaBlast finit la préparation vers 585-615 km : **surveiller la sensation dès 450 km, soit mi-octobre**.

**Deux actions ouvertes, à traiter maintenant :**
1. **Acheter la deuxième paire.** L'objet n'est pas d'économiser la première : c'est de varier les contraintes mécaniques, ce qui compte avec une bandelette sous surveillance. En alternant, la NovaBlast finit la préparation vers 430 km et la seconde vers 270 km, toutes deux confortablement dans leur vie utile.
2. **Choisir la chaussure de course et la roder sur un finish avant fin octobre.** Même logique que les gels : rien de neuf le jour J. Une paire à plaque demande deux ou trois sorties avec allure spécifique dedans.

Le signal de fin de vie n'est pas le compteur mais la sensation : semelle sèche, jambes plus marquées après un footing ordinaire.
**Date du Hyrox Sprint.** Non confirmée, tombera dans S6-S10. La semaine concernée perd sa longue avec finish et son seuil passe à 2 × 8'.
**Sommeil et poids.** Données disponibles, jamais exploitées.
