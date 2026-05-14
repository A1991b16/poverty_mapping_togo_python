# Poverty Mapping Togo 🇹🇬 — Python Version

## Description
Reproduction en Python du projet de cartographie 
de la pauvreté au Togo, initialement développé en R.
Combine données DHS 2017 et variables satellitaires
via un modèle XGBoost.

## Résultats
- **R² = 0.887** sur les données de test
- La densité de population est le principal prédicteur
- Cohérent avec la version R (R² = 0.856)

## Données
- DHS Togo 2017 — Wealth index + coordonnées GPS
- WorldClim — Précipitations et température
- SRTM — Altitude
- WorldPop — Densité de population 2020

## Méthode
1. Exploration des données (pandas, matplotlib)
2. Matrice de corrélation (seaborn)
3. Modèle XGBoost (scikit-learn)
4. Visualisation des résultats

## Technologies
- Python 3.13 (Anaconda)
- numpy, pandas, matplotlib, seaborn
- scikit-learn, xgboost
- Jupyter Notebook

## Lien avec la version R
Ce projet est la version Python de :
github.com/A1991b16/poverty_mapping_togo

## Auteur
Womenyao Komla Sedzro EKLOU
M2 Magistère Économie du Développement — CERDI
Université Clermont Auvergne, France 
