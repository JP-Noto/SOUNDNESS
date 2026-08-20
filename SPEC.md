# SPEC SOUNDNESS

`Statut : hypothèse instruite, 0.0.3. Le normatif se dit à l'indicatif ; le rang de l'ensemble
reste hypothèse tant qu'aucun déploiement réel n'a eu lieu.`

## Termes

- **pièce** : le document qui fait foi, immuable ; une nouvelle version d'un document est une
  nouvelle pièce.
- **fiche** : le produit d'une extraction, jamais un original ; elle vit, la pièce demeure.
- **template** : la structure qui donne sa forme à une fiche ; il appartient à une famille.
- **famille** : un ensemble de pièces reconnaissables par un même test d'appartenance ; elle
  naît par acte (S1.5) et porte un validateur nommé.
- **règle-mère** : le sommet du template d'une famille, le plus petit schéma utile.
- **ramification** : l'ouverture d'une sous-famille dans l'arbre des templates.
- **promotion** : l'acte qui change le régime d'un champ, variable vers constante.
- **statut d'extraction** : l'état de confiance d'une fiche, née conforme, extraite, curée,
  validée.
- **déclaration de dépôt** : la qualification d'une pièce à son entrée, sur les axes que
  l'utilisateur déclare ; le canal, lui, est constaté par le système.
- **canal officiel** : le dépôt émis nativement par le circuit du template officiel d'une
  famille, signature électronique et identifiants portés ; attribut vérifié par le système,
  jamais déclaré par l'utilisateur. Un scan n'arrive jamais par le canal officiel.
- **template light** : la règle-mère plus les champs que les obligations déclarées de la
  famille rendent obligatoires, rien de plus.
- **curation** : le geste humain qui reprend une extraction.
- **validateur de famille** : l'humain nommé qui décide pour une famille : ses actes
  structurels et la validation de ses fiches. Le profil peut nommer des validateurs de fiches
  distincts, sous le même périmètre.
- **profil d'application** : le document qui porte les réglages qu'un déploiement fait des
  paramètres délégués par cette SPEC (S8) ; sans profil, les défauts de la SPEC s'appliquent.

## Les affirmations

- **A1, la dualité.** La fiche est le produit d'une extraction, jamais un original ; chaque
  fiche renvoie à sa pièce, seule opposable ; tout avis fondé sur une consultation se trace.
- **A2, la règle-mère.** Le sommet est le plus petit schéma utile : une constante
  d'appartenance et un premier champ à forte valeur métier ; l'identité des instances est portée
  par le renvoi à la pièce, jamais par le sommet.
- **A3, la ramification.** Croissance en arborescence calquée sur la logique métier ; la
  précision se gagne par les validations accumulées au fil de l'usage ; le volume seul ne
  promeut rien.
- **A4, le spectre et le statut.** Du document né conforme au brouillon manuscrit ; le statut
  d'extraction voyage avec la donnée ; au sommet, l'extraction tend vers la lecture.
- **A5, la part humaine.** Réglée, jamais paritaire par principe ; déclarer, curer, valider,
  promouvoir ; on ne cure que ce qui le mérite ou ce qui s'est déclaré difficile ; le réglage
  change combien la machine propose, jamais qui décide.

## S1 — L'élection du sommet, et la naissance des familles

- **S1.1** Le sommet d'une famille contient exactement deux choses : la constante
  d'appartenance, c'est-à-dire le type de la famille avec son test d'appartenance déclaré (à
  quoi l'on reconnaît qu'une pièce en est), et un premier champ à forte valeur métier.
- **S1.2** Le premier champ s'élit par ce critère, dans cet ordre : le champ qu'exige la
  première obligation applicable à la famille, les obligations s'ordonnant légale, puis
  contractuelle, puis de gestion ; à défaut, le champ que le métier demande en premier quand on
  lui présente une pièce de la famille, établi sur l'usage tracé. À rang égal, l'acte humain
  motivé tranche. L'élection est un acte de validation, daté, motivé, révisable par le même
  chemin.
- **S1.3** Le sommet ne porte aucun identifiant d'instance : l'identité est portée par le renvoi
  à la pièce (A1). Un champ d'identifiant métier (numéro de facture, numéro de marché) peut
  exister plus bas dans le template, comme champ ordinaire.
- **S1.4** Le sommet ne change que par acte de validation de niveau famille. Sa modification
  ouvre une revue des fiches existantes de la famille ; elle n'en invalide aucune d'office.
- **S1.5** Une famille naît par acte de validation, comme le reste (S3.1). L'acte de naissance
  porte trois choses, et sans les trois il n'y a pas de famille : le test d'appartenance, le
  premier champ élu (S1.2), et le validateur nommé. Une famille sans validateur ne valide rien,
  fiches comprises.

