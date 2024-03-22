# 9_methodes_ensemble_california_housing

Exploration des Méthodes d'Ensemble dans le Machine Learning

Introduction:
Les méthodes d'ensemble sont des approches puissantes en apprentissage automatique, se positionnant aux côtés de l'apprentissage profond en termes de performance. L'objectif de ce projet est de développer une compréhension approfondie de ces méthodes. Pour ce faire, nous créerons un notebook Markdown présentant les concepts essentiels liés aux méthodes d'ensemble, suivant le plan ci-dessous :

Plan de la Présentation:

Principe Général des Méthodes d'Ensemble:

Définition du concept fondamental des méthodes d'ensemble en apprentissage automatique.
Bagging et Pasting:

Explication des différences entre le "Bagging" et le "Pasting".
Évaluation "Out-Of-Bag":

Compréhension de l'évaluation "Out-Of-Bag" et son utilité.
Méthode de "Random Patches":

Exploration de la méthode de "Random Patches" et de son application.
Méthode de "Random Subspaces":

Analyse détaillée de la méthode de "Random Subspaces" et de son utilisation.
RandomForest:

Description approfondie de ce qu'est une RandomForest, incluant les concepts précédemment présentés intégrés dans ce modèle.
Paramètres de RandomForestRegressor (Scikit-Learn):

Explication exhaustive de tous les paramètres de la fonction "RandomForestRegressor" de la librairie Scikit-Learn.
Mise en Pratique:

Préparation des Données:

Chargement du jeu de données "California Housing Dataset".
Application de la fonction train_test_split() et autres préparations nécessaires.

Entraînement et Évaluation sur le Jeu d'Apprentissage:

Chargement du jeu d'apprentissage.
Entraînement du modèle avec validation croisée et optimisation des hyperparamètres en utilisant RandomForest et régression linéaire multiple.
Évaluation et affichage des performances du modèle sur le jeu d'apprentissage.

Évaluation sur le Jeu de Test:

Chargement des données de test.
Évaluation des performances du modèle entraîné dans le Notebook précédent sur le jeu de test.
Affichage des performances obtenues.
Question Subsidiaire:
Comparaison des performances de la RandomForest avec celles d'un modèle de régression linéaire multiple sur le jeu de test.

Livrables Attendus:

Un notebook Markdown présentant les concepts essentiels des méthodes d'ensemble.
Jupyter Notebook organisé selon les étapes décrites dans la section "Mise en Pratique".
