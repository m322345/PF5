![Entete](images/projet.png)

# 📌 Étude et Implémentation d’un Moteur de Classification d’Articles

## 📖 Contexte
L’entreprise **Place du Marché**, une marketplace e-commerce, souhaite automatiser l’**attribution des catégories d’articles** en s’appuyant sur les **descriptions textuelles et les images** des produits. Après une **étude de faisabilité**, l’objectif est désormais de **mettre en place un modèle de classification supervisée** basé sur les images et d’optimiser sa performance grâce à la **data augmentation**.

Par ailleurs, une extension des catégories d’articles est prévue, impliquant une collecte de nouveaux produits via l’**API OpenFood Facts**.

## 🎯 Objectifs du Projet
- ✅ Étudier la **faisabilité** d’un moteur de classification automatique.
- ✅ Mettre en place une **classification supervisée** d’images.
- ✅ Optimiser le modèle avec des techniques de **data augmentation**.
- ✅ Extraire et structurer des données via l’**API OpenFood Facts**.
- ✅ Présenter les résultats sous forme de **slides**.

## 🛠️ Étapes du Projet

### 1️⃣ **Étude de Faisabilité du Moteur de Classification**
- **Prétraitement des données** (nettoyage du texte, transformation des images).
- **Extraction de features** :
  - Texte : **Bag-of-Words, TF-IDF, Word2Vec, BERT, Universal Sentence Encoder**.
  - Images : **SIFT, ORB, CNN Transfer Learning**.
- **Réduction de dimension** (PCA, t-SNE, UMAP) pour visualisation des catégories.
- **Analyse de regroupement automatique** et validation de la faisabilité.

### 2️⃣ **Implémentation de la Classification Supervisée**
- Utilisation d’un **modèle CNN (TensorFlow/Keras ou PyTorch)**.
- Expérimentation avec **data augmentation** (rotation, zoom, modification du contraste).
- Évaluation avec des **métriques de classification** (accuracy, F1-score).

### 3️⃣ **Extraction de Données via l’API OpenFood Facts**
- Accès et requêtage de l’**API OpenFood Facts**.
- Récupération des **10 premiers produits contenant “champagne”**.
- Sauvegarde des données sous format **CSV** :
  - `foodId, label, category, foodContentsLabel, image`

### 4️⃣ **Présentation et Justification des Résultats**
- Structuration d’une **présentation** :
  - Objectifs et problématique
  - Analyse exploratoire et extraction de features
  - Implémentation du modèle de classification
  - Résultats et interprétation
  - Test de l’API OpenFood Facts

## 📦 Livrables Attendus
- ✅ Un **notebook exploratoire** sur la faisabilité du moteur de classification.
- ✅ Des **visualisations 2D** illustrant la séparation des catégories.
- ✅ Une **analyse comparative** des différentes méthodes utilisées.
- ✅ Une **conclusion** sur la faisabilité du moteur de classification.
- ✅ Un **modèle de classification supervisée** d’images.
- ✅ Un **notebook/script Python** pour l’extraction de données via API.
- ✅ Un **fichier CSV** contenant les produits collectés.
- ✅ Une **présentation détaillée** des résultats.

## 🚀 Objectif Final
Déterminer si les **descriptions textuelles et les images** permettent de **classifier automatiquement** les articles de la marketplace, en vue d’un moteur de classification à grande échelle.

---
- 👥 **Compétences requises** : NLP, Computer Vision, Deep Learning, API REST, Machine Learning.
- 🌍 **Technologies** : Python, Sklearn, BERT, TensorFlow/Keras, PyTorch, OpenCV, Pandas, OpenFood Facts API.
