# CardioMind
# **Projet d'Analyse des Maladies Cardiaques : CardioMind**

##  **Professeur :**
- **Dr ZOUGAGH NISRINE** 🌟

### 🎓 **Matière** : Visualisation des Donnes 

### Date : *10/03/2025* ✍️
👨‍💻 Étudiant : Aldiouma Mbaye

## 📌 **Description du Projet**
Ce projet vise à analyser un jeu de données médical afin de prédire la présence ou l'absence de maladies cardiaques. L'étude repose sur des techniques de classification et de clustering appliquées aux données de patients.

## 🗂 **Jeu de Données**
- **Nom :** Heart Attack UCI
- **Description :** Ce jeu de données comprend divers attributs médicaux tels que l'âge, la pression artérielle, le taux de sucre dans le sang et des biomarqueurs spécifiques comme la troponine et la CK-MB.
- **Objectif :** Prédire si un patient est atteint d'une maladie cardiaque à partir de ses paramètres médicaux.

## 🔍 **Tâches de Classification**
### 1️⃣ **Préparation des Données**
- Traitement des valeurs manquantes et normalisation des données.
- Encodage des variables catégorielles.

### 2️⃣ **Modèles de Classification**
- **Forêt Aléatoire 🌲**
  - Implémentation d’un classifieur Random Forest.
  - Visualisation de l'importance des caractéristiques.
  - Ajustement des hyperparamètres et évaluation du modèle.
  
- **AdaBoost 🚀**
  - Utilisation d'un modèle AdaBoost.
  - Analyse des classificateurs faibles.
  - Évaluation des performances.
  
- **SVM (Support Vector Machine) 📈**
  - Implémentation d’un modèle SVM.
  - Visualisation de la séparation des classes.
  - Optimisation des hyperparamètres.
  
## 🧩 **Tâches de Clustering**
### 1️⃣ **Exploration des Données**
- Visualisation des données dans un espace 2D en utilisant des variables pertinentes.

### 2️⃣ **Modèles de Clustering**
- **k-Means** 🔵
  - Application de k-Means avec un nombre défini de clusters.
  - Évaluation des performances avec le silhouette score.
  - Explication des limites de k-Means avec un exemple.

## 📊 **Analyse Comparative**
### 🔬 **Analyse des Classifieurs**
- Comparaison des performances des différents modèles.
- Identification des forces et faiblesses de chaque algorithme.
- Recommandations sur le meilleur modèle.

### 🔍 **Analyse du Clustering**
- Comparaison des techniques de clustering.
- Discussion sur la pertinence du partitionnement des données.
- Évaluation des limites et perspectives d’amélioration.

## 📁 **Structure du Projet**
```
📂 CardioMind/
├── 📁 data/ → Contiendra les jeux de données bruts et prétraités.
├── 📁 notebooks/ → Pour les analyses exploratoires et expérimentations.
├── 📁 reports/ → Stockage des visualisations, résultats et rapports finaux.
├── 📁 src/ → Contiendra le code source du projet (prétraitement, modèles ML, etc.).
├── 📄 requirements.txt → Liste des dépendances du projet.
├── 📄 LICENSE → Licence du projet.
└── 📄 README.md → Documentation générale.
```

## 🏁 **Installation et Exécution**
```bash
# Cloner le dépôt
git clone https://github.com/user/CardioMind.git
cd CardioMind

# Installer les dépendances
pip install -r requirements.txt

# Lancer Jupyter Notebook
jupyter notebook
```
