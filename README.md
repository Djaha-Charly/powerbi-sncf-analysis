# 📊 Analyse des Flux de Voyageurs SNCF en Île-de-France avec Power BI

## 📌 Contexte
Ce projet a été réalisé dans le cadre de mon apprentissage et portfolio en Business Intelligence. Il vise à analyser les flux de voyageurs dans les gares SNCF d’Île-de-France en utilisant Power BI, à partir de trois fichiers de données publiques.

## 📦 Données utilisées
- **gares.csv** : Liste des gares SNCF avec leurs coordonnées géographiques.
- **frequentation.csv** : Nombre de voyageurs par gare et par année.
- **voyageurs.csv** : Nombre de voyageurs montants et descendus par jour, heure et gare.

## ⚠️ Qualité des données
Les données présentaient plusieurs incohérences :
- Des années manquantes ou incomplètes (ex : 2015, 2018 et 2020 absentes dans `voyageurs.csv`)
- Un nombre limité de gares pour l'année 2024 (59 contre 248 en 2023)
- Des valeurs de segmentation parfois absentes

**Décisions prises** :
- Exclusion de certaines années des visualisations globales
- Création de tables et colonnes dérivées pour mieux structurer les données
- Remplacement des valeurs manquantes dans la segmentation par `Non classée`

## 🎯 Objectifs métier
1. Identifier les gares les plus fréquentées annuellement
2. Suivre l’évolution de la fréquentation entre les années
3. Visualiser la répartition géographique des flux voyageurs
4. Identifier les pics horaires et jours de forte affluence
5. Analyser les flux selon la segmentation DRG des gares

## 📊 Visualisations clés
- **Cartes géographiques** des gares par volume de voyageurs
- **Histogrammes dynamiques** filtrables par type de voyageurs
- **Carte thermique** des pics horaires par jour de semaine
- **Segments interactifs** par type de voyageurs et segmentation DRG

## 🛠️ Technologies utilisées
- Power BI Desktop
- DAX
- Power Query
- Git & GitHub

## 📁 Structure du dépôt
📦 Analyse_Flux_Voyageurs_SNCF/
 ┃    ┣ README.md
 ┃    ┣ gares.csv
 ┃    ┣ frequentation.csv 
 ┃    ┣ voyageurs.csv
 ┃    ┣ Analyse_SNCF.pbix   ----->   Fichier powerBI desktop

📂 captures/
 ┃    ┣ visuel1.png 
 ┃    ┣ visuel2.png 
 ┃    ┣ visuel3.png 

## 📎 Sources
- https://data.sncf.com/explore/dataset/frequentation-gares/
- https://data.sncf.com/explore/dataset/positions-geographiques-des-gares/
- https://data.sncf.com/explore/dataset/flux-donnees-horaires-voyageurs/

## 📌 Auteur
Charly William Djaha Yankep  
📍 Saint-Pierre-des-Corps, France  
🎯 Data Analyst Junior
