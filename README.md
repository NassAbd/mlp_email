# Email Classification avec un réseau de neurones (MLP)

<p align="center">
  <img src="./images/neural_network.png" alt="Neural network" width="600"/>
</p>

## Description

Ce notebook pédagogique propose une introduction à la classification de textes via un réseau de neurones, en se focalisant sur la détection de spams dans des emails. Le projet met en pratique :

* La préparation et le nettoyage d'un dataset (données d'emails avec labels "spam" et "ham").
* La transformation de données textuelles en représentations numériques (TF-IDF).
* La construction et l'entraînement d'un réseau de neurones de type Multi-Layer Perceptron (MLP).
* L'évaluation du modèle via différentes métriques.

Il permet d'aborder plusieurs concepts clés en apprentissage automatique et traitement du langage naturel (NLP).

## Objectifs pédagogiques

* Comprendre la préparation et le nettoyage d'un dataset textuel.
* Appliquer des transformations textuelles classiques (TF-IDF) pour le machine learning.
* Construire et entraîner un réseau de neurones simple pour la classification binaire.
* Evaluer un modèle à l'aide de métriques et d'analyses d'erreurs.
* Familiarisation avec des bibliothèques Python courantes pour la data science.

## Prérequis et dépendances

Ce notebook utilise les bibliothèques suivantes :

* pandas
* numpy
* matplotlib
* scikit-learn
* tensorflow
* ipython


Pour les installer :

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow ipython
```

## Structure du notebook

1. **Chargement et exploration des données** : visualisation, description, gestion des données manquantes.
2. **Préparation des données** : nettoyage, vectorisation TF-IDF des textes.
3. **Modélisation** : définition et entraînement du réseau de neurones (MLP).
4. **Evaluation** : matrices de confusion, rapports de classification.
5. **Analyses complémentaires** et observations.