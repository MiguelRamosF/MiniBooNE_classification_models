# MiniBooNE_classification_models

Résumé: 

L'objectif de ce projet est de construire un modèle de prédiction à l'aide de divers algorithmes d'apprentissage automatique et de documenter les étapes de bout en bout à l'aide d'un modèle. Le jeu de données concerne l'identification de particules MiniBooNE, on est donc dans une situation de classification binaire classique dans laquelle nous essayons de prédire l'un des deux résultats possibles.


INTRODUCTION: 

Cet ensemble de données est issu de l'expérience MiniBooNE et est utilisé pour distinguer les neutrinos électroniques (signal) des neutrinos de muons (arrière-plan). Le fichier de données est configuré comme suit. La première ligne indique le nombre d'événements de signal et elle est suivie du nombre d'événements de fond. Donc les enregistrements avec les événements signal viennent en premier, suivis des événements en arrière-plan. Chaque ligne, après la première ligne, contient les 50 variables ID de particule pour un événement.

ANALYSE: 

Les performances de base des algorithmes d’apprentissage automatique ont atteint une précision moyenne de 83,74%. 
Deux algorithmes (Random Forest et GBM) ont permis d'obtenir les mesures de précision les plus élevées après le cycle de modélisation.

Random Forest : 89,20 %
GBM: 87,41 %

Sur le jeu de test validation, le Random Forest a une précision de 93,35 %


CONCLUSION:

L'algorithme de Random Forest a obtenu les meilleurs résultats globaux en utilisant les jeux de données de formation et de test.
Pour cet ensemble de données, ce modèle doit être pris en compte pour une utilisation ultérieure en modélisation ou en production.

