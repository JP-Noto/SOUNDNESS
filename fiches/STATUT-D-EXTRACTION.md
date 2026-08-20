# Le statut d'extraction

**Quatre états, des transitions fermées, et la confiance qui voyage avec la fiche.**

## Ce que c'est

Chaque fiche porte un statut, un seul : **née conforme** (entrée par le canal officiel, le
circuit natif du template officiel, constaté par le système, jamais déclaré : un scan n'y
accède pas), **extraite** (produite par la machine, non relue), **curée** (reprise par un
humain), **validée** (engagée en référence par un acte). Ce que lit l'assistant porte la
confiance de ce qu'il lit ; un profil peut fixer un statut plancher par usage.

```text
dépôt par le canal officiel ──────────────► NÉE CONFORME
tout autre dépôt, après extraction ───────► EXTRAITE

NÉE CONFORME ─── correction ──────────────► CURÉE
EXTRAITE ─────── geste de curation ───────► CURÉE
NÉE CONFORME · EXTRAITE · CURÉE ─── acte de validation ───► VALIDÉE
VALIDÉE ──────── toute correction ────────► CURÉE, puis revalidation
```

Les statuts de flux existent dans toute l'industrie de l'extraction documentaire, et la fiche
le reconnaît ([LINEAGE](../LINEAGE.md)). La différence tient à deux choses : ici, le statut est
un cycle doctrinal aligné sur celui du savoir de LIVING REFERENCE, et rien ne monte jamais par
écoulement du temps ni par volume.

## Le geste

Les transitions sont fermées : ce qui n'est pas écrit n'existe pas. Valider n'est jamais
implicite, même pour une fiche née conforme : la signature officielle est un attribut de la
pièce, la validation est un acte sur la fiche : valider, c'est engager l'usage en référence,
pas constater une lecture. Toute correction fait redescendre en curée, revalidation exigée ; et
faire redescendre une fiche validée est réservé aux identités habilitées.

## Un exemple

Un ordre de mission arrive par le circuit officiel : née conforme. Le responsable confirme d'un
geste : validée. Un mois plus tard, une erreur de lecture est corrigée : curée, puis revalidée.
Le journal des transitions garde chaque pas, sans réécriture.

## Les règles qui s'appliquent

A4 ; S4 entière ; S5.2 pour l'entrée ; S8 pour le plancher.

## Ce que cette fiche ne promet pas

Le statut mesure la confiance du traitement, pas la vérité du contenu : une fiche validée peut
être fausse si l'humain a validé par routine. Cette limite appartient à la part humaine, et la
fiche [PART-HUMAINE-REGLEE](PART-HUMAINE-REGLEE.md) la porte.

## Rang de preuve

**Hypothèse.** Le mécanisme a passé deux bancs adverses le 2026-08-17 (antériorité, réfutation,
instanciation sur deux cas) ; il n'a connu aucun déploiement réel. Les effets attendus se disent
au conditionnel tant qu'ils ne sont pas mesurés.
