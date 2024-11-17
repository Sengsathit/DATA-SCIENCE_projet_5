![Classification automatique des biens de consommation](https://raw.githubusercontent.com/Sengsathit/OCR_data_scientist_assets/main/header_place_de_marche.png)

# PROJET : Classification automatique des biens de consommation

On considère, pour ce projet, l'entreprise fictive **Place du Marché** qui développe une marketplace anglophone. Actuellement, l'attribution des catégories des articles est effectuée manuellement par les vendeurs, ce qui engendre des incohérences et limite l'efficacité à mesure que le volume d'articles augmente.

Pour améliorer l'expérience utilisateur et préparer un passage à l'échelle, vous êtes chargé de mettre en œuvre une solution de classification automatique des articles à partir de leurs descriptions textuelles et images.

## Objectifs

1. Étudier la faisabilité d'un moteur de classification : 
- Utiliser les textes et images des articles pour regrouper automatiquement des produits similaires. 
- Réaliser une analyse visuelle et quantitative de la pertinence des regroupements. 
- Tester différentes approches pour extraire les caractéristiques pertinentes des données.
2. Mettre en place une classification supervisée : 
- Former un modèle de classification des images en utilisant des techniques avancées comme le CNN Transfer Learning. 
- Mettre en œuvre des stratégies de data augmentation pour améliorer les performances du modèle.
3. Tester une API de collecte de données :
- Collecter des données supplémentaires via une API (par exemple, produits à base de "champagne").
- Exporter les résultats dans un fichier CSV structuré pour une intégration future.

## Structure du dépôt

- `1_notebook_pretraitement_feature_extraction_faisabilite.ipynb` : Ce notebook est dédié au prétraitement des données textuelles et visuelles ainsi qu’à l’extraction des caractéristiques (features) nécessaires pour évaluer la faisabilité d’un moteur de classification.
- `2_notebook_classification.ipynb` : Ce notebook se concentre sur la mise en œuvre de modèles de classification supervisée, principalement basés sur des images.
- `3_script_python.ipynb` : Ce fichier contient un script Python structuré pour interagir avec une API externe et automatiser la collecte de données.
- `requirements.txt` : Liste des dépendances Python nécessaires pour exécuter les notebooks.

---

## Prérequis

Pour exécuter ce projet, vous aurez besoin de Python (version 3.8 ou supérieure). Il est également recommandé d'utiliser un environnement virtuel pour isoler les dépendances du projet.

### Étapes pour créer et activer un environnement virtuel :

1. Créez un environnement virtuel :
   ```bash
   python -m venv .venv
   source .venv/bin/activate

2. Installez les dépendances :
   ```bash
   pip install -r requirements.txt
