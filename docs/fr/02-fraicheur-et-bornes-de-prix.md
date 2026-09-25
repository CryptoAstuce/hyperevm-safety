# Fraîcheur et bornes de prix

Un prix est utilisable seulement si son âge reste sous une borne définie par le protocole.
Le contrôle doit rejeter timestamp futur, valeur nulle et écart excessif avec une référence indépendante.
Les circuits de pause séparés permettent de bloquer emprunts ou liquidations sans geler tous les remboursements.
Une valeur stale ne doit pas être recyclée silencieusement comme prix actuel.
Les bornes de déviation doivent tenir compte de la volatilité sans devenir une autorisation illimitée.
Le chemin de secours doit exposer sa source et son propre modèle de confiance.
Chaque branche d’erreur conserve les opérations qui réduisent le risque, notamment remboursement et ajout de collatéral.

Suite : [03 — Décimales et solvabilité](03-decimales-et-solvabilite.md).
