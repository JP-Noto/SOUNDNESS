# WHITEPAPER SOUNDNESS

`Statut : hypothèse, 0.0.5. Ce papier donne le pourquoi ; le normatif vit dans la SPEC, qui
prime. Le français fait foi.`

## La thèse

Quand une machine extrait du savoir de documents, la confiance ne peut pas vivre dans la
copie : elle vit dans le chemin qui relie la copie à ce qui fait foi. SOUNDNESS soutient qu'un
système d'extraction digne de confiance tient sur trois engagements, et qu'aucun des trois ne
suffit sans les deux autres :

1. **la dualité** : la fiche extraite n'est jamais l'original ; elle renvoie à sa pièce, seule
   opposable, et tout avis fondé sur une consultation se trace ;
2. **le template vivant** : la structure qui range les fiches naît minimale et grandit par des
   actes de validation accumulés au fil de l'usage, jamais par décret initial ni par volume ;
3. **la confiance qui voyage** : chaque fiche porte l'état de son traitement, née conforme,
   extraite, curée, validée, et ce que lit l'assistant porte la confiance de ce qu'il lit.

Le nom dit la thèse. En logique, la *soundness* d'un système de preuve est la propriété que
tout ce qui s'y prouve est vrai. Ici : la fiche ne dit rien que la pièce ne fonde.

## Le problème

Le travail assisté par IA consomme des documents et en produit. Deux dérives symétriques
guettent. Si l'extraction est libre, sans structure, chaque passage de la machine produit une
lecture différente, et rien ne distingue ce qui a été vérifié de ce qui a été généré : la
confiance meurt par dilution. Si la structure est décrétée d'avance, un schéma complet posé
avant les pièces réelles, elle meurt par rigidité : les documents vrais débordent toujours le
schéma prévu, et le système finit contourné, la vraie information vivant dans des champs
commentaires que plus rien ne gouverne.

Le problème s'aggrave d'un fait simple : la pièce la plus facile à lire n'est pas la plus
fréquente. Un flux réel mélange le document né dans un gabarit officiel signé, la facture PDF,
le scan propre, et le bon de livraison griffonné signé à la main. Un système qui traite tout
pareil ment quelque part : soit il surestime le manuscrit, soit il fait payer au natif le prix
du manuscrit.

## Pourquoi la dualité

On pourrait vouloir fusionner : faire de la fiche extraite le document de travail unique. Le
gain apparent est réel, un seul objet ; le coût est fatal : le jour où la fiche est contestée,
il n'y a plus rien derrière elle. La dualité coûte un renvoi et rachète tout le reste : la
pièce demeure immuable et opposable, la fiche vit, se corrige, se sert ; le doute a un endroit
où aller, et l'avis qui en revient se trace. L'archivistique a établi ce partage il y a plus
d'un siècle, l'instrument de recherche contre la pièce originale ; l'archivage à valeur
probante l'a durci en norme. SOUNDNESS n'invente pas la dualité : il la rend native pour un
lecteur double, l'humain et la machine, et il en fait la condition de tout le reste.

C'est aussi ce qui répare la règle-mère. Une première version demandait au sommet du template
de distinguer chaque instance ; un banc l'a réfutée par trilemme, vide, fausse ou
notationnelle. La réparation vient de la dualité : l'identité est portée par le renvoi à la
pièce, le sommet n'a pas à la porter une seconde fois. Le sommet redevient ce qu'il doit être :
le plus petit schéma utile.

## Pourquoi le template vivant

Entre le schéma décrété et l'absence de schéma, la voie médiane est connue des traditions que
ce corpus cite : les archétypes cliniques se spécialisent sous gouvernance, les vocabulaires
publics promeuvent leurs termes par l'usage, les schémas hybrides promeuvent un attribut stable
en colonne. SOUNDNESS reprend le geste et le soumet à une discipline empruntée à LIVING
REFERENCE : **le volume propose, l'acte décide.** La machine compte, signale l'invariance,
suggère la branche ; un humain nommé promeut, ouvre, fusionne, par acte daté et motivé, pièces
d'appui citées. La croissance a deux axes qui ne se confondent pas, les valeurs pour la
promotion, les populations pour la ramification, et un critère d'arrêt, on ne descend que là où
une obligation ou un usage consulte.

Pourquoi pas l'apprentissage seul ? Parce qu'un schéma qui bouge sans acte est un schéma dont
personne ne répond. La promotion silencieuse est exactement le genre de confort qui coûte la
confiance : le jour du contrôle, « le système a appris » n'est pas une réponse ; « le
validateur a promu le 12, sur ces trois pièces, pour ce motif » en est une.

## Pourquoi la confiance voyage

