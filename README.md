# 📊 Projet de Modélisation du Churn Client

Ce projet a pour objectif d'**analyser le comportement des clients** et de **prédire les risques d'attrition (churn)**. L'analyse se concentre particulièrement sur la compréhension des raisons pour lesquelles les clients quittent l'entreprise, notamment sur le marché allemand.

## Objectifs du Projet
- **Analyser le marché allemand** pour identifier les facteurs spécifiques de départ des clients.
- **Effectuer du Feature Engineering** (ex: création de variables comme le `BalanceSalaryRatio`).
- **Entraîner des modèles de Machine Learning** pour prédire précisément le churn.

## Technologies et Librairies Utilisées
- **Langage :** Python 3.14
- **Environnement :** VS Code / Jupyter Notebooks
- **Librairies clés :** 
  - `pandas` & `numpy` (Manipulation des données)
  - `seaborn` & `matplotlib` (Visualisation des données)
  - `scikit-learn` (Modélisation de Machine Learning)


## 📈 Étapes de l'Analyse (Workflow)

### 1. Exploration et Nettoyage des Données (EDA)
- Analyse des distributions, des valeurs manquantes et des corrélations.
- Focus sur la segmentation géographique (Focus : Marché Allemand).

### 2. Feature Engineering (Ingénierie des variables)
- Création de nouvelles variables métier pour améliorer la puissance prédictive des modèles.
- *Exemple :* Calcul du ratio solde/salaire (`BalanceSalaryRatio = Balance / (EstimatedSalary + 1)`).

### 3. Modélisation et Évaluation (À compléter selon vos algorithmes)
- Entraînement de plusieurs modèles de classification (ex: Régression Logistique, Random Forest, XGBoost).
- Évaluation des performances via la matrice de confusion, le score F1 et la courbe ROC-AUC.

## 💻 Tous les détails et les resultats sont dans le notebook

  
