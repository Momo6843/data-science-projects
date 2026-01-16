# Détection de fraude par Machine Learning

## Objectif
Développer un système de détection de fraude basé sur l’apprentissage
automatique, à partir d’un jeu de données réel fortement déséquilibré.

## Problématique
La fraude représente une classe très minoritaire, ce qui rend les modèles
classiques inefficaces sans traitement spécifique du déséquilibre des classes.

## Méthodologie
- Optimisation du chargement et de l’utilisation mémoire
- Analyse exploratoire des données
- Sélection des variables pertinentes
- Encodage des variables catégorielles
- Réduction de dimension par Analyse en Composantes Principales (ACP)
- Entraînement et comparaison de plusieurs modèles :
  - Random Forest
  - XGBoost
  - SVM
  - KNN
- Recherche d’hyperparamètres (GridSearchCV)
- Gestion du déséquilibre des classes :
  - Random Under Sampling
  - Tomek Links
  - Random Over Sampling
  - SMOTE
  - SMOTE-Tomek

## Résultats
Les performances des modèles sont comparées avant et après rééquilibrage
des classes, mettant en évidence l’impact majeur des techniques de sampling
sur la capacité de détection de la fraude.

## Compétences mobilisées
- Détection de fraude
- Classification supervisée
- Gestion de données déséquilibrées
- Machine learning avancé
- Évaluation et comparaison de modèles
