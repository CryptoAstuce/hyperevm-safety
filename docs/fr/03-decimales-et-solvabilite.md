# Décimales et solvabilité

HyperCore et les tokens ERC-20 peuvent employer des précisions et unités différentes.
Toute conversion fixe direction d’arrondi, facteur d’échelle et borne de débordement.
La valeur du collatéral doit arrondir de manière conservatrice face à la dette.
Le health factor ne doit jamais gagner de précision fictive lors d’une division entière.
Les sommes de plusieurs actifs sont normalisées dans une unité commune avant comparaison.
Les limites u64 côté Core doivent être contrôlées avant conversion en uint256 côté EVM.
Un test d’invariant utile compare toujours l’implémentation à un modèle entier simple et indépendant.

Suite : [04 — Liquidations et incident JELLY](04-liquidations-et-incident-jelly.md).
