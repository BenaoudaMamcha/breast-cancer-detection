# Breast Cancer Detection with CNN (TensorFlow/Keras & PyTorch)

## Projet

Ce projet présente deux implémentations de la détection du cancer du sein à l'aide de réseaux de neurones convolutifs (CNN). La première version utilise **TensorFlow** et **Keras**, et la deuxième utilise **PyTorch**. 


## Description

La détection du cancer du sein est un problème de classification binaire (Cancer vs Non-Cancer) souvent étudié en Machine Learning et Deep Learning. Ce projet utilise un réseau de neurones convolutifs pour classer les images médicales en fonction de la présence de cancer. Les deux versions du modèle sont créées à l'aide de **TensorFlow/Keras** et **PyTorch**, ce qui permet de comparer les performances des deux frameworks.

### Objectifs du projet :
- Développer et comparer des modèles de classification d'images avec **TensorFlow** et **Keras** d'une part, et **PyTorch** de l'autre.
- Appliquer les techniques de Deep Learning pour résoudre un problème médical réel.
- Tester les performances des deux frameworks sur un même problème pour en tirer des conclusions sur leur efficacité et facilité d'utilisation.

## Technologies Utilisées

- **Python**: Langage principal utilisé pour l'implémentation.
- **TensorFlow** et **Keras**: Frameworks pour la création du modèle CNN dans la première version.
- **PyTorch**: Framework pour la création du modèle CNN dans la deuxième version.
- **OpenCV**: Pour le traitement d'images.
- **Matplotlib**: Pour la visualisation des résultats (graphes de précision et de perte).
- **Jupyter Notebooks / Google Colab**: Pour le développement interactif du modèle.

## Installation

1. Clonez ce dépôt sur votre machine locale :

    ```bash
    git clone https://github.com/BenaoudaMamcha/breast-cancer-detection.git
    cd breast-cancer-detection
    ```

2. Installez les dépendances nécessaires à l'aide de `pip` :

    ```bash
    pip install -r requirements.txt
    ```

   Le fichier `requirements.txt` inclut les bibliothèques nécessaires pour **TensorFlow/Keras** et **PyTorch**.

## Utilisation

### Version TensorFlow/Keras

1. **Préparer les données** : Le dataset d'images est stocké dans le répertoire `data/`. Vous pouvez l'ajouter manuellement ou utiliser le clonage GitHub pour récupérer le dataset.
   
2. **Entraîner le modèle avec TensorFlow/Keras** : Une fois les données prêtes, lancez l'entraînement du modèle en utilisant le script **TensorFlow** :

    ```bash
    python tensorflow_keras_model.py
    ```

    Ce script entraînera le réseau de neurones à l'aide de **TensorFlow** et **Keras** sur le dataset d'images.

3. **Visualiser les résultats** : À la fin de l'entraînement, des courbes de précision et de perte sont affichées pour évaluer les performances du modèle.

### Version PyTorch

1. **Préparer les données** : Les mêmes données sont utilisées pour la version PyTorch.

2. **Entraîner le modèle avec PyTorch** : Pour entraîner le modèle avec **PyTorch**, exécutez le script suivant :

    ```bash
    python pytorch_model.py
    ```

    Ce script implémente la version du modèle en utilisant **PyTorch**.

3. **Visualiser les résultats** : Comme avec la version TensorFlow, des courbes de performance (précision, perte) seront générées pour analyser le modèle.

## Résultats

Les performances du modèle sont mesurées sur la base de la précision et de la perte. Les deux versions du modèle (TensorFlow/Keras et PyTorch) sont comparées, et les résultats sont visualisés à l’aide de graphiques.

### Exemple de précision obtenue :
- **TensorFlow/Keras** :
  - Précision d'entraînement : 90%
  - Précision de validation : 87%

- **PyTorch** :
  - Précision d'entraînement : 88%
  - Précision de validation : 85%

## Structure du projet

breast-cancer-detection/
├── data/ # Données d'images du dataset
├── notebooks/ # Jupyter Notebooks ou Google Colab pour l'analyse
├── tensorflow_keras_model.py # Code du modèle avec TensorFlow/Keras
├── pytorch_model.py # Code du modèle avec PyTorch
├── requirements.txt # Liste des bibliothèques nécessaires
├── README.md # Documentation du projet
└── .gitignore # Fichiers à ignorer par Git



## À propos de moi

Si vous avez des questions ou souhaitez en savoir plus, n'hésitez pas à me contacter sur [mon LinkedIn](https://www.linkedin.com/in/benaouda-mamchaoui/) ou via GitHub.
