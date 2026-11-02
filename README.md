# Nettoyage et exploration d'un dataset financier

## Contexte
Premier projet du portfolio data analyst. Objectif : prendre en main 
pandas et Jupyter sur un cas réel — charger, nettoyer et explorer des 
données boursières (Apple, 2022-2025).

## Question de cadrage
Comment le cours et la volatilité d'Apple ont-ils évolué entre 2022 et 
aujourd'hui, et y a-t-il des anomalies dans les données à corriger 
avant toute analyse ?

## Démarche
1. Récupération des cours historiques AAPL via l'API yfinance
2. Vérification de la structure des données (types, valeurs manquantes)
3. Contrôle des doublons et des incohérences (prix négatifs, High < Low)
4. Statistiques descriptives et visualisation du cours et de la volatilité
5. Rédaction d'une note de synthèse

## Résultat principal
Dataset propre (aucune valeur manquante ni incohérence sur 1003 
observations). Cours de clôture entre 122,83 $ et 285,41 $ sur la 
période. Pic de volatilité marqué mi-2025 (~0,70 annualisé), signe 
d'un choc de marché.

## Outils utilisés
Python, pandas, yfinance, matplotlib, Jupyter Notebook

## Comment relancer le projet
pip3 install pandas numpy yfinance matplotlib jupyter
Ouvrir exploration.ipynb et exécuter les cellules dans l'ordre.