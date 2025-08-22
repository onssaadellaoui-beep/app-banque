# Application de Prédiction de Crédit Bancaire

## Description
Cette application aide les banques à déterminer si une personne avec un profil donné peut obtenir un crédit ou non.  
Le modèle utilise des données de Kaggle pour prédire la probabilité d’acceptation d’un crédit selon les caractéristiques du client.

L’application est développée avec **Flask** et s’appuie sur un **template existant de GitHub** pour l’interface web.  
Le backend charge un modèle pré-entraîné (`model.pkl`) pour effectuer les prédictions.

---

## Dataset
- Les données utilisées proviennent de Kaggle (train set).  
- Elles ont été prétraitées et utilisées pour entraîner le modèle inclus dans le projet.  
- **Lien Kaggle ** : (https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)

---

## Outils et Technologies
- Python
- Flask (pour l’application web)
- Pandas / NumPy (prétraitement des données)
- Scikit-learn (modélisation et entraînement)
- Jupyter / Google Colab (exploration et entraînement du modèle)
- HTML / CSS (template pour l’interface web)

---

## Structure du projet
projetbanque/
│
├── app.py # Code principal de l'application
├── model.pkl # Modèle pré-entraîné
├── static/
│ └── css/
│ └── style.css # Styles de l'application

---

## Installation
1. Cloner le projet :  
```bash
git clone https://github.com/onssaadellaoui-beep/app-banque.git
pip install -r requirements.txt
python app.py
Ouvrir le navigateur à l’adresse : http://127.0.0.1:5000/
Remarques
Le modèle inclus est pré-entraîné sur le train set de Kaggle.
L’interface web utilise un template existant pour faciliter le déploiement.
Ce projet peut être amélioré en ajoutant des fonctionnalités comme :
Support pour de nouvelles données d’entrée
Visualisation des résultats
Gestion multi-utilisateur pour les banques
Auteur
Ons Saadellaoui
Licence : Libre pour usage académique et démonstration
├── templates/ # Templates HTML de l'application
├── README.md # Ce fichier
└── requirements.txt # Dépendances Python
