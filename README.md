# Fraud Detection Project

This is the final project for a Big Data lesson (from Master 2 SISE at the _Université Lumière Lyon 2_) headed by [Guillaume METZLER](https://guillaumemetzler.github.io/). The aim of this project was to detect and predict fraud given certain features and using machine learning algorithms.

We had over 11 million real transactions from _Fichier National des Chèques Irréguliers_ (FNCI) and the _Banque de France_.

The original project can be found [here](https://github.com/adcastex/fouille_de_donnees) in French.

## Introduction 📚

Fraud detection is a challenge in machine learning due to the imbalance of classes (fraud vs. non-fraud). We aim to create effective predictive models using appropriate algorithms. We are investigating resampling techniques such as **SMOTEEN** and **Tomek Link** before running several machine learning algorithms to analyse the data.

## Methods 📊

1. **Resampling techniques:** SMOTEEN and Tomek Link algorithms to rebalance the classes and enhance the representation of frauds.
2. **Data analysis:** Several machine learning algorithms, including Decision trees, random forests, basic artificial neural networks, autoencoder, XGBoost, balanced random forests, ensemble models, k-Means, logistic regression to detect and predict fraud given certain features.
3. **Models' effectiveness evaluation:** Using F1-score, which is relevant in class imbalance problems.

## Results 📍

The maximum value for the F1-score is about 0.06.

## Conclusion 📎

Fraud detection in a context of class imbalance problems remains a significant challenge in machine learning. This project thus highlights the importance of developing more advanced methods to improve the performance of models in such situations.

## Authors ✏️

[Adrien CASTEX](https://github.com/adcastex), [Célia MAURIN](https://github.com/cemaurin), Annabelle NARSAMA
