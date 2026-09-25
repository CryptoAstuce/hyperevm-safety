# Liquidations et incident JELLY

Un marché doit rester solvable même lorsque prix, liquidité et taille de position évoluent brutalement.
La reproduction JELLY du dépôt sépare une version propre d’une variante volontairement vulnérable.
Cette méthode de jumeaux rend la propriété attendue visible sans confondre correctif et démonstration.
Les invariants suivent dette, collatéral, bonus de liquidation et valeur réalisable.
Une liquidation partielle ne doit pas augmenter le déficit ni bloquer les étapes suivantes.
Les plafonds d’emprunt et de collatéral limitent l’exposition à un actif peu liquide.
Les incidents historiques servent de cas adverses, pas de preuve que toutes les variantes sont couvertes.

Suite : [05 — Limites et vérification](05-limites-et-verification.md).
