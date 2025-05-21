# Detecting-Twitter-Polluters
Comparative analysis of machine learning algorithms to classify polluting vs. legitimate users on Twitter (X)

## Description

Ce travail a été réalisé dans le cadre du Travail Pratique 1 du cours `Apprentissage Automatique (INF7370)`, offert durant la session d’hiver 2025 par M. Mouhamed Bouguessa à l’Université du Québec à Montréal (UQAM).

L’objectif principal est d’analyser et de comparer la performance de différents algorithmes de classification pour l’identification de comptes pollueurs sur Twitter (X), à partir de données réelles issues de tweets.

Les algorithmes à étudier sont :

1. Arbre de décision
2. Bagging
3. AdaBoost
4. Boosting de gradient (GBoost)
5. Forêts d’arbres aléatoires
6. Classification bayésienne naïve

Les données à traiter sont constituées de:

* 2 353 473 tweets postés par 22 223 utilisateurs pollueurs
* 3 259 693 tweets postés par 19 276 utilisateurs légitimes

## Contenu du dépôt

| Dossier/Fichier    | Description                                                             |
| ------------------ | ----------------------------------------------------------------------- |
| `data/`            | Contient les jeux de données             |
| `notebooks/`       | Notebooks Jupyter pour la préparation des données l'entraînement et l'évaluation des modèles |
| `README.md`        | Ce fichier de présentation                                              |
| `requirements.txt` | Dépendances Python nécessaires                                          |

## Étapes du projet

1. Préparation des données dans le fichier [`features_extraction.ipynb`](notebooks/features_extraction.ipynb)
2. Entraînement des 6 algorithmes et analyse comparative dans le fichier [`comparison_all_algorithms.ipynb`](notebooks/comparison_all_algorithms.ipynb)
3. Entraînement des 6 algorithmes sur données déséquilibrées et analyse comparative dans le fichier [`imbalanced_data_comparison.ipynb`](notebooks/imbalanced_data_comparison.ipynb)

## Insights Clés

* Les modèles de type Boosting (AdaBoost, GBoost) montrent une meilleure performance sur les données équilibrées.

* En cas de déséquilibre de classes, l’évaluation par AUC devient essentielle pour juger les performances.

## Technologies utilisées

* Python (Pandas, Scikit-learn, Scipy, Matplotlib)
* Jupyter Notebook
* Git

## Auteur

Rickiel Bamessi

Étudiant de Maîtrise en Informatique pour l'Intelligence et la Gestion des Données

Email : rickielsad@gmail.com

LinkedIn : [rickiel-sadrack-bamessi](linkedin.com/in/rickiel-sadrack-bamessi)