# Enhancing Traffic Prediction with Self-Supervised Learning
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0-lightred)
![License](https://img.shields.io/badge/License-MIT-green)

Ce projet vise à améliorer la prédiction du trafic routier en utilisant des techniques d'apprentissage auto-supervisé (SSL) combinées à des modèles de réseaux de neurones GCN (Graph Convolutional Networks) et LSTM (Long Short-Term Memory). L'objectif est de prédire les conditions de trafic futures en exploitant des données spatio-temporelles, tout en réduisant la dépendance aux données étiquetées, souvent coûteuses et difficiles à obtenir.

Méthodologie : 

    Apprentissage auto-supervisé : Nous utilisons SimCLR pour pré-entraîner le modèle sur des données non étiquetées, en apprenant des représentations significatives des motifs de trafic.
    Modèle GCN+LSTM : Le modèle capture à la fois les dépendances spatiales (via GCN) et temporelles (via LSTM) pour prédire les flux de trafic.
    Augmentation des données : Des techniques comme l'injection de bruit, le redimensionnement et le décalage temporel sont utilisées pour améliorer la robustesse du modèle.

Résultats

    Le modèle affiche des performances prometteuses sur des métriques clés telles que la RMSE (Root Mean Squared Error) et la MAE (Mean Absolute Error).
    Les visualisations montrent une forte corrélation entre les prédictions et les valeurs réelles, démontrant l'efficacité de l'approche.
