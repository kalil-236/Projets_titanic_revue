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
1. Logistic Regression - Accuracy: 
2. Random Forest - Accuracy: 
3. SVM - Accuracy: 

## Meilleur modèle : 


## Résultats :
- Accuracy: 
- Precision: 
- Recall: 

## Comment utiliser
```bash
# Installer les dépendances
pip install -r requirements.txt

# Lancer l'exploration
jupyter notebook notebooks/01_exploration.ipynb




###  **`requirements.txt` - Dépendances Python**
```
pandas==1.5.3
numpy==1.24.3
scikit-learn==1.2.2
matplotlib==3.7.1
seaborn==0.12.2
jupyter==1.0.0