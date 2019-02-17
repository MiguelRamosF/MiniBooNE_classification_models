# MiniBooNE_classification_models

Résumé: 

L'objectif de ce projet est de construire un modèle de prédiction à l'aide de divers algorithmes d'apprentissage automatique et de documenter les étapes de bout en bout à l'aide d'un modèle. Le jeu de données concerne l'identification de particules MiniBooNE, on est donc dans une situation de classification binaire classique dans laquelle nous essayons de prédire l'un des deux résultats possibles.


INTRODUCTION: 

Cet ensemble de données est issu de l'expérience MiniBooNE et est utilisé pour distinguer les neutrinos électroniques (signal) des neutrinos de muons (arrière-plan). Le fichier de données est configuré comme suit. La première ligne indique le nombre d'événements de signal et elle est suivie du nombre d'événements de fond. Donc les enregistrements avec les événements signal viennent en premier, suivis des événements en arrière-plan. Chaque ligne, après la première ligne, contient les 50 variables ID de particule pour un événement.



ANALYSE: 

Les performances de base des algorithmes d’apprentissage automatique ont atteint une précision moyenne de 90,58%. Deux algorithmes (Bagged CART et Stochastic Gradient Boosting) ont permis d'obtenir les mesures de précision les plus élevées après le premier cycle de modélisation. Après une série d'essais de réglage, le rehaussement de gradient stochastique a obtenu le meilleur résultat global et une métrique de précision de 93,95%. En utilisant les paramètres optimisés, l’algorithme Stochastic Gradient Boosting a traité l’ensemble de données de test avec une précision de 93,85%, soit un niveau légèrement inférieur à celui des données d’apprentissage.

CONCLUSION: 

L'algorithme Stochastic Gradient Boosting a obtenu les meilleurs résultats globaux en utilisant les jeux de données de formation et de test. Pour cet ensemble de données, l'algorithme de renforcement du gradient stochastique doit être pris en compte pour une utilisation ultérieure en modélisation ou en production.
