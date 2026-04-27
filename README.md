# Proyecto_DataMining_NN
Rugby &amp; AI: Minería y Redes Neuronales aplicadas al Top 14 francés


Este proyecto implementa un marco analítico avanzado que combina Minería de Datos y Aprendizaje Profundo Multitarea (MTL) para analizar el desempeño en la liga Top 14 de Francia. El objetivo es transformar estadísticas tácticas crudas y registros meteorológicos de Météo-France en conocimiento estratégico mediante modelos predictivos y descriptivos. La arquitectura incluye segmentación por K-Means, inferencia estadística mediante GLM (Poisson), modelos supervisados (XGBoost/Random Forest) y una red neuronal MTL para predecir simultáneamente el resultado del partido y los puntos concedidos. Se utiliza SHAP para garantizar la explicabilidad del modelo. Este repositorio constituye el proyecto final de la asignatura de Minería de Datos y Redes Neuronales de la Maestría en Ciencia de Datos en la Universidad Escuela Colombiana de Ingeniería Julio Garavito (Bogotá, Colombia).

This project implements an advanced analytical framework combining Data Mining and Deep Multi-Task Learning (MTL) to analyse performance in the French Top 14 league. The objective is to transform raw tactical statistics and Météo-France meteorological records into strategic insights using predictive and descriptive models. The architecture features K-Means clustering, statistical inference via Poisson GLM, supervised models (XGBoost/Random Forest), and an MTL neural network designed to simultaneously predict match outcomes and points conceded. SHAP is employed to ensure model explainability. This repository serves as the final project for the Data Mining and Neural Networks module of the Master’s in Data Science programme at Escuela Colombiana de Ingeniería Julio Garavito University (Bogotá, Colombia).

Ce projet met en œuvre un cadre analytique avancé combinant le Data Mining et l'Apprentissage Profond Multi-tâches (MTL) pour analyser les performances de la ligue Top 14 en France. L'objectif est de transformer les statistiques tactiques brutes et les relevés météorologiques de Météo-France en connaissances stratégiques via des modèles prédictifs et descriptifs. L'architecture comprend une segmentation par K-Means, de l'inférence statistique via GLM (Poisson), des modèles supervisés (XGBoost/Random Forest) et un réseau de neurones MTL pour prédire simultanément le résultat du match et les points concédés. SHAP est utilisé pour garantir l'explicabilité du modèle. Ce dépôt est dédié au projet final du cours de Data Mining et Réseaux de Neurones du Master en Science des Données de l'université Escuela Colombiana de Ingeniería Julio Garavito (Bogotá, Colombie).

Lenguaje: Python 3.12 

Extracción: BeautifulSoup, html, json, requests
Procesamiento: Pandas, NumPy
Modelado clásico: Scikit-learn, Statsmodels, XGBoost
Aprendizaje profundo: TensorFlow / Keras
Interpretabilidad: SHAP
Visualización: Matplotlib, Seaborn

Datos: LNR — Ligue Nationale de Rugby (estadísticas oficiales Top 14) y Météo-France (datos meteorológicos por estación)
