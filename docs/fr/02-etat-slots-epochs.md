# 2. État, slots et epochs

La Beacon Chain organise le temps en slots et epochs. L’état contient validateurs, balances, committees, checkpoints et informations nécessaires aux transitions.

Chaque slot peut accueillir une proposition et des attestations. Les epochs regroupent les règles de justification, finalité et récompenses.

Le client doit distinguer l’état finalisé de la tête courante et du contenu encore optimiste. Cette distinction protège les décisions prises par les opérateurs et les applications.

Les mises à jour d’état doivent respecter la version du fork Ethereum actif.

Suite : [Réseau et synchronisation](03-reseau-synchronisation.md).
