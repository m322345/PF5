![Entete](images/projet.png)

# 📌 Préparation des Données pour un Organisme de Santé Publique

## 📖 Contexte
L'agence **Santé publique France** souhaite améliorer la base de données **Open Food Facts**, qui fournit des informations nutritionnelles sur divers produits alimentaires. Actuellement, la saisie des données est manuelle, ce qui entraîne des erreurs et des valeurs manquantes.

L'objectif du projet est d'explorer et de nettoyer les données pour évaluer la **faisabilité d'un système de suggestion automatique** des valeurs manquantes.

## 🎯 Objectifs du Projet
- ✅ Nettoyer et explorer les données de **Open Food Facts**.
- ✅ Identifier et traiter les **valeurs aberrantes** et **valeurs manquantes**.
- ✅ Réaliser une **analyse univariée et bivariée** des données.
- ✅ Examiner la faisabilité d’un **système de complétion automatique**.
- ✅ Vérifier la conformité du projet avec les **principes du RGPD**.

## 🛠️ Étapes du Projet

### 1️⃣ **Nettoyage et Filtrage des Données**
- Identifier les **features pertinentes** (quantitatives et qualitatives).
- Sélectionner une variable cible avec plus de **50% de valeurs manquantes**.
- Supprimer les **doublons** et les entrées incomplètes.
- Automatiser le nettoyage pour garantir la **réutilisabilité** du code.

### 2️⃣ **Identification et Traitement des Valeurs Aberrantes**
- Détection par **visualisation** (boxplots, histogrammes, scatter plots).
- Utilisation de méthodes statistiques :
  - Plage interquartile (IQR), écart-type, etc.
- Traitement des valeurs aberrantes : suppression, remplacement ou catégorisation.

### 3️⃣ **Gestion des Valeurs Manquantes**
- Analyse des motifs de valeurs manquantes (**aléatoires ou systématiques**).
- Sélection de la meilleure méthode d’imputation :
  - **Statistiques** : moyenne, médiane, mode.
  - **Modèles avancés** : KNN, régression linéaire.

### 4️⃣ **Analyse Univariée et Bivariée**
- Étude des **distributions** des variables via histogrammes et boxplots.
- Identification des **corrélations** entre les variables via :
  - Matrices de corrélation, scatter plots.
- Sélection des variables ayant une influence sur la cible.

### 5️⃣ **Analyse Multivariée et Sélection des Variables**
- Visualisation avancée : PCA, ACP, ANOVA.
- Sélection des meilleures features pour un modèle de suggestion automatique.

### 6️⃣ **Présentation et Respect du RGPD**
- Explication des méthodes utilisées et des conclusions.
- Justification de la conformité aux **5 principes du RGPD**.
- Production d’une présentation claire pour un **public non technique**.

## 📦 Livrables Attendus
✅ Un **notebook Jupyter** documenté avec le processus de nettoyage et d’analyse.
✅ Un **dataset propre et structuré**.
✅ Des **visualisations graphiques** pour illustrer l’analyse.
✅ Une **présentation détaillée** expliquant la faisabilité du projet.

## 🚀 Objectif Final
Démontrer qu'il est possible d'améliorer la saisie des données d’**Open Food Facts** en développant un **système de suggestion automatique**, tout en respectant les normes du **RGPD** et en garantissant des données fiables.

---
📅 **Délai** : Mission à réaliser dans un temps limité.
👥 **Compétences requises** : Python, Pandas, Analyse de données, Visualisation.
🌍 **Source des données** : Open Food Facts.