Un score de confiance qui vit dans la base et meurt à la sortie ne protège personne : c'est au
moment où la fiche est servie à l'assistant, ou à l'humain, que la confiance doit être lisible.
D'où le statut porté par la fiche, servi avec elle, et l'automate fermé : quatre états, des
transitions écrites, rien d'implicite, rien qui monte par le temps ou le volume. Le spectre des
pièces entre par la même porte : le canal officiel, constaté par le système et jamais déclaré,
réserve la meilleure naissance au document qui la mérite structurellement ; l'ordre de prudence
de la table de départ fait suivre à toute pièce cumulant plusieurs natures la ligne la plus
prudente, jamais la plus flatteuse. Le premier banc de ce corpus a trouvé l'inversion de
confiance qui menaçait, un scan de formulaire officiel mieux né que sa nature ; la règle du
canal l'a fermée.

## Pourquoi la part humaine se règle

L'humain fait partie du processus, et cela ne veut pas dire un travail à parts égales. Quatre
gestes courts et souverains, déclarer, curer, valider, promouvoir, posés sur un tamis qui dit
ce qui est dû et rien d'autre. La machine propose toujours d'abord, même mal : l'humain ne part
jamais d'une page blanche. Le réglage de la quantité d'aide appartient à MYSTANCE, et son
invariant tient ici comme partout : le réglage change combien la machine propose, jamais qui
décide. La limite est déclarée plutôt que niée : aucun réglage ne protège d'une validation par
routine ; une trace cochée sans regard ment, et la vigilance ne se délègue pas.

## L'architecture, en un schéma

```text
dépôt ── déclaration (nature · difficulté) ── canal constaté par le système
  │
  ▼
table de départ, ordre de prudence (S5.2) ──► template plein · light · entrée directe
  │
  ▼
extraction : la machine propose ──► FICHE (statut : née conforme ou extraite)
  │                                    │ renvoi tracé
  ▼                                    ▼
curation due par le tamis (S6.2)     PIÈCE, immuable, opposable
  │
  ▼
acte de validation ──► VALIDÉE, servie avec son statut
  │
  └── paires proposé-corrigé ──► signalements ──► actes sur le template (S3)
```

Huit familles de règles portent ce schéma : l'élection du sommet et la naissance des familles
(S1), la ramification (S2), la promotion (S3), l'automate des statuts (S4), la déclaration de
dépôt (S5), la curation (S6), le sommet du spectre (S7), le profil d'application (S8).

## Les deux cas fondateurs

Les bancs de ce corpus instancient deux pièces extrêmes, et elles restent ses cas de référence.
**L'ordre de mission né conforme** : canal officiel, entrée directe, confirmation d'un geste ;
l'extraction est une lecture, la dualité survit quand même, le contenu converge, jamais le
régime. **Le bon de livraison signé main, scanné** : déclaré scanné et manuscrit, template
plein, curation des zones manuscrites, paires conservées, validation ; douze gestes humains
pour cent douze pièces, la proportion est le mécanisme.

## Ce qui réfuterait ce papier

Huit conditions publiées, R1 à R8, dont les bancs du 2026-08-17 ont déjà exercé quatre : R1 a
requalifié l'apport, l'assemblage plutôt que les briques ; R2 a réfuté puis réparé la
règle-mère ; R4 a réaligné une formule sur LIVING REFERENCE ; R5 a produit la liste qui a fait
la version 0.0.3. Les autres attendent le terrain : R7 tombera ou tiendra sur des fiches
validées réelles, R8 sur des pièces qui cumulent. Les résultats, négatifs compris, se publient.

## Travaux voisins

Ce corpus est né en citant ses dettes, LINEAGE les détaille : la description archivistique à
niveaux et l'instrument de recherche ; l'archivage à valeur probante et la copie fiable ; le
two-level modeling d'openEHR et les feature models pour le partage stable-variable ; le
template en constantes et variables de la lignée RoadRunner ; la promotion d'attribut du
pattern EAV hybride ; l'industrie de l'extraction documentaire pour la confiance par champ, la
revue ciblée et l'apprentissage des corrections. Aucune de ces sources ne combine la pyramide
de méthode, la dualité opposable et la part humaine réglée par doctrine en un seul cadre
lisible humain-IA : c'est cet assemblage, et lui seul, que SOUNDNESS revendique.

## La place dans la famille

LIVING REFERENCE gouverne le statut du savoir ; WORKING REFERENCE, la façon dont la référence
sert le travail ; MYSTANCE, la place de l'humain. SOUNDNESS s'ajoute en dessous : il gouverne
la naissance du savoir extrait de documents, et il rend aux trois aînés ce qu'il leur emprunte,
le cycle de statuts, la discipline de l'acte, l'invariant du décideur. Le sol, l'intégrité de
ce qui est écrit, appartient à DATUM, hors de ce corpus.

## Statut, et la mesure à venir

Rang hypothèse : un seul praticien, aucune fiche produite en conditions réelles. La première
mesure honnête sera faite chez l'auteur, déclarée comme telle ; la mesure qui compte viendra
d'un déploiement tiers, et ce corpus ne dira jamais l'avoir avant de l'avoir. Ce qui se
mesurera, pré-enregistré avant toute mesure : la part de fiches servies dont le statut était
juste, le nombre de gestes humains par cent pièces, et le temps entre un doute et la pièce qui
le tranche.
