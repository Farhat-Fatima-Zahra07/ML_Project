#  Projet Machine Learning – Prédiction des Maladies Cardiaques

## Description du projet
Ce projet utilise le Machine Learning pour analyser des données médicales et prédire la présence de maladies cardiaques.

Il contient plusieurs approches :
- Apprentissage supervisé
- Apprentissage non supervisé
- Modèles linéaires
- Méthodes d’ensemble

---

##  Dataset
Le dataset `heart.csv` contient des informations médicales comme :
- Âge
- Sexe
- Tension artérielle
- Cholestérol
- Fréquence cardiaque maximale
- Autres variables cliniques
 Variable cible :
- num :
  - 0 → pas de maladie
  - 1 → maladie cardiaque

---

##  Étapes du projet

###  Prétraitement des données
- Gestion des valeurs manquantes (SimpleImputer)
- Encodage des variables catégorielles (LabelEncoder)
- Normalisation des données (StandardScaler)

---

###  Clustering (Non supervisé)
- K-Means
- Clustering hiérarchique
- DBSCAN
- Évaluation avec Silhouette Score

---

###  Modèles de classification

####  Arbres de décision et ensembles
- Decision Tree
- Random Forest (Bagging)
- AdaBoost (Boosting)

####  KNN
- k-Nearest Neighbors

####  Modèles linéaires
- Régression linéaire (pour compréhension)
- Régression logistique (classification binaire)
- Régression logistique multinomiale (multi-classes)

---

##  Évaluation des modèles
Les modèles sont évalués avec :
- Accuracy
- Matrice de confusion
- Rapport de classification
- Courbe ROC et AUC
- Validation croisée (Cross Validation)

---

##  Résultat final
Le meilleur modèle est sélectionné selon la précision et les résultats de validation.

---

##  Bibliothèques utilisées
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- scipy

---

##  Comment exécuter le projet

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
