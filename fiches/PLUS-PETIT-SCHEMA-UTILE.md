# Le plus petit schéma utile

**Le sommet d'un template dit deux choses : ce qu'est la famille, et le premier champ qui sert.**

## Ce que c'est

Tout template d'une famille de pièces naît de sa forme minimale. Elle contient exactement deux
choses : la **constante d'appartenance**, le type de la famille avec le test qui permet de
reconnaître qu'une pièce en est ; et un **premier champ à forte valeur métier**. Rien d'autre.
Surtout pas d'identifiant d'instance : l'identité est portée par le renvoi à la pièce, la
dualité s'en charge, le sommet n'a pas à la porter une seconde fois.

```text
          ┌───────────────────────────────────┐
sommet    │ constante d'appartenance          │   le plus petit schéma utile ;
          │ + premier champ à valeur métier   │   l'identité ne monte pas ici,
          └────────────────┬──────────────────┘   elle passe par le renvoi à la pièce
                           │
            branches ouvertes par pièces réelles, jamais par anticipation
```

Une première version de cette règle demandait au champ du sommet de « distinguer chaque
instance » ; un banc l'a réfutée, à raison, et la version présente en est la réparation. La
fiche le dit parce que c'est ainsi qu'une règle gagne sa forme : en perdant ce qu'elle
prétendait de trop.

## Le geste

Le premier champ ne se choisit pas au goût : d'abord le champ qu'exige la première obligation
applicable, les obligations s'ordonnant légale, puis contractuelle, puis de gestion ; à défaut,
le champ que le métier demande en premier, établi sur l'usage tracé. L'élection est un acte de
validation, daté, motivé, révisable. Et une famille naît par acte, trois choses ou rien : le
test d'appartenance, le premier champ, le validateur nommé.

## Un exemple

Famille « ordre de mission ». Constante d'appartenance : une autorité identifiée missionne
nommément un agent, et le document l'atteste. Premier champ : l'agent missionné, parce que la
première obligation de gestion le demande. Le numéro d'ordre vit plus bas, champ ordinaire.

## Les règles qui s'appliquent

A2 ; S1 entière, la naissance des familles comprise (S1.5).

## Ce que cette fiche ne promet pas

Le plus petit schéma utile ne prédit pas les besoins futurs et ne cherche pas à le faire : la
croissance viendra des pièces réelles, jamais de l'anticipation. C'est l'objet de la fiche
[RAMIFICATION](RAMIFICATION.md).

## Rang de preuve

**Hypothèse.** Le mécanisme a passé deux bancs adverses le 2026-08-17 (antériorité, réfutation,
instanciation sur deux cas) ; il n'a connu aucun déploiement réel. Les effets attendus se disent
au conditionnel tant qu'ils ne sont pas mesurés.
