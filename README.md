# *🏠 Objectif du projet*
Développer un modèle de régression linéaire multiple pour prédire le prix de l'immobilier à Paris à partir de diverses caractéristiques des logements.
# *📊 Données utilisées*
Le jeu de données contient 17 variables décrivant les propriétés immobilières, telles que :

* Taille (en m²), nombre de pièces, présence de jardin/piscine, nombre d'étages
* Année de construction, quartier, nombre de propriétaires précédents
* Sous-sol, grenier, garage, chambres d’hôtes, etc.
* Variable cible : price (prix du bien)
# *🧹 Prétraitement des données*
* Conversion des colonnes booléennes (hasYard, hasPool, etc.)
* Vérification des valeurs manquantes
* Analyse statistique descriptive
* Visualisation des corrélations (nuages de points, boxplots, heatmap)
# *🧠 Modélisation*
* Séparation des données : 70% entraînement / 30% test
* Pipeline de transformation :
    * Standardisation des variables numériques
    * Transformation des variables booléennes
* Modèle utilisé : LinearRegression (régression linéaire multiple)
# *📈 Évaluation du modèle*
* RMSE (Erreur quadratique moyenne)
* R² (Coefficient de détermination)
* MAE (Erreur absolue moyenne)
* MAPE (Erreur absolue moyenne en pourcentage)
* Visualisation des résidus et erreurs de prédiction avec Yellowbrick

# *💾 Déploiement*
* Le modèle est sauvegardé avec joblib pour une utilisation future.

# *📦 Exemple de prédiction*
* Une campagne de test est réalisée avec les caractéristiques suivantes :
    * 34 000 m², 4 pièces, jardin, piscine, 5 étages, etc.
* Le modèle prédit un **prix estimé** d’environ **\$3406944** (valeur fictive à titre d'exemple).


