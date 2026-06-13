
# 🌿 Advanced Machine Learning & Deep Learning

Bienvenue dans le dépôt principal regroupant mes travaux académiques pour le module **Apprentissage Automatique & Deep Learning Avancé** (Master 1 IA). Ce dépôt illustre l'exploration complète des modèles classiques de Machine Learning jusqu'aux architectures profondes de Deep Learning, couronnée par un projet intégrateur robuste.

## 📂 Structure du Dépôt

Ce repository est organisé en trois grands axes :

### 1. 🧠 Devoir Deep Learning (`/DL_Devoir`)
Focus sur l'entraînement et l'optimisation des architectures de réseaux de neurones convolutifs (CNN).
- **Notebook** : `notebook_DL_cnn_avances.ipynb`
- **Livrables** : Rapport complet d'analyse et Présentation PDF.

### 2. 🌳 Devoir Machine Learning - Boosting (`/ML_Devoir`)
Maîtrise des algorithmes ensemblistes et de Gradient Boosting pour la classification et la régression.
- **Notebook** : `notebook_ML_boosting (1).ipynb`
- **Livrables** : Rapport technique et Présentation PDF détaillant l'importance des variables et les performances.

### 3. 🚀 Projet Intégrateur Final (`/Projet_Integrateur`)
**Sujet** : Détection des maladies des plantes (Dataset PlantVillage).
Ce projet clôture le module en proposant un **Pipeline Hybride Industriel** combinant la puissance d'extraction du Deep Learning et l'interprétabilité du Machine Learning.
* **Extraction de caractéristiques** : Fine-tuning de l'architecture **ResNet-18**.
* **Réduction de dimensionnalité** : ACP (Analyse en Composantes Principales) de 512 à 85 composantes.
* **Méta-modèle de classification** : **XGBoost** (Accuracy Test : 98.62%).
* **Explicabilité (XAI)** : Validation visuelle via **Grad-CAM** et tabulaire via **SHAP**.
* **Livrables** : Code source complet (`.ipynb`) et rapport scientifique rédigé en LaTeX (`rapport_examen_pipeline_hybride.tex`).

## 🌍 Impact et Contexte Sahélien
Le projet intégrateur a été pensé pour répondre directement aux enjeux de sécurité alimentaire au Sahel et spécifiquement en **Mauritanie**. Le pipeline hybride proposé est conçu pour être frugal (faible consommation de VRAM en inférence), ce qui en fait un excellent candidat pour le déploiement de type **Edge AI** sur des smartphones agricoles dans des zones à connectivité limitée.

## 🛠️ Technologies & Outils Utilisés
* **Langages** : Python 3.10+, LaTeX
* **Deep Learning** : PyTorch, Torchvision
* **Machine Learning** : Scikit-Learn, XGBoost, LightGBM
* **Interprétabilité (XAI)** : SHAP, Grad-CAM (Captum / Torch-CAM)
* **Traitement de données** : Pandas, NumPy, Matplotlib, Seaborn

---
*Projet développé dans le cadre de l'année universitaire 2025-2026.*
