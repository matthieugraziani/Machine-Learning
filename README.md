# <p align="center">Projet IA - Machine Learning</p>
# <p align="center">Anaylise de Survie</p>

Ce projet a pour but d'estimer le taux de survie en fonction de différentes caractéristiques telles que le type de tumeur et le traitement.

---

## 📚 Description du Dataset

**Fichier:** `brain_tumor_dataset.csv`
**Colonnes:** 19
**Rangées:** 20,000

Cet ensemble de données contient des données simulées pour le diagnostic des tumeurs cérébrales, le traitement et les détails des patients. Il se compose de 19 colonnes et de 20 000 rangées, fournissant des informations telles que les données démographiques des patients, les caractéristiques de la tumeur, les symptômes, les détails du traitement et les exigences de suivi. L’ensemble de données est conçu pour des projets d’apprentissage automatique axés sur la prédiction du type et de la gravité des tumeurs cérébrales, ainsi que sur la compréhension de diverses méthodes de traitement et des résultats pour les patients.

---

## ⚙️ Choix technique


Préprocessing/Normalisation :

 - OneHotEncoder : Conversion des objet en numérique
 - StandardScaler : Uniformisation de chaque variable


Modeles de regresssion :

 - Régression linéaire
 - Arbre de décision
 - Forêt aleatoire


** Il est pertinent de choisir des modèles de régression pour prédire une valaur numérique continue, on utilise des métriques comme l’erreur quadratique moyenne (MSE) ou le coefficient de détermination (R²), qui sont adaptées à la comparaison de valeurs continues. **


Optimisation :

 - GridSearch : optimisation de chaques paramêtres internes aux modèles de régression 



---

## 🗂️ Contenu du projet 

 - Survival_analysis.ipynb
 - requirements.txt
 - Readme.md

---

## 🗂️ Structure principale du notebook : Survival_analysis.ipynb

 - 1 - Librairies
 - 2 - Dataset
 - 3 - EDA
 - 4 - Preprocessing/Normalisation
 - 5 - Choix du modèle de regression
 - 6 - Optimisation
 - 7 - Visualisation
 - 8 - Prédiction

---

## 🛠️ Librairies utilisées

 - kagglehub
 - matplotlib
 - pandas
 - scikit-learn
 - seaborn

---

## 🔧 Installation

L'ensemble du programme fonctionne avec :
- la version 3.11.9 de python.
- La liste des packages listé dans "requirements.txt".

```bash
git clone git@github.com:matthieugraziani/Machine-Learning.git
cd Machine-Learning

python -m venv .venv
.venv\Scripts\activate

pip install -r requirements.txt
```
---

## 👤 Contact

matthieu.graziani007@gmail.com
