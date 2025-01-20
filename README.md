# Reconnaissance de chiffres manuscrits avec des réseaux de neurones

## Description

Ce projet consiste à développer un système capable de reconnaître des chiffres manuscrits en utilisant des techniques d'apprentissage profond. Deux types de modèles de réseaux neuronaux ont été implémentés et comparés :
1. **Réseaux de neurones multicouches (MLP)**.
2. **Réseaux de neurones convolutifs (CNN)**.

Le modèle CNN s'est révélé plus performant grâce à sa capacité à capturer des caractéristiques spatiales complexes dans les images.

## Fonctionnalités

- Chargement des données MNIST, un jeu de données standard pour la reconnaissance de chiffres manuscrits.
- Implémentation de deux types de modèles de réseaux neuronaux :
  - Modèle MLP (Multilayer Perceptron).
  - Modèle CNN (Convolutional Neural Network).
- Entraînement et validation des modèles.
- Comparaison des performances des deux modèles.
- Test des modèles avec des images manuscrites externes.
- Visualisation des résultats et des prédictions.

## Résultats

| Modèle                    | Précision sur les données de test |
|---------------------------|-----------------------------------|
| Réseau de neurones MLP    | **97.59%**                       |
| Réseau de neurones CNN    | **99.15%**                       |

Le modèle CNN a démontré de meilleures performances, notamment pour des images manuscrites externes.

## Prérequis

Avant de lancer ce projet, assurez-vous d'avoir installé les bibliothèques suivantes :
- TensorFlow
- NumPy
- Matplotlib
- OpenCV (pour tester avec des images externes)

Pour installer les dépendances, vous pouvez utiliser la commande suivante :
```bash
pip install tensorflow numpy matplotlib opencv-python
