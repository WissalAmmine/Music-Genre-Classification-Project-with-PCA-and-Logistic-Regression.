**📋 Description du projet** <br>

Ce projet vise à prédire les genres musicaux manquants dans un dataset musical en utilisant des techniques d'apprentissage automatique et d'analyse en composantes principales (PCA). En réduisant la dimensionnalité des données tout en conservant l'essentiel de l'information, le modèle de régression logistique permet de remplir les valeurs manquantes de la colonne "Genre" de manière précise et efficace.
________________________________________
**🛠️ Technologies utilisées**<br>
•	Python : Langage principal pour la manipulation des données et la création des modèles.<br>
•	Bibliothèques principales :<br>
    o	pandas et numpy : Manipulation et analyse des données.<br>
    o	scikit-learn : Réduction de dimensionnalité avec PCA et création du modèle de régression logistique.<br>
    o	matplotlib et seaborn : Visualisation des données et graphiques.<br>
•	Outils statistiques et de machine learning :<br>
    o	PCA (Principal Component Analysis)<br>
    o	Régression logistique<br>
    o	Évaluation des modèles avec des métriques comme l'accuracy et le rapport de classification.<br>
________________________________________
**📁 Structure du projet**<br>
•	music_dataset_mod.csv : Dataset contenant les caractéristiques musicales et la colonne "Genre", avec des valeurs manquantes.<br>
•	Code source :<br>
    o	Préparation et exploration des données.<br>
    o	Visualisation des distributions de genres et corrélations.<br>
    o	Réduction de dimensionnalité avec PCA.<br>
    o	Modélisation avec régression logistique.<br>
    o	Prédiction et remplissage des genres manquants.<br>
•	Résultats visuels :<br>
    o	Matrice de corrélation.<br>
    o	Variance cumulée pour la sélection des composantes principales.<br>
    o	Histogrammes et graphiques des genres après prédiction.<br>
________________________________________
**🚀 Étapes du projet**<br>
1.	Exploration et nettoyage des données :<br>
  o	Analyse des valeurs manquantes.<br>
  o	Visualisation de la répartition des genres.<br>
2.	Analyse de corrélation :<br>
  o	Étude des relations entre les différentes caractéristiques du dataset.<br>
3.	Réduction de dimensionnalité avec PCA :<br>
  o	Identification du nombre optimal de composantes principales pour capturer au moins 80 % de la variance.<br>
4.	Création et entraînement du modèle :<br>
  o	Régression logistique sur les données réduites.<br>
5.	Prédiction et remplissage des genres :<br>
  o	Remplissage des valeurs manquantes avec les prédictions du modèle.<br>
6.	Évaluation des performances :<br>
  o	Comparaison des performances entre les données PCA et les données originales.<br>
________________________________________
**🎯 Résultats**<br>
•	Nombre de composantes principales : Le PCA a permis de réduire les données à un nombre minimal de dimensions tout en expliquant plus de 80 % de la variance.<br>
•	Modèle performant : La régression logistique a atteint une précision élevée pour la classification des genres.<br>
•	Visualisations utiles : Des graphiques intuitifs pour analyser les résultats et les genres prédits.<br>
