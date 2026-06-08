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

### 2. Classification
Modèles utilisés :
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

```bash
pip install pandas numpy matplotlib seaborn scikit-learn