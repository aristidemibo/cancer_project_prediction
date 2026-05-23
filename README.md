# cancer_project_prediction
project d'apprentisage comme data scientiste junior
# Breast Cancer EDA Project 🧪

## 🎯 Objectif
Ce projet fait partie de mon apprentissage en Data Science (formation IBM).  
L’objectif est de réaliser une **analyse exploratoire des données (EDA)** sur le dataset du cancer du sein afin de :
- Comprendre la structure des données
- Identifier les variables discriminantes entre tumeurs bénignes et malignes
- Préparer le terrain pour un futur modèle de machine learning

---

## 📂 Organisation du projet

---

## 🛠️ Librairies utilisées
- **[pandas](ca://s?q=pandas_exemple)** → manipulation des données  
- **[seaborn](ca://s?q=seaborn_exemple)** → visualisations statistiques  
- **[matplotlib](ca://s?q=matplotlib_exemple)** → graphiques personnalisés  
- **[scikit-learn](ca://s?q=scikit_learn_exemple)** → préparation pour machine learning  

---

## 📊 Étapes d’EDA
1. **[Inspection initiale](ca://s?q=pandas_df_info)** → `data.info()`, `data.describe()`  
2. **[Distribution des classes](ca://s?q=pandas_value_counts)** → `data['diagnosis'].value_counts()`  
3. **[Nettoyage](ca://s?q=pandas_isnull_sum)** → suppression de la colonne `id`, gestion des valeurs manquantes  
4. **[Corrélations](ca://s?q=seaborn_heatmap_correlation)** → matrice de corrélation + heatmap  
5. **[Visualisations](ca://s?q=seaborn_pairplot_cancer)** → pairplots, boxplots, histogrammes  
6. **[Interprétation](ca://s?q=Interpretation_EDA_cancer)** → identification des variables clés (`radius_mean`, `perimeter_mean`, etc.)

---

## 📈 Résultats principaux
- Les tumeurs malignes ont généralement des valeurs plus élevées pour `radius_mean` et `perimeter_mean`.  
- La variable `texture_mean` apporte une information supplémentaire mais moins discriminante seule.  
- Les visualisations (pairplot, boxplot, heatmap) confirment que certaines caractéristiques physiques sont fortement liées au diagnostic.

---

## 🚀 Prochaines étapes
- Sélection des variables les plus pertinentes (**feature selection**)  
- Entraînement d’un modèle de classification (ex. régression logistique, random forest)  
- Évaluation des performances avec métriques (accuracy, recall, precision, F1-score)

---

## 👨‍🎓 Contexte
Projet réalisé dans le cadre de ma formation **IBM Data Science**.  
Il s’agit d’un projet d’apprentissage pratique pour renforcer mes compétences en :
- Analyse exploratoire
- Visualisation de données
- Préparation de dataset pour le machine learning
