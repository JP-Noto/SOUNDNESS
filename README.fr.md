# SOUNDNESS

**La fiche ne dit rien que la pièce ne fonde.**

`Statut : Public Draft` · `Corpus : 0.1` · `Rang : hypothèse` · `Licence : CC BY-NC-SA 4.0` · [English](README.md)

> SOUNDNESS, du terme de logique : la propriété d'un système de preuve dont tout ce qui se
> prouve est vrai. Ici, appliqué au savoir extrait de documents.

## Le point de départ

Quand une machine extrait du savoir de documents, deux dérives symétriques guettent. Sans
structure, chaque passage produit une lecture différente et rien ne distingue le vérifié du
généré : la confiance meurt par dilution. Avec un schéma décrété d'avance, les pièces réelles
débordent toujours le prévu et le système finit contourné : la confiance meurt par rigidité. Et
le flux réel n'est pas homogène : il mélange le document né dans un gabarit officiel signé, la
facture PDF, le scan propre et le bon de livraison griffonné. Un système qui traite tout pareil
ment quelque part.

## Le principe : trois engagements

La confiance ne vit pas dans la copie ; elle vit dans le chemin qui relie la copie à ce qui
fait foi. D'où trois engagements, dont aucun ne suffit sans les deux autres :

1. **la dualité** : la fiche extraite n'est jamais l'original ; elle renvoie à sa pièce, seule
   opposable, et tout avis fondé sur une consultation se trace ;
2. **le template vivant** : la structure naît minimale, le plus petit schéma utile, et grandit
   par actes de validation accumulés au fil de l'usage ; le volume propose, l'acte décide ;
3. **la confiance qui voyage** : chaque fiche porte son statut, née conforme, extraite, curée,
   validée, et ce que lit l'assistant porte la confiance de ce qu'il lit.

## Les mécanismes

Six fiches, une par mécanisme ([index](fiches/index.md)) :

- [`DUALITE-FICHE-PIECE`](fiches/DUALITE-FICHE-PIECE.md) : la fiche sert, la pièce fait foi, le
  chemin se trace ;
- [`PLUS-PETIT-SCHEMA-UTILE`](fiches/PLUS-PETIT-SCHEMA-UTILE.md) : le sommet du template, et la
  naissance des familles par acte ;
- [`RAMIFICATION`](fiches/RAMIFICATION.md) : croître par pièces réelles, l'axe des valeurs
  distinct de l'axe des populations ;
- [`STATUT-D-EXTRACTION`](fiches/STATUT-D-EXTRACTION.md) : quatre états, transitions fermées,
  rien ne monte par le temps ni le volume ;
- [`DECLARATION-DE-DEPOT`](fiches/DECLARATION-DE-DEPOT.md) : trois axes à l'entrée, et la table
  en ordre de prudence, jamais la ligne la plus flatteuse ;
- [`PART-HUMAINE-REGLEE`](fiches/PART-HUMAINE-REGLEE.md) : quatre gestes courts et souverains,
  la participation décisive, pas volumineuse.

## Deux chemins de lecture

**Chemin de l'utilisateur**, l'ordre du geste : la dualité d'abord, puis le dépôt, le statut, la
curation ; la part humaine en dernier, elle éclaire tout le reste.
**Chemin normatif** : [`SPEC.md`](SPEC.md) d'abord, trente-quatre règles S1.1 à S8.3, puis le
[`WHITEPAPER`](WHITEPAPER.md) pour le pourquoi de chacune.

| Fichier | Rôle |
|---|---|
| [`SPEC.md`](SPEC.md) | le normatif : termes, affirmations, huit familles de règles, falsification R1-R8 ; il prime |
| [`WHITEPAPER.md`](WHITEPAPER.md) | le pourquoi : la thèse, les refus argumentés, l'architecture en un schéma, la mesure à venir |
| [`LINEAGE.md`](LINEAGE.md) | les dettes, déclarées avant l'écriture : huit mécanismes, leurs traditions, ce qui diffère |
| [`fiches/`](fiches/index.md) | les six mécanismes, registre du professeur : le geste, l'exemple, le schéma, le rang |
| [`research/`](research/banc-2026-08-17.md) | les bancs : protocole publié avant résultats, verdicts négatifs compris |
| [`CHANGELOG.md`](CHANGELOG.md) | les versions |

## Né de la pratique

Ce corpus vient d'un retour de praticien : des années de discipline personnelle de classement,
une arborescence calquée sur la logique métier, et l'enseignement d'un projet antérieur, LOCUS,
la fiche-lieu adossée au réel. La règle qui a tout déclenché tient en une phrase du praticien :
tout doit rester consultable et intelligible pour un humain comme pour une IA. Le reste, la
pyramide, le statut, l'ordre de prudence, est venu en éprouvant cette phrase contre des cas
réels, l'ordre de mission né conforme et le bon de livraison griffonné, qui restent les deux
cas fondateurs du corpus.

## Ce qui est prouvé, ce qui ne l'est pas

Le corpus est né en citant ses dettes ([LINEAGE](LINEAGE.md)) et il a passé deux bancs adverses
le jour de sa naissance : antériorité sur cinq domaines, réfutation, double instanciation. Deux
affirmations en sont sorties réparées, et les verdicts, négatifs compris, sont publiés dans
[`research/`](research/banc-2026-08-17.md). **Rien d'autre n'est prouvé.** Aucune fiche n'a été
produite en conditions réelles ; les effets attendus se disent au conditionnel ; trois mesures
sont pré-déclarées pour le terrain à venir, et ce corpus ne dira jamais les avoir avant de les
avoir.

## La place dans la famille

| Couche | Gouverne |
|---|---|
| un AI OS hôte | le système : lois, fichiers, frontières |
| [LIVING REFERENCE](https://github.com/JP-Noto/LIVING-REFERENCE) | le statut du savoir : ce qui est validé, ce qui fait canon |
| [WORKING REFERENCE](https://github.com/JP-Noto/WORKING-REFERENCE) | la façon dont la référence sert le travail |
| [MYSTANCE](https://github.com/JP-Noto/MYSTANCE) | la place de l'humain : la relation réglée |
| **SOUNDNESS** | la naissance du savoir extrait de documents : la fiche fondée sur la pièce |

Le sol, l'intégrité de ce qui est écrit, appartient à DATUM, hors de ce corpus. La famille est
opérée par le laboratoire [ONDE AI R&D](https://github.com/JP-Noto/ONDE).

## Statut

Public Draft, rang hypothèse. Le corpus est publié depuis le 2026-08-20 et la licence
a pris effet ([LICENSE](LICENSE.md)). Il est publié pour être lu, repris et pris en défaut ; il
n'a pas encore servi en conditions réelles, et il le dira le jour où ce sera le cas. Les
contributions sont réglées d'avance : [CONTRIBUTING.md](CONTRIBUTING.md).
