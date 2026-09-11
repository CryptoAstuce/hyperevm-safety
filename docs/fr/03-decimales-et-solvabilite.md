# Decimales et solvabilite

HyperCore et les tokens ERC-20 peuvent employer des precisions et unites differentes.
Toute conversion fixe direction d arrondi, facteur d echelle et borne de debordement.
La valeur du collateral doit arrondir de maniere conservatrice face a la dette.
Le health factor ne doit jamais gagner de precision fictive lors d une division entiere.
Les sommes de plusieurs actifs sont normalisees dans une unite commune avant comparaison.
Les limites u64 cote Core doivent etre controlees avant conversion en uint256 cote EVM.
Un test d invariant utile compare toujours l implementation a un modele entier simple et independant.

Suite : [04 — Liquidations et incident JELLY](04-liquidations-et-incident-jelly.md).
