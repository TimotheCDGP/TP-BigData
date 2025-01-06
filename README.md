# 📊 **Projet BigData : Analyse des Pokémon**

## 🎓 **Contexte**
Ce projet a été réalisé dans le cadre d'un TP de Big Data. L'objectif principal est d'explorer et d'analyser les interactions des Pokémon en combat, notamment leurs forces, faiblesses, et résistances selon leurs types, tout en mettant en œuvre une architecture de type **Lakehouse**.

---

## 🧑‍🤝‍🧑 **Membres du Groupe**
- **PEYREGNE Timothé**
- **RAIS Adel**
- **MANGUIN Charles**

---

## 📝 **Description**
### **But du projet**
- Nettoyer, transformer, et analyser les données Pokémon pour extraire des insights sur leurs interactions en combat.
- Implémenter une architecture **Lakehouse** comprenant :
  - Une zone de staging (**Bronze**),
  - Une zone de transformation (**Silver**),
  - Une zone d'analyse finale (**Gold**).
- Visualiser les résultats et produire un rapport final.

---

## 📂 Structure du Projet
├── datasets/ Contient les fichiers de données bruts extraits de Kaggle
├── notebooks/ Notebooks Databricks pour le traitement et l'analyse des données
├── report/ Rapport Compte rendu du projet
├── README.md Ce fichier
└── .gitignore Fichiers et dossiers à ignorer dans Git

---

## 🔗 **Sources des Données**
Les données utilisées dans ce projet proviennent de Kaggle :
- [Pokémon Dataset 1](https://www.kaggle.com/datasets/rounakbanik/pokemon) : Statistiques des Pokémon.
- [Pokémon Dataset 2](https://www.kaggle.com/datasets/mrdew25/pokemon-database/data) : Informations détaillées (types, interactions, etc.).

Ces fichiers sont également disponibles dans le dossier `/datasets` pour un usage local.

---

## 🛠️ **Outils et Technologies**
- **Airbyte** : Pour l'ingestion de données depuis les fichiers CSV.
  - [Site officiel d'Airbyte](https://github.com/airbytehq/airbyte)
- **Azure Blob Storage** : Utilisé comme stockage cloud pour les zones **Bronze**, **Silver**, et **Gold**.
- **Databricks Notebooks** : Pour le traitement et l'analyse des données avec PySpark.
- **Python** : Bibliothèques :
  - **Pandas**, **Seaborn**, **Matplotlib** pour les visualisations et analyses statistiques.
  - **PySpark** pour les transformations sur Databricks.

---

## 📊 **Rapport Final**
Le rapport complet, incluant :
- Le modèle conceptuel des données (MCD).
- Les étapes de transformation et nettoyage.
- Les analyses des interactions des Pokémon en combat.
- Les visualisations clés (corrélations, forces/faiblesses).

📄 **Lien vers le rapport :** [`Big data.pdf`](Big%20data.pdf)

---
