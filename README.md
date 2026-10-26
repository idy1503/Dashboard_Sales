# 📊 Analyse des ventes avec Power BI

## 📌 Présentation du projet

Ce projet consiste à analyser les performances commerciales à travers un tableau de bord interactif réalisé avec **Microsoft Power BI**.

L'objectif est de transformer les données de ventes en indicateurs exploitables afin de faciliter le suivi du chiffre d'affaires, l'analyse des commandes, l'évaluation des performances des produits et la comparaison des ventes entre différents pays.

Le rapport propose plusieurs vues complémentaires permettant d'explorer les données à différents niveaux de détail, de la synthèse globale des performances commerciales jusqu'à la consultation des transactions individuelles.

## 🎯 Objectifs du projet

- Analyser le chiffre d'affaires global et son évolution dans le temps.
- Suivre le nombre de commandes et les quantités de produits vendues.
- Calculer et analyser la valeur moyenne des commandes.
- Comparer les performances commerciales entre les différents pays.
- Identifier les produits qui contribuent le plus au chiffre d'affaires.
- Analyser les tendances mensuelles et trimestrielles des ventes.
- Concevoir un modèle de données structuré selon une architecture en étoile.
- Créer des mesures analytiques avec DAX.
- Concevoir un tableau de bord interactif facilitant l'exploration des données commerciales.

## 🛠️ Outils et technologies

| Outil | Utilisation |
|---|---|
| Microsoft Power BI | Création du tableau de bord et visualisation des données |
| Power Query | Préparation et transformation des données |
| DAX | Création de mesures et calcul des indicateurs clés de performance |
| Modélisation en étoile | Organisation du modèle de données et des relations entre les tables |

## 🏗️ Modélisation des données

Le modèle de données repose sur une **architecture en étoile (Star Schema)**, une approche de modélisation dimensionnelle adaptée à l'analyse décisionnelle.

Cette organisation permet de structurer les données transactionnelles et les dimensions d'analyse afin de faciliter l'exploitation des données dans Power BI.

La modélisation permet notamment de :

- Structurer les relations entre les tables du modèle.
- Organiser les données pour faciliter l'analyse multidimensionnelle.
- Simplifier la création et la maintenance des mesures DAX.
- Analyser les ventes selon différentes dimensions, notamment les produits, les pays et les périodes.
- Faciliter l'interaction entre les filtres et les visualisations du rapport.

## 🔄 Préparation et transformation des données avec Power Query

**Power Query** a été utilisé pour préparer et transformer les données avant leur exploitation dans le modèle analytique.

Cette étape permet de structurer les données afin de les rendre exploitables pour les calculs, les analyses et les visualisations.

Le processus de préparation des données constitue une étape essentielle pour assurer la cohérence entre les informations sources et les indicateurs présentés dans le tableau de bord.

## 🧮 Création des mesures analytiques avec DAX

Le langage **DAX (Data Analysis Expressions)** a été utilisé pour créer les mesures nécessaires au calcul des indicateurs clés de performance du tableau de bord.

Les principaux indicateurs suivis sont :

| Indicateur | Objectif |
|---|---|
| Chiffre d'affaires | Mesurer le montant total des ventes |
| Nombre de commandes | Suivre le volume des commandes |
| Nombre de pièces vendues | Mesurer les quantités de produits commercialisées |
| Valeur moyenne des commandes | Évaluer le montant moyen des commandes |

Ces mesures alimentent les visualisations du rapport et permettent d'analyser les performances commerciales en fonction des filtres et des dimensions sélectionnés.

## 📈 Présentation du tableau de bord

Le rapport est organisé autour de trois vues complémentaires.

### 📊 1. Vue d'ensemble des ventes

