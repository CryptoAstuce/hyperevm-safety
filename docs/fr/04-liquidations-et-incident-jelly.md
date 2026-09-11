# Liquidations et incident JELLY

Un marche doit rester solvable meme lorsque prix, liquidite et taille de position evoluent brutalement.
La reproduction JELLY du depot separe une version propre d une variante volontairement vulnerable.
Cette methode de jumeaux rend la propriete attendue visible sans confondre correctif et demonstration.
Les invariants suivent dette, collateral, bonus de liquidation et valeur realisable.
Une liquidation partielle ne doit pas augmenter le deficit ni bloquer les etapes suivantes.
Les plafonds d emprunt et de collateral limitent l exposition a un actif peu liquide.
Les incidents historiques servent de cas adverses, pas de preuve que toutes les variantes sont couvertes.

Suite : [05 — Limites et vérification](05-limites-et-verification.md).
