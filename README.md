# 📚 Analyse des ventes d'une librairie en ligne

## 🎯 Objectif

Analyser les ventes d'une librairie en ligne afin de comprendre les performances commerciales, le comportement des clients et les facteurs influençant les achats.

## 📌 Contexte

Projet réalisé dans le cadre de la formation **Data Analyst OpenClassrooms**.

La librairie LaPage, historiquement présente en magasin physique, a développé une activité e-commerce. L'entreprise souhaite mieux exploiter ses données afin de piloter son activité commerciale et améliorer sa connaissance client.

## ❓ Problématique

Comment exploiter les données de ventes en ligne pour identifier les produits performants, comprendre les comportements d'achat et orienter les décisions marketing et commerciales ?

## 📂 Sources de données

### Products

Informations sur les produits :

* Identifiant produit
* Prix
* Catégorie

### Customers

Informations clients :

* Identifiant client
* Sexe
* Année de naissance

### Transactions

Historique des ventes :

* Date de transaction
* Client
* Produit acheté
* Session de navigation

## 🛠️ Méthodologie

### Préparation des données

* Contrôle des clés primaires
* Nettoyage des données
* Suppression des lignes vides
* Conversion des types de données
* Fusion des différentes tables

### Analyse exploratoire

* Évolution du chiffre d'affaires
* Analyse des ventes mensuelles
* Répartition du CA par catégorie
* Analyse des volumes vendus
* Analyse des clients

### Analyse statistique

* Test du Khi²
* Corrélation de Spearman
* Test de Kruskal-Wallis
* Courbe de Lorenz
* Coefficient de Gini

## 📊 Analyses réalisées

### Performance commerciale

* Évolution du chiffre d'affaires
* Nombre de transactions
* Produits vendus
* Répartition du CA par catégorie

### Analyse produits

* Top 10 des produits générant le plus de chiffre d'affaires
* Flop 10 des produits
* Répartition des références par catégorie

### Analyse clients

* Nombre de clients actifs
* Identification B2B / B2C
* Concentration du chiffre d'affaires

### Analyse comportementale

* Impact du genre sur les achats
* Impact de l'âge sur les dépenses
* Impact de l'âge sur la fréquence d'achat
* Impact de l'âge sur le panier moyen
* Analyse des préférences de catégories selon l'âge

## 📈 Principaux résultats

### Chiffre d'affaires

* Forte contribution de la catégorie 1 au chiffre d'affaires global
* La catégorie 0 génère beaucoup de ventes mais peu de valeur

### Concentration des ventes

* Le chiffre d'affaires est concentré sur une minorité de clients
* Coefficient de Gini de 0,44 indiquant une répartition inégale des revenus

### Comportement client

* Les clients jeunes génèrent des paniers moyens plus élevés
* Les clients plus âgés achètent plus fréquemment
* Les préférences de lecture varient selon l'âge

### Analyse statistique

* Relation significative entre le genre et les catégories de livres achetées
* Corrélations significatives entre l'âge et plusieurs comportements d'achat
* Différences d'âge significatives selon les catégories de livres consommées

## 💡 Recommandations

* Développer des campagnes marketing ciblées selon les segments d'âge
* Valoriser les catégories à forte marge
* Fidéliser les clients à forte contribution
* Adapter les recommandations produits selon le profil client

## 🧰 Technologies utilisées

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook

## 📁 Structure du projet

```text
data/
│
├── products.csv
├── customers.csv
├── transactions.csv

notebooks/
│
├── analyse_librairie.ipynb

presentation/
│
├── support_presentation.pdf

README.md
```

## ✅ Compétences développées

* Data Cleaning
* Analyse exploratoire
* Data Visualisation
* Analyse comportementale
* Statistiques appliquées
* Tests d'hypothèses
* Segmentation clients
* Storytelling de données
* Recommandations business

## 👨‍💻 Auteur

**Mohamed Zaidi**
