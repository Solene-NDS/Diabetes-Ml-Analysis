#  Diabetes ML Analysis

Analyse et modélisation d'un jeu de données médical pour prédire le diabète et les facteurs de risque associés.

##  Objectif

Analyser les facteurs influençant le risque et la présence du diabète à partir de caractéristiques démographiques, comportementales et cliniques, et construire des modèles prédictifs.

##  Dataset

- **1 000 patients** avec des données démographiques, cliniques et comportementales
- Variables : BMI, glycémie, HbA1c, cholestérol, tension artérielle, activité physique, etc.
- Cibles : `diabetes` (Yes/No) et `risk_category` (Low / Moderate / High)

##  Contenu du projet

| Étape | Description |
|-------|-------------|
|  Lecture des données | Chargement, aperçu, types de variables |
|  Nettoyage | Valeurs manquantes, outliers, statistiques descriptives |
|  ACP | Réduction dimensionnelle, visualisation en 2D |
|  Clustering | KMeans + CAH (Ward), méthode du coude, silhouette, Davies-Bouldin |
|  Régression | Linéaire simple (BMI → Glucose) et multiple (→ HbA1c) |
|  Classification | KNN binaire (diabète) et multiclasse (risk_category) |

##  Technologies

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.x-orange)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13-teal)

##  Lancer le projet

```bash
# Installer les dépendances
pip install pandas numpy scikit-learn matplotlib seaborn scipy jupyter

# Lancer le notebook
jupyter notebook Projet_ML_Diabete.ipynb
```

## 📁 Structure

```
Diabetes-Ml-Analysis/
├── Projet_ML_Diabete.ipynb   # Notebook principal
├── patients_synthetic_1000.csv  # Dataset
└── README.md
```

## 👩‍💻 Auteure
**Solène N'DAH-SEKOU** — Étudiante ingénieure en 1ère année de cycle ingénieur à l'EFREI Paris  
