                              Sujet : Modèles Linéaires - Adaline et Régression Logistique

1 - Description: 
Ce projet vise à implémenter un algorithme de descente de gradient pour optimiser les paramètres d'un modèle Adaline et de régression logistique.
Nous utilisons la descente de gradient stochastique (SGD) pour ajuster les poids du modèle et analyser l'impact de la normalisation des données sur les performances du modèle.

2 - Structure du projet :

Implémentation de l'algorithme de descente de gradient stochastique: 
      -Initialisation des poids.
      -Sélection aléatoire d’un échantillon d'entraînement.
      -Calcul de la sortie du modèle.
      -Évaluation de la fonction de coût.
      -Mise à jour des poids avec le gradient.
      -Répétition jusqu'à convergence.
      -Normalisation des données.

Stratégie max : Normalisation par la valeur maximale de chaque caractéristique
Stratégie norme : Normalisation par la norme du vecteur


3 - Jeux de données: 
Les performances des modèles ont été évaluées sur des bases de données réelles issues de UCI Machine Learning Repository :
  - Breast Cancer Wisconsin
  - Spambase
  - Ionosphere

4 - Exécution du projet:
Charger les données et effectuer la normalisation.
Entraîner les modèles Adaline et Régression Logistique.
Tester sur les bases de données réelles.
Comparer les performances.

5- Résultats et Analyse: 
L'effet de la normalisation max et norme sur la convergence et la performance des modèles a été étudié.
Les résultats montrent que la normalisation améliore la stabilité de l'apprentissage et la précision des modèles.
