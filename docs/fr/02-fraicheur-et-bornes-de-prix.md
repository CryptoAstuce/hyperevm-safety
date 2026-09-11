# Fraicheur et bornes de prix

Un prix est utilisable seulement si son age reste sous une borne definie par le protocole.
Le controle doit rejeter timestamp futur, valeur nulle et ecart excessif avec une reference independante.
Les circuits de pause separés permettent de bloquer emprunts ou liquidations sans geler tous les remboursements.
Une valeur stale ne doit pas etre recyclee silencieusement comme prix actuel.
Les bornes de deviation doivent tenir compte de la volatilite sans devenir une autorisation illimitee.
Le chemin de secours doit exposer sa source et son propre modele de confiance.
Chaque branche d erreur conserve les operations qui reduisent le risque, notamment remboursement et ajout de collateral.

Suite : [03 — Décimales et solvabilité](03-decimales-et-solvabilite.md).
