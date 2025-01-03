# 🌟 Projet ANN - Classification des Vêtements 👕👗
Introduction
Bienvenue dans ce projet d'entraînement d'un réseau de neurones artificiels (ANN) sur un dataset de vêtements. 🚀 Ce guide explique comment configurer, entraîner et évaluer le modèle.

## 🛠️ Prérequis
Python
Assurez-vous d'avoir installé Python 3.8 ou une version supérieure.

Pip
Pip doit être installé pour gérer les dépendances.

Git
Utilisez Git pour cloner le dépôt.

## 📥 Installation
### Étape 1 : Clonez le dépôt 🌐
Clonez le projet avec la commande suivante :
bash
Copier le code
git clone https://github.com/amagourmeriem/Model_CNN.git 
cd ann-fashion-classification  
### Étape 2 : Créez un environnement virtuel 🐾
Créez un environnement virtuel pour isoler les dépendances :
Sur Linux/Mac :
bash
Copier le code
python -m venv venv  
source venv/bin/activate  
Sur Windows :
bash
Copier le code
python -m venv venv  
venv\Scripts\activate  
### Étape 3 : Installez les dépendances 📦
Installez les bibliothèques nécessaires :
bash
Copier le code
pip install -r requirements.txt  
## 📊 Dataset
Étape 1 : Téléchargez et préparez le dataset 📂
Téléchargez le dataset (par exemple, Fashion MNIST) et placez-le dans le dossier data/.
Assurez-vous que les fichiers train.csv et test.csv sont présents.
## 🚀 Entraînement
### Étape 1 : Entraînez le modèle ANN
Lancez l'entraînement avec la commande suivante :
bash
Copier le code
python train.py --epochs 20 --batch-size 32  
Les checkpoints du modèle seront sauvegardés dans le dossier models/.
## 📈 Évaluation
### Étape 1 : Évaluez le modèle
Utilisez la commande suivante pour évaluer le modèle sur le jeu de test :
bash
Copier le code
python evaluate.py --model models/best_model.h5  
Les métriques telles que la précision et la matrice de confusion s'afficheront dans la console.
## 📤 Prédiction
### Étape 1 : Prédisez de nouveaux exemples
Pour prédire sur de nouveaux échantillons, utilisez :
bash
Copier le code
python predict.py --input data/new_samples.csv  
Les résultats seront enregistrés dans le fichier predictions.csv.
## 🛠️ Dépannage
Problèmes courants
Mémoire insuffisante : Essayez de réduire la taille des lots avec --batch-size.
Erreurs ou bugs : Consultez les logs dans le dossier logs/.
## Support
Pour toute question ou suggestion, ouvrez une issue ou contactez-moi à mariemamagour317@gmail.com.

