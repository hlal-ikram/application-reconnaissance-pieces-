# 📸 Application de reconnaissance des pièces automobiles

Ce projet de machine learning vise à reconnaître des pièces automobiles à partir d'images grâce à des techniques d'apprentissage automatique. Développée dans un Jupyter Notebook (.ipynb), l'application propose une interface graphique avec Tkinter permettant de charger une image et d'obtenir une prédiction instantanée de la pièce identifiée.

## 🛠 Fonctionnalités
- Interface graphique avec Tkinter pour la sélection d'images.
- Extraction des caractéristiques des images à l'aide de VGG16 pré-entraîné.
- Classification des pièces avec plusieurs algorithmes de machine learning :
  - Support Vector Machine (SVM)
  - RandomForest
  - K-Nearest Neighbors (KNN)

## 📊 Algorithmes de machine learning testés
- **SVM** : Meilleure précision avec 75,6 %.
- **RandomForest** : Précision de 58,9 %.
- **KNN** : Précision de 33,2 %.

Le modèle SVM a été sélectionné pour l'intégration dans l'application finale en raison de sa meilleure performance.

## 🗂 Jeux de données
Le dataset utilisé pour ce projet est disponible sur Kaggle :
[Car Parts Dataset (50 classes)](https://www.kaggle.com/datasets).

## 🚀 Technologies utilisées
- **Python** pour l'implémentation.
- **TensorFlow** et **Keras** pour l'extraction des caractéristiques d'images avec le modèle VGG16.
- **scikit-learn** pour l'entraînement des modèles de classification (SVM, RandomForest, KNN).
- **Tkinter** pour l'interface graphique.
- **Pillow** pour la gestion et le traitement des images.

## 💻 Utilisation
1. Ouvrez le fichier `programme.ipynb` dans Jupyter Notebook.
2. Exécutez les cellules pour lancer l'interface graphique.
3. Cliquez sur "Sélectionner une image" pour charger une image de la pièce automobile.
4. Le système analysera l'image et affichera la prédiction dans la cellule du notebook ainsi que dans l'interface graphique.

## 🔍 Modèles utilisés
- **VGG16** : Modèle CNN pré-entraîné utilisé pour l'extraction des caractéristiques des images.
- **SVM** : Modèle sélectionné pour la classification finale en raison de ses performances optimales.

## 📈 Améliorations futures
- Augmentation du dataset pour améliorer la précision des prédictions.
- Exploration de nouveaux modèles de machine learning pour augmenter la robustesse et la précision des résultats.
- Optimisation de l'interface utilisateur pour une meilleure expérience.

## 📦 Installation
Clonez ce repository :
```bash
git clone https://github.com/hlal-ikram/application-reconnaissance-pieces.git
cd application-reconnaissance-pieces

Installez les dépendances requises :
```bash
pip install tensorflow keras scikit-learn pillow

Exécutez toutes les cellules du notebook pour lancer l'application.

