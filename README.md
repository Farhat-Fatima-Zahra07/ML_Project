## HEART DISEASE MACHINE LEARNING PROJECT

## Description
Ce projet utilise le Machine Learning pour prédire les maladies cardiaques à partir de données médicales.

Il contient :
- Classification supervisée
- Régression supervisée
- Clustering non supervisé

---

## Dataset
Le fichier utilisé est : `heart.csv`

Variables principales :
- age
- sex
- trestbps
- chol
- thalach
- etc.

Variable cible :
- num : 0 = pas de maladie, 1 = maladie cardiaque

---

## Étapes du projet

### 1. Prétraitement
- Remplacement des valeurs manquantes (SimpleImputer)
- Encodage des variables (get_dummies)
- Normalisation (StandardScaler)

---

<<<<<<< HEAD
### 2. Classification
Modèles utilisés :
=======
###  Clustering (Non supervisé)
- K-Means
- Clustering hiérarchique
- DBSCAN
- Évaluation avec Silhouette Score

---

###  Modèles de classification

####  Arbres de décision et ensembles
>>>>>>> c6f0eacd1b4064c0e1a413b1afcf9a153e002dc6
- Decision Tree
- Random Forest
- KNN
- Logistic Regression
- AdaBoost

Évaluation :
- Accuracy
- Confusion Matrix
- ROC Curve
- AUC
- Cross Validation

---

### 3. Régression
Objectif : prédire le cholestérol (chol)

Modèles :
- Linear Regression
- Random Forest Regression

Évaluation :
- MSE
- R²

---

### 4. Clustering
Algorithmes utilisés :
- K-Means
- DBSCAN

Visualisation des clusters avec matplotlib.

---

## Résultats
Le modèle avec la meilleure accuracy est affiché automatiquement à la fin du code.

---

## Bibliothèques utilisées
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Installation

<<<<<<< HEAD
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
=======
### Installer les bibliothèques :
pip install pandas numpy matplotlib seaborn scikit-learn scipy

### Lancer le notebook :
jupyter notebook ml_project.ipynb

---

##  Concepts appris
- Pipeline de Machine Learning
- Classification et clustering
- Bias / variance
- Bagging / Boosting
- Validation croisée
- Courbe ROC
- Modèles linéaires

---
## Auteur
Projet académique – Machine Learning (Heart Disease Prediction)

Nom : Fatima Zahra Farhat

---

## Améliorations possibles
- Ajouter SVM
- Optimisation des hyperparamètres (GridSearchCV)
- Importance des variables
- Déploiement avec Streamlit ou Flask
>>>>>>> c6f0eacd1b4064c0e1a413b1afcf9a153e002dc6