## S2 — La ramification

- **S2.1** L'arbre des templates est taxonomique : une branche est une sous-famille de pièces,
  jamais une section de document. La décomposition en sections, champs et groupes de champs vit
  à l'intérieur d'un template ; elle ne crée pas de nœud dans l'arbre. Une branche se reconnaît
  à ceci qu'elle porte son propre test d'appartenance.
- **S2.2** Une branche s'ouvre quand trois pièces réelles au moins ont exigé des champs que le
  reste de la famille n'exige pas, et que ces pièces se reconnaissent par un test d'appartenance
  propre. Jamais par anticipation : une branche spéculative est une dérive nommée. Le seuil de
  trois est le défaut ; le profil peut le régler (S8).
- **S2.3** On ne descend d'un étage de l'arbre que si une obligation déclarée ou un usage tracé
  le consulte. Un étage que rien ne consulte pendant la durée du profil (défaut : un an) est un
  candidat à la fusion avec son parent, par acte de validation.
- **S2.4** Promotion et ramification ne se confondent pas, leurs axes diffèrent. La promotion
  joue sur l'axe des valeurs : un champ déjà présent dont la valeur s'avère invariante dans la
  famille devient constante. La ramification joue sur l'axe des populations : un champ qui ne
  vaut que pour une sous-population reconnaissable appelle une branche. Un même constat ne peut
  ouvrir que l'un des deux, selon cet axe.

## S3 — La promotion

- **S3.1** Toute création de famille, toute promotion, toute ouverture de branche, tout ajout
  de champ est un acte de validation au sens de LIVING REFERENCE : décidé par un humain
  habilité, daté, tracé avec son motif. Rien n'est automatique.
- **S3.2** Le système propose, il ne promeut pas. Il signale quand le seuil de signalement du
  profil est atteint (défaut : trois pièces) : ce champ porte la même valeur sur n pièces, ce
  champ manque sur telle sous-population. Le volume fonde des propositions, jamais des
  décisions.
- **S3.3** Le décideur est le validateur de famille, nommé par périmètre (S1.5).
- **S3.4** L'acte de promotion porte : quoi, qui, quand, le motif, et les pièces d'appui qui ont
  fondé la proposition.
- **S3.5** La rétrogradation suit le même chemin : une constante contredite par une pièce réelle
  redevient variable par acte tracé, jamais silencieusement, et la pièce contradictoire est
  citée dans l'acte.

## S4 — Le statut d'extraction, un automate

- **S4.1** Une fiche porte un statut et un seul à tout instant. Le statut est servi avec la
  fiche : ce que lit l'IA porte la confiance de ce qu'elle lit.
- **S4.2** Les transitions, et rien d'autre :
  - dépôt par le canal officiel → **née conforme** ;
  - tout autre dépôt, après extraction machine → **extraite** ;
  - extraite ou née conforme → **curée**, par geste de curation ; une fiche née conforme
    corrigée avant validation passe par là, comme les autres ;
  - née conforme, extraite ou curée → **validée**, par acte de validation, jamais implicite :
    la signature officielle est un attribut de la pièce, la validation est un acte sur la
    fiche ; valider, c'est engager l'usage en référence, pas constater une lecture ; pour une
    fiche née conforme, l'acte peut être une confirmation d'un geste ;
  - validée → **curée**, par toute correction : une fiche corrigée redescend et se revalide.
- **S4.3** Le statut ne monte jamais par écoulement du temps ni par volume.
- **S4.4** Le profil peut déclarer un statut plancher en dessous duquel une fiche ne se sert
  pas à l'IA pour tel usage (défaut : aucun plancher, le statut voyageant toujours).
- **S4.5** Le journal des transitions s'ajoute et ne se réécrit pas, dans le régime de
  conservation déclaré.
- **S4.6** Faire redescendre une fiche validée est réservé aux identités habilitées du
  périmètre ; toute curation porte son auteur (S6.4).

## S5 — La déclaration de dépôt

- **S5.1** Trois axes. La **nature**, déclarée, à choix multiples : native structurée, native
  libre, scannée, manuscrite ; une pièce peut en cumuler, un bon de livraison scanné à
  signature manuscrite est scanné et manuscrit. La **difficulté**, déclarée, binaire :
  ordinaire ou difficile. Le **canal**, constaté par le système, jamais déclaré : officiel ou
  libre.
