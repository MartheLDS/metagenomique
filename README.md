# Assignation taxonomique de séquences ARN de bactéries du milieu urinaire

**Objectif** : comparer les performances de différents modèles de classificationà partir de différents jeux d'entrainements.

## choix du jeux d'entrainements
- datasets généralistes déjà existants
- consitution de jeux custom spécifiques au milieu urinaire:
    - espèces d'intérêt extraites d'études
    - récupération des txids via NCBI
    - récupération de séquences représentatives pour chaque txid
    - variation du nombre minimum et maximum de représntants pour chaque espèce pour réduire le déséquilibre des classes

## constitution d'un jeu de test
- extraction d'une partie d'un jeu d'entrainement
- suppression des séquences du jeu de test des jeux d'entraînements

## test de plusieurs modèles
- approche naïve avec RapidFuzz
- knn / distance cosine
- NaiveBayes

## comparaison des résultats
- sur des pathogènes d'intérêt 
- sur des lactobacilles (rôle potentiellement protecteur)



