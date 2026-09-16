# 4. Attestations et fork choice

Les attestations portent un vote sur la tête de chaîne, le checkpoint source et le checkpoint cible. Nimbus vérifie le slot, la committee, la signature et la cohérence avec l’état.

Le fork choice pondère les votes pour sélectionner la branche préférée. La tête choisie peut évoluer avant la finalité.

Les agrégateurs réduisent le volume de signatures diffusées en regroupant des attestations compatibles. La signature agrégée doit rester vérifiable par le client.

Une attestation correcte ne transforme pas une branche en état finalisé à elle seule.

Suite : [Propositions et finalité](05-propositions-finalite.md).
