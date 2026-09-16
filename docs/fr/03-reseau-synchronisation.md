# 3. Réseau et synchronisation

Nimbus découvre des pairs, négocie les capacités et récupère les blocs et états nécessaires. La synchronisation valide les données reçues avant de les intégrer à la chaîne locale.

Les erreurs de réseau, le retard, les pairs malveillants et les réorganisations ont des signaux différents. Les confondre peut conduire à suivre un état incorrect ou à interrompre inutilement le nœud.

Le checkpoint sync réduit le volume initial à récupérer, mais ajoute une hypothèse de confiance sur le checkpoint choisi.

Le réseau est une source de données, pas une source automatique de vérité.

Suite : [Attestations et fork choice](04-attestations-fork-choice.md).
