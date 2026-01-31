# Titanic Survival Prediction

## Objectif
Prédire la survie des passagers du Titanic

## Dataset
- Source : Kaggle Titanic Competition
- 891 lignes d'entraînement
- 12 features

## Features Engineering
- **FamilySize** : SibSp + Parch + 1
- **Title** : Extraction depuis Name (Mr, Mrs, Miss...)
- **IsAlone** : FamilySize == 1

## Modèles testés
1. Logistic Regression - Cv_score: 0.822
2. Random Forest - Cv_score:  0.793
3. SVM - Cv_score: 0.829 
(il s'agit des scores moyens)
## Meilleur modèle : 
SVM
score de validation : 0.821
## Comment utiliser
```bash
# Installer les dépendances
pip install -r requirements.txt

# Lancer l'exploration
jupyter notebook notebooks/01_exploration.ipynb




###  **`requirements.txt` - Dépendances Python**
```
matplotlib==3.10.8
pandas==3.0.0
scikit_learn==1.8.0
seaborn==0.13.2
jupyter==1.0.0

