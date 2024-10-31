# OPC_DATA_ANALYST_PROJET10
Détectez des faux billets avec R ou Python

# Identification Automatique des Faux Billets - Projet ONCFM

## Contexte

Je suis consultant Data Analyst au sein d'une entreprise spécialisée dans la data, et je réalise actuellement une mission en régie pour l'**Organisation nationale de lutte contre le faux-monnayage (ONCFM)**. Cette institution cherche à mettre en place une modélisation capable d'identifier automatiquement les faux billets en euros en se basant uniquement sur certaines dimensions et caractéristiques physiques des billets.

Dans le cadre de cette mission, je travaille sous la supervision de **Marie**, responsable du projet d’analyse de données à l’ONCFM. Elle m'accorde une grande autonomie pour explorer différentes approches de modélisation et souhaite une présentation finale des résultats incluant les analyses réalisées, les pistes explorées, et le modèle final sélectionné.

## Objectifs du Projet

1. **Préparation et Nettoyage des Données** : Explorer et nettoyer les données pour assurer leur qualité, notamment en traitant les valeurs manquantes et en vérifiant la cohérence des dimensions et caractéristiques des billets.
   
2. **Exploration et Analyse des Données** : Analyser les données pour identifier les patterns et différences entre les vrais et faux billets, afin de guider la sélection des variables et des méthodes de modélisation.

3. **Développement d'un Modèle de Classification** : Construire un modèle de machine learning capable de classer les billets en « vrai » ou « faux ». Plusieurs approches de modélisation seront explorées pour comparer leurs performances.

4. **Présentation des Résultats** : Présenter les résultats finaux à Marie, incluant le modèle choisi, les analyses préalables, et les pistes explorées.

## Étapes du Projet

### Étape 1 : Préparation et Nettoyage des Données

- **Objectif** : Préparer le jeu de données pour l’analyse en traitant les valeurs manquantes et en effectuant un nettoyage des variables.
- **Détails** :
  - Identifier et traiter les valeurs manquantes, en utilisant des méthodes comme la régression linéaire si cela est pertinent (inspiré par le conseil d’un collègue).
  - Vérifier la cohérence des valeurs pour chaque variable et détecter d’éventuels outliers qui pourraient influencer la modélisation.
- **Livrable** : Un notebook contenant les étapes de préparation et de nettoyage des données.

### Étape 2 : Analyse Exploratoire des Données (EDA)

- **Objectif** : Analyser les données pour comprendre les différences entre les vrais et faux billets et sélectionner les caractéristiques les plus pertinentes pour la modélisation.
- **Détails** :
  - Examiner la distribution des dimensions et autres caractéristiques des billets.
  - Utiliser des visualisations pour identifier les patterns distinctifs entre les vrais et faux billets.
  - Calculer des statistiques descriptives pour chaque variable et effectuer des tests statistiques si nécessaire.
- **Livrable** : Un notebook contenant l'analyse exploratoire et les visualisations associées.

### Étape 3 : Modélisation et Sélection du Modèle

- **Objectif** : Construire un modèle de machine learning pour classer les billets en vrais ou faux.
- **Méthodes** :
  - Tester plusieurs modèles de classification, tels que **régression logistique**, **k-nearest neighbors (KNN)**, **forêts aléatoires (Random Forest)**, et **SVM (Support Vector Machine)**.
  - Comparer les performances des modèles à l'aide de métriques telles que la précision, le rappel et le score F1.
  - Affiner le modèle sélectionné pour maximiser sa capacité de détection des faux billets.
- **Livrable** : Un notebook contenant les différentes étapes de modélisation, les performances des modèles testés, et le modèle final retenu.

### Étape 4 : Présentation des Résultats

- **Objectif** : Présenter les résultats du projet à Marie, en expliquant la méthodologie, les analyses, et le modèle final de manière compréhensible pour les parties prenantes.
- **Détails** :
  - Expliquer les étapes de préparation et d’analyse des données.
  - Présenter les modèles explorés et les performances de chacun.
  - Justifier le choix du modèle final et interpréter les résultats pour la détection des faux billets.
- **Livrable** : Présentation PowerPoint ou document structuré contenant un résumé des résultats et recommandations.

## Détails Techniques

- **Fichiers** :
  - `Dataset Faux Billets` : Jeu de données fourni par l'ONCFM, contenant les caractéristiques physiques des billets en euros.
  - **Notebook de Préparation des Données** : Document de travail contenant les étapes de nettoyage et d'analyse exploratoire.
  - **Notebook de Modélisation** : Document de travail pour le développement et la comparaison des modèles de classification.

- **Outils Utilisés** :
  - Langage de programmation : **Python** ou **R** (selon le choix pour le développement du modèle).
  - **Algorithmes de Machine Learning** : Régression logistique, k-nearest neighbors, Random Forest, SVM.
  - **Visualisation de données** : Pour l’analyse exploratoire et la présentation des résultats.

- **Compétences Utilisées** :
  - Préparation et nettoyage de données.
  - Analyse exploratoire pour comprendre les différences entre vrais et faux billets.
  - Développement de modèles de machine learning pour la classification.
  - Communication des résultats aux parties prenantes.

## Résumé

Ce projet vise à développer un modèle de classification capable de détecter automatiquement les faux billets en euros. En explorant différentes méthodes de modélisation et en sélectionnant les caractéristiques les plus pertinentes, je fournirai à l’ONCFM une solution data-driven pour lutter contre la contrefaçon des billets. Les résultats de cette mission soutiendront les efforts de l'ONCFM dans la détection des contrefaçons, renforçant ainsi la sécurité financière.
