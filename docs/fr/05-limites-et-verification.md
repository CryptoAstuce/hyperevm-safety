# Limites et vérification

Les property tests explorent des séquences mais leur couverture dépend des actions et domaines générés.
Un invariant trop faible peut rester vert tout en autorisant une perte économique réelle.
Les planted twins prouvent que le harnais détecte certaines fautes, pas toutes les fautes possibles.
Les seuils d’oracle, facteurs de collatéral et limites de position restent des choix de gouvernance.
Ce parcours repose sur src, invariants, formal, incidents et l’exemple minimal-lending-market du dépôt.
Aucune installation, compilation, fuzzing ou exécution nouvelle n’a été effectuée.
Aucun résultat de test ni garantie d’audit n’est revendiqué ici.
Pour vérifier, exécuter les suites Echidna, Medusa et Foundry dans un environnement isolé et revoir les hypothèses.
