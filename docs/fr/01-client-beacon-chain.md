# 1. Client consensus et Beacon Chain

Nimbus implémente le client consensus Ethereum et suit la Beacon Chain. Il échange avec les pairs, maintient l’état consensus et expose les interfaces nécessaires aux validateurs.

Comme les autres clients post-Merge, il dialogue avec un client d’exécution pour traiter les payloads. La séparation permet de faire évoluer consensus et exécution indépendamment.

L’implémentation en Nim vise une empreinte adaptée à des environnements variés, mais les garanties dépendent de la configuration et du matériel.

Suite : [État, slots et epochs](02-etat-slots-epochs.md).
