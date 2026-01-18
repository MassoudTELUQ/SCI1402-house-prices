# SCI1402 – House Prices (Regression)

## Objectif
Ce projet a été réalisé dans le cadre du cours SCI 1402 (Projet en science des données).
L’objectif est d’analyser des données immobilières et de prédire le prix de vente des maisons
à partir de caractéristiques numériques.

## Données
Les données utilisées proviennent de la plateforme Kaggle :
**House Prices – Advanced Regression Techniques**.

La variable cible du projet est :
- `SalePrice`

## Approche
Les principales étapes du projet sont :
- Chargement et inspection des données
- Analyse des valeurs manquantes
- Sélection d’un sous-ensemble de variables numériques
- Analyse exploratoire des données (visualisations)
- Modélisation à l’aide d’une régression linéaire
- Évaluation du modèle (RMSE et R²)

## Résultats (modèle de base)
- RMSE ≈ 38 014
- R² ≈ 0,81

## Structure du dépôt
- `notebooks/` : notebooks Jupyter du projet
- `images/` : figures et visualisations
- `README.md` : description du projet

## Exécution
Le projet peut être consulté en ouvrant le notebook Jupyter disponible dans le dossier
`notebooks/`. Les bibliothèques principales utilisées sont :
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
