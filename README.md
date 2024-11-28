# 🎵 Music Genre Classification Project with PCA and Logistic Regression

## 📋 Description du projet
Ce projet vise à **prédire les genres musicaux manquants** dans un dataset musical en utilisant des techniques d'apprentissage automatique et d'analyse en composantes principales (PCA). En réduisant la dimensionnalité des données tout en conservant l'essentiel de l'information, le modèle de régression logistique permet de remplir les valeurs manquantes de la colonne **"Genre"** de manière précise et efficace.

---

## 🛠️ Technologies utilisées
- **Python** : Langage principal pour la manipulation des données et la création des modèles.
- **Bibliothèques principales** :
  - `pandas` et `numpy` : Manipulation et analyse des données.
  - `scikit-learn` : Réduction de dimensionnalité avec PCA et création du modèle de régression logistique.
  - `matplotlib` et `seaborn` : Visualisation des données et graphiques.
- **Outils statistiques et de machine learning** :
  - **PCA (Principal Component Analysis)**
  - **Régression logistique**
  - Évaluation des modèles avec des métriques comme l'accuracy et le rapport de classification.

---

## 📁 Structure du projet
- **`music_dataset_mod.csv`** : Dataset contenant les caractéristiques musicales et la colonne **"Genre"**, avec des valeurs manquantes.
- **Code source** :
  - Préparation et exploration des données.
  - Visualisation des distributions de genres et corrélations.
  - Réduction de dimensionnalité avec PCA.
  - Modélisation avec régression logistique.
  - Prédiction et remplissage des genres manquants.
- **Résultats visuels** :
  - Matrice de corrélation.
  - Variance cumulée pour la sélection des composantes principales.
  - Histogrammes et graphiques des genres après prédiction.

---

## 🚀 Étapes du projet
1. **Exploration et nettoyage des données** :
   - Analyse des valeurs manquantes.
   - Visualisation de la répartition des genres.
2. **Analyse de corrélation** :
   - Étude des relations entre les différentes caractéristiques du dataset.
3. **Réduction de dimensionnalité avec PCA** :
   - Identification du nombre optimal de composantes principales pour capturer au moins 80 % de la variance.
4. **Création et entraînement du modèle** :
   - Régression logistique sur les données réduites.
5. **Prédiction et remplissage des genres** :
   - Remplissage des valeurs manquantes avec les prédictions du modèle.
6. **Évaluation des performances** :
   - Comparaison des performances entre les données PCA et les données originales.

---

## 🎯 Résultats
- **Nombre de composantes principales** : Le PCA a permis de réduire les données à un nombre minimal de dimensions tout en expliquant plus de 80 % de la variance.
- **Modèle performant** : La régression logistique a atteint une précision élevée pour la classification des genres.
- **Visualisations utiles** : Des graphiques intuitifs pour analyser les résultats et les genres prédits.
