# Frontière HyperCore–HyperEVM

Les protocoles HyperEVM peuvent lire des données HyperCore via des précompiles spécialisées.
Ces lectures portent sur un instant déterminé et ne reflètent pas les actions CoreWriter du même bloc.
Un marché de prêt doit distinguer prix, position, timestamp logique et bloc d’observation.
La disponibilité d’une valeur ne prouve ni sa fraîcheur ni son adéquation comme oracle de liquidation.
Les conversions entre indices Core et adresses de tokens EVM doivent rester bijectives et vérifiées.
Une erreur à cette frontière peut rendre solvable un compte insolvable ou provoquer une liquidation indue.
Les invariants doivent donc envelopper toute lecture avant qu’elle influence dette ou collatéral.

Suite : [02 — Fraîcheur et bornes de prix](02-fraicheur-et-bornes-de-prix.md).
