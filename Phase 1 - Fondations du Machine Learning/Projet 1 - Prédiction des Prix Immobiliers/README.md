# Projet 1 - Prédiction des Prix Immobiliers 🏡

## Description
Ce projet fait partie de la **Phase 1 : Fondations du Machine Learning** dans mon parcours *Road to Master AI*. L'objectif de ce projet est de prédire les prix des maisons en Californie en utilisant un modèle de régression linéaire. Le modèle est entraîné sur des caractéristiques comme l'âge des maisons, le nombre de chambres, la population locale, et le revenu médian pour capturer les tendances du marché immobilier.

## Objectifs du Projet
1. **Explorer et Préparer les Données** : Comprendre les caractéristiques des données, gérer les valeurs manquantes, et normaliser les valeurs numériques.
2. **Entraîner un Modèle de Régression Linéaire** : Utiliser la régression linéaire pour prédire les prix des maisons.
3. **Évaluer la Performance du Modèle** : Analyser la précision du modèle à l'aide de métriques d'erreur telles que le MAE, MSE, et RMSE.

## Étapes du Projet
1. **Exploration des Données** :
   - Chargement du dataset California Housing.
   - Utilisation de `.info()`, `.describe()` et visualisations pour analyser les données.
   - Gestion des valeurs manquantes et prétraitement des données.

2. **Prétraitement des Données** :
   - Standardisation des caractéristiques numériques pour uniformiser les échelles.

3. **Modélisation** :
   - Division des données en ensembles d'entraînement et de test (80/20).
   - Entraînement d’un modèle de régression linéaire.
   - Prédiction des prix sur l'ensemble de test.

4. **Évaluation du Modèle** :
   - Calcul des métriques d’évaluation : **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, **Root Mean Squared Error (RMSE)**.
   - Interprétation des résultats pour identifier les limites du modèle.

## Résultats
- **Mean Absolute Error (MAE)** : 56 642
- **Mean Squared Error (MSE)** : 5 865 619 646
- **Root Mean Squared Error (RMSE)** : 76 587

Ces valeurs montrent que, bien que le modèle capture des tendances générales, il présente des erreurs significatives pour certaines prédictions. Cela souligne l’importance d’explorer des modèles plus complexes ou des ajustements supplémentaires pour améliorer les performances.

## Visualisations
- **Valeurs Réelles vs. Valeurs Prédites** : Un graphique de dispersion pour comparer les valeurs prédites aux valeurs réelles.
- **Distribution des Erreurs** : Histogramme des erreurs pour analyser la répartition des écarts entre les prédictions et les valeurs réelles.

## Améliorations Futures
1. **Essayer d'autres modèles** : Tester des modèles plus avancés comme les forêts aléatoires ou le gradient boosting pour voir s'ils capturent mieux les variations.
2. **Feature Engineering** : Ajouter des caractéristiques pertinentes, comme la densité de population, pour enrichir le modèle.
3. **Validation croisée** : Utiliser la validation croisée pour obtenir une évaluation plus robuste et réduire le risque de surapprentissage.

## Conclusion
Ce projet fournit une première approche pour la prédiction des prix immobiliers en utilisant la régression linéaire. Bien que les résultats montrent des tendances intéressantes, il existe des opportunités d'amélioration pour rendre les prédictions plus précises.

---

**Note** : Ce projet fait partie de mon parcours *Road to Master AI* pour développer des compétences solides en intelligence artificielle et machine learning.

