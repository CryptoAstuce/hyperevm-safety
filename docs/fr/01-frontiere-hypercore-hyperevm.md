# Frontiere HyperCore–HyperEVM

Les protocoles HyperEVM peuvent lire des donnees HyperCore via des precompiles specialisees.
Ces lectures portent sur un instant determine et ne reflètent pas les actions CoreWriter du meme bloc.
Un marche de pret doit distinguer prix, position, timestamp logique et bloc d observation.
La disponibilite d une valeur ne prouve ni sa fraicheur ni son adequation comme oracle de liquidation.
Les conversions entre indices Core et adresses de tokens EVM doivent rester bijectives et verifiees.
Une erreur a cette frontiere peut rendre solvable un compte insolvable ou provoquer une liquidation indue.
Les invariants doivent donc envelopper toute lecture avant qu elle influence dette ou collateral.

Suite : [02 — Fraîcheur et bornes de prix](02-fraicheur-et-bornes-de-prix.md).