- **S5.2** La table de départ s'évalue dans cet ordre, et la première ligne qui s'applique
  l'emporte :
  1. difficulté difficile, quels que soient nature et canal → template light, statut extraite ;
  2. nature comportant scannée ou manuscrite, quel que soit le canal → template plein,
     statut extraite, tamis de S6.2 ;
  3. canal officiel → entrée directe, statut née conforme ; un scan n'y accède jamais, le
     canal étant un constat du système ;
  4. nature native structurée → template plein, statut extraite ;
  5. nature native libre → template plein, statut extraite.
  L'ordre est un ordre de prudence : en cas de cumul, la pièce suit la ligne la plus prudente,
  jamais la plus flatteuse.
- **S5.3** L'absence de déclaration vaut ordinaire, et le système propose la nature qu'il
  détecte ; la proposition se confirme d'un geste.
- **S5.4** Une déclaration erronée se détecte : si l'extraction n'atteint pas les attentes du
  template de départ, champs obligatoires introuvables, le système redéclasse la pièce en
  difficile, le signale, et trace l'écart. Il ne corrige jamais une déclaration en silence. La
  fiche entamée se resserre alors au template light ; les champs déjà extraits hors light sont
  conservés en propositions, marqués comme telles, et attendent la curation.

## S6 — La curation

- **S6.1** La machine propose toujours d'abord, même mal, même partiellement : l'humain ne part
  jamais d'une page blanche. Sur pièce lisible, curer c'est corriger la proposition ; sur pièce
  difficile, curer c'est compléter ce que la machine a pu proposer.
- **S6.2** Est due, et seulement elle : la curation de toute pièce déclarée ou redéclassée
  difficile ; celle des champs extraits de zones scannées ou manuscrites (c'est le sens du
  renvoi de la ligne 2 de S5.2) ; celle de tout champ sous le seuil de confiance du profil
  (défaut : quatre-vingt-dix centièmes) ; celle de tout champ qu'une obligation déclarée rend
  obligatoire et qui manque. Le reste ne se cure pas d'office : le tamis vaut pour les fiches
  comme pour les traces.
- **S6.3** Chaque curation est conservée comme paire, proposé et corrigé, rattachée au
  template : c'est la matière des signalements de S3.2. Elle n'enseigne aucun modèle
  d'extraction si le profil l'interdit, données confidentielles en tête (défaut : interdit).
- **S6.4** La curation se trace : qui, quand, quels champs.

## S7 — Le sommet du spectre

- **S7.1** La dualité survit au sommet. Même née conforme, la pièce reste distincte de sa
  fiche : la pièce est immuable et opposable, signée, scellée ; la fiche est vivante, statuts,
  liens, annotations, et c'est elle qui sert. Ce qui tend à se confondre est le contenu, jamais
  le régime.
- **S7.2** Une fiche née conforme peut être produite par lecture intégrale ; elle porte quand
  même son statut et son renvoi à la pièce, et se corrige par S4.2 comme les autres.
- **S7.3** Si le template officiel d'un document et le template de la famille divergent, la
  pièce fait foi, et l'écart ouvre une proposition de révision du template. On ne corrige
  jamais une pièce signée.

## S8 — Le profil d'application

- **S8.1** Le profil d'application est un document du déploiement, lisible comme le reste. Il
  naît et se révise par acte de validation de l'opérateur du déploiement, daté et motivé.
- **S8.2** Il porte nommément, et seulement, les paramètres que la SPEC lui délègue : le seuil
  de ramification (S2.2, défaut trois), la durée de fusion (S2.3, défaut un an), le seuil de
  signalement (S3.2, défaut trois), le statut plancher par usage (S4.4, défaut aucun), le seuil
  de confiance (S6.2, défaut quatre-vingt-dix centièmes), l'autorisation d'apprentissage
  (S6.3, défaut interdit), et les validateurs de fiches délégués (Termes, validateur de
  famille).
- **S8.3** Sans profil, les défauts de la SPEC s'appliquent tels quels : l'absence de profil
  n'est jamais un vide, c'est le défaut.

## Falsification

Les conditions R1 à R4 de la note de chantier demeurent, révisées à chaque version. S'y
ajoutent :

- **R5.** Si une instanciation réelle exige, à un pas quelconque, une décision que S1 à S8 ne
  fournissent pas, la famille de règles concernée est incomplète et le dit.
- **R6.** Si l'axe de S2.4, valeurs contre populations, ne suffit pas à trancher un cas réel
  entre promotion et ramification, S2.4 est réfuté.
- **R7.** Si le maintien du tamis S6.2 produit des fiches validées fausses en usage réel, le
  tamis est mal calibré et sa règle doit être reprise.
- **R8.** Si deux lignes de la table S5.2 peuvent s'appliquer à une même pièce avec des effets
  différents malgré l'ordre de prudence, S5.2 est réfuté.
