Blood Donation Prediction
Ce projet vise à prédire la probabilité de futurs dons de sang à l'aide de modèles de Machine Learning. En exploitant des données démographiques, comportementales et géographiques, il identifie les profils les plus susceptibles de redonner leur sang.

Objectifs

Nettoyer et structurer les données issues d’un questionnaire.
Analyser les comportements et tendances liés aux dons de sang.
Construire et comparer plusieurs modèles de classification.
Visualiser les résultats via des dashboards interactifs.


Modèles ML testés

Régression Logistique
K-Nearest Neighbors (KNN)
LightGBM
XGBoost
CatBoost (modèle le plus performant)

📌 Résultat : CatBoost atteint une précision (accuracy) de 91,25 %.

Technologies utilisées

Python : Pandas, NumPy, Scikit-learn, XGBoost, LightGBM, CatBoost
Jupyter Notebook : Analyse et modélisation
Power BI : Visualisations interactives
Git & GitHub : Gestion de version


Structure du projet
blood-donation-prediction/
├── Notebook Final – Prédiction des Dons de Sang.ipynb
├── requirements.txt
├── dashboard/
│   ├── 01_profil_demographique.png
│   ├── 02_culture_don.png
│   ├── 03_satisfaction_donneur.png
│   └── 04_region_map.png


Lancer le projet
🔧 Installation des dépendances
pip install -r requirements.txt

 Ouvrir le notebook
jupyter notebook "Notebook Final – Prédiction des Dons de Sang.ipynb"

 Aperçu des dashboards (Power BI)

Profil démographique des donneurs : Analyse des caractéristiques démographiques.
Attitudes et motivations : Étude des motivations des donneurs.
Satisfaction des donneurs : Évaluation de l’expérience des donneurs.
Cartographie régionale : Répartition géographique des dons.


Licence
Projet académique réalisé dans le cadre d’un PFA (Projet de Fin d’Année).Usage strictement pédagogique.
