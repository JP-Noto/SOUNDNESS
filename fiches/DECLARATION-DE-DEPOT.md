# La déclaration de dépôt

**Qualifier la pièce à l'entrée, en un geste, et laisser l'ordre de prudence router.**

## Ce que c'est

À l'entrée, trois axes. La **nature**, déclarée, cumulable : native structurée, native libre,
scannée, manuscrite ; un bon de livraison scanné à signature manuscrite est scanné et
manuscrit, et le dire n'a rien d'un dilemme. La **difficulté**, déclarée, binaire : ordinaire ou
difficile ; c'est l'outil de l'utilisateur qui sait que sa pièce donnera du fil à retordre. Le
**canal**, constaté par le système, jamais déclaré : officiel ou libre.

La table de départ s'évalue dans un ordre de prudence, et la première ligne qui s'applique
l'emporte :

```text
1. difficile ?              ──► template light,  EXTRAITE
2. scannée ou manuscrite ?  ──► template plein,  EXTRAITE, tamis dû
3. canal officiel ?         ──► entrée directe,  NÉE CONFORME
4. native structurée ?      ──► template plein,  EXTRAITE
5. native libre ?           ──► template plein,  EXTRAITE
   (en cas de cumul, la ligne la plus prudente l'emporte)
```

En cas de cumul, la pièce suit la ligne la plus prudente, jamais la plus flatteuse : c'est la
réponse du corpus à un défaut que son propre banc a trouvé, une table sans précédence où un
scan de formulaire officiel aurait obtenu le meilleur statut de naissance.

## Le geste

Déclarer est une ligne, pas un formulaire ; ne rien déclarer vaut ordinaire, et le système
propose la nature qu'il détecte, confirmée d'un geste. Une déclaration erronée se détecte à
l'extraction : la pièce est redéclassée difficile, l'écart tracé, jamais corrigé en silence, et
la fiche se resserre au template light, le sommet plus les champs que les obligations rendent
obligatoires.

## Un exemple

L'utilisateur dépose un brouillon de chantier photographié et prévient : difficile. Le système
ouvre le template light de la famille, propose ce qu'il parvient à lire, et l'utilisateur
complète. Sans la déclaration, l'extraction aurait échoué sur le template plein, et le
redéclassement aurait fait le même chemin, avec une étape de plus.

## Les règles qui s'appliquent

S5 entière ; S6.2 pour ce que la nature rend dû ; S4.2 pour le statut d'entrée.

## Ce que cette fiche ne promet pas

La déclaration n'est pas une barrière ni un contrôle de l'utilisateur : c'est une aide au
routage. Sa vérité se vérifie sur pièce, à l'extraction, jamais sur parole.

## Rang de preuve

**Hypothèse.** Le mécanisme a passé deux bancs adverses le 2026-08-17 (antériorité, réfutation,
instanciation sur deux cas) ; il n'a connu aucun déploiement réel. Les effets attendus se disent
au conditionnel tant qu'ils ne sont pas mesurés.
