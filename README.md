# Implémentez un modèle de scoring

Au cours de ce projet, mon rôle était de construire un outil de "scoring credit" afin d'aider une banque (Nom de la banque : "Prêt à dépenser") à mieux évaluer la solvabilité de ses clients.

Pour ce faire il était nécessaire d'implémenter un modèle de classification supervisé pour évaluer la probabilité de défaut de chaque client en fonctions de différentes variables (revenus, statut marital, nombre d'enfants à charge, etc.).

Ce projet s'est déroulé en deux parties.

Il a fallu dans un premier temps traiter la base de données (traitement des valeurs manquantes, valeurs abérrantes, feature engineering, etc.) afin d'avoir des données exploitables pour la modélisation. Tout ce travail a été réalisé dans le notebook qui s'intitule : Pretraitement.ipynb.

Le notebook Prediction.ipynb présente les différents modèles de classification qui ont été implémenté et leurs résultats. Il était important de s'assurer que les modèles avaiient été implémentés de la bonne manière pour résoudre les problèmes d'échantillons de données déséquilibrés par exemple.

Enfin, il fallait sélectionner les bonnes métriques adéquates pour pouvoir évaluer correctement la performance des modèles en fonction du type d'erreur que l'on souhaite minimiser (erreur de type 1 VS erreur de type 2). 