![Vue d'ensemble du tableau de bord](screenshots/vue-ensemble.png)

Cette page présente une synthèse des principales performances commerciales.

**Indicateurs clés de performance (KPI)**

- Chiffre d'affaires.
- Nombre de commandes.
- Nombre de pièces vendues.
- Valeur moyenne des commandes.

**Analyse géographique**
- Répartition du chiffre d'affaires par pays.
- Comparaison de la contribution des différents marchés aux ventes totales.

**Analyse des produits**
- Classement des produits selon le chiffre d'affaires généré.
- Identification des produits les plus performants.

**Évolution temporelle**
- Suivi de l'évolution mensuelle du chiffre d'affaires.
- Observation des variations entre les périodes.

Un filtre par année permet d'explorer les performances commerciales sur différentes périodes.

### 📋 2. Indicateurs clés des ventes

![Indicateurs clés des ventes](screenshots/indicateurs-cles-des-ventes.png)

Cette page propose une analyse détaillée des performances commerciales par pays et par période.

Le tableau regroupe les informations suivantes :

- **Pays :** pays dans lequel les ventes ont été réalisées.
- **Année :** année de réalisation des ventes.
- **Trimestre :** trimestre correspondant à la période analysée.
- **Mois :** mois de réalisation des ventes.
- **Chiffre d'affaires :** montant total des ventes.
- **Nombre de commandes :** nombre de commandes enregistrées.
- **Nombre de pièces vendues :** quantité totale de produits vendus.
- **Valeur moyenne des commandes :** montant moyen des commandes.

Cette vue facilite la comparaison des performances entre les pays et les périodes, ainsi que l'analyse des variations du chiffre d'affaires et du volume des commandes.

### 🧾 3. Détails des ventes

![Détails des ventes](screenshots/details-ventes.png)

Cette page permet de consulter les transactions commerciales à un niveau plus détaillé.

Le tableau présente les informations suivantes :

- Date de commande.
- Numéro de commande.
- Quantité commandée.
- Prix unitaire.
- Montant des ventes.
- Produit concerné.
- Pays de vente.

Des filtres par produit et par pays permettent de cibler les transactions correspondant aux critères sélectionnés.

Cette vue facilite la consultation des données détaillées et permet d'examiner les transactions à l'origine des résultats présentés dans les vues de synthèse.

## 🎛️ Interactivité du rapport

Le tableau de bord intègre des filtres permettant d'adapter l'analyse aux besoins de l'utilisateur.

Les filtres disponibles comprennent notamment :

- **Année :** explorer les performances sur différentes périodes.
- **Produits :** analyser les ventes d'un produit particulier.
- **Pays :** examiner les performances d'un marché spécifique.

Cette interactivité facilite l'exploration des données et la comparaison des performances commerciales selon différents critères.

## 🔍 Principaux axes d'analyse

Le tableau de bord permet notamment d'explorer les questions suivantes :

- Quel est le chiffre d'affaires total réalisé sur la période étudiée ?
- Quels pays contribuent le plus au chiffre d'affaires ?
- Quels produits génèrent les revenus les plus importants ?
- Comment le chiffre d'affaires évolue-t-il d'un mois à l'autre ?
- Comment le volume des commandes évolue-t-il dans le temps ?
- Quelle est la valeur moyenne des commandes ?
- Quelles différences observe-t-on entre les performances commerciales des pays ?
- Quelles transactions composent les résultats observés dans les indicateurs agrégés ?

Ces axes d'analyse contribuent à une meilleure compréhension des performances commerciales et facilitent l'exploration des données selon plusieurs dimensions.

## 🚀 Utilisation du projet

Pour explorer le tableau de bord :

1. Cloner ou télécharger le dépôt GitHub.
2. Ouvrir le fichier `.pbix` avec Microsoft Power BI Desktop.
3. Vérifier les chemins d'accès aux fichiers sources si le rapport utilise des données externes.
4. Actualiser les données si nécessaire.
5. Explorer les différentes vues du rapport.
6. Utiliser les filtres pour analyser les ventes par année, produit ou pays.

## 💡 Compétences mobilisées

Ce projet m'a permis de mettre en pratique les compétences suivantes :

- Préparation et transformation des données avec Power Query.
- Modélisation dimensionnelle selon une architecture en étoile.
- Organisation et gestion des relations entre les tables dans Power BI.
- Création de mesures analytiques avec DAX.
- Calcul et suivi des indicateurs clés de performance (KPI).
- Analyse des performances commerciales.
- Analyse temporelle du chiffre d'affaires.
- Comparaison des performances par pays et par produit.
- Conception de tableaux de bord interactifs.
- Visualisation et restitution de données pour faciliter la prise de décision.

## 👤 Auteur Lydie KOUAKOU

**Projet personnel de Data Analytics — Analyse des ventes**

Technologies : **Microsoft Power BI · Power Query · DAX · Modélisation en étoile**

---

*Ce projet illustre une démarche d'analyse de données commerciales combinant préparation des données, modélisation dimensionnelle, calcul d'indicateurs et visualisation interactive afin de faciliter le suivi et l'analyse des performances de vente.*
