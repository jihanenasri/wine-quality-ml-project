# Wine Quality - Projet Machine Learning supervisé

## Description
Prédiction de la qualité du vin rouge à partir de ses caractéristiques physico-chimiques.  
Ce projet implémente des modèles supervisés pour deux tâches :  
- **Classification binaire** : le vin est-il bon (qualité ≥ 7) ?  
- **Régression** : prédire la note de qualité (de 0 à 10).

## Dataset
- Source : [UCI Machine Learning Repository - Wine Quality](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- 1599 échantillons, 11 caractéristiques (acidité, pH, alcool, etc.)

## Modèles implémentés
- **Modèles linéaires** : régression logistique, régression linéaire
- **Instance-based** : KNN (k=5)
- **Arbre de décision** (profondeur 4) avec extraction de règles interprétables (rule‑based)
- **Ensemble learning** : Random Forest, AdaBoost, Gradient Boosting
- **Évaluation** : accuracy, F1-score, matrices de confusion, RMSE, R², courbe ROC/AUC
- **Analyse biais/variance** : validation croisée, courbe d’apprentissage (learning curve)
- **Optimisation** : GridSearchCV pour Random Forest
- **Analyse** : importance des caractéristiques, détection d’erreurs, temps d’exécution

## Résultats principaux
- Meilleure classification : **Random Forest optimisé (accuracy ≈ 88 %)**
- Régression : **Random Forest (R² ≈ 0.45)** supérieur à la régression linéaire (R² ≈ 0.36)
- AUC > 0.90 pour la classification

## Exécution
1. Placez `winequality-red.csv` dans un sous-dossier `archive`.
2. Lancez le notebook Jupyter.
3. Exécutez les cellules séquentiellement.

## Auteur
jihane nasri