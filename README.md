# Prédiction de Matchs de Football - Ligue 1 (2013-2025)

Ce projet a pour objectif de prédire l'issue des matchs de football de la Ligue 1 en utilisant plusieurs techniques d'apprentissage et d'en comparer les résultats.

## Description du Projet
À partir de données historiques couvrant la période de **2013 à 2024**, nous construisons un ensemble de données complet intégrant :
- Les dynamiques récentes des équipes (points et différence de buts sur les 5 derniers matchs).
- Les caractéristiques structurelles des clubs (valeur marchande, âge moyen, effectif international, etc.).
- Les historiques de confrontations directes (Head-to-Head).

Après une étape de réduction de dimensionnalité par Analyse en Composantes Principales (ACP), nous comparons plusieurs modèles de classification (Random Forest, SVM, KNN, Régression Logistique) afin d'identifier le plus performant pour prédire les résultats de la saison 2025.

## Comprend également
* **Exploration & Visualisation** : Analyse de la répartition historique des scores et de la valeur marchande cumulée par club.
* **Feature Engineering** : Calcul d'écarts statistiques dynamiques entre équipe à domicile et équipe à l'extérieur.
* **Évaluation comparative** : Comparaison rigoureuse des algorithmes avec optimisation des hyperparamètres (GridSearchCV, RandomizedSearchCV).
* **Prédiction Cumulative** : Suivi de la stabilité et de l'évolution de la précision sur l'ensemble de test.
