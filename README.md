# Deep Learning

Ce repository regroupe des notebooks d'apprentissage profond realises avec Python et PyTorch. L'objectif general est d'explorer plusieurs familles de modeles de deep learning sur des cas pratiques : classification tabulaire, classification d'images et modeles sequentiels pour la traduction automatique.

## Idee generale du projet

Le projet sert de support d'experimentation pour comprendre et comparer differentes architectures de reseaux de neurones :

- un reseau de neurones classique applique au jeu de donnees Breast Cancer ;
- des modeles de classification d'images avec FashionMNIST ;
- des architectures recurrentes RNN, LSTM, GRU et Seq2Seq sur un corpus francais vers anglais.

Chaque notebook contient les etapes principales d'un projet de deep learning : import des bibliotheques, chargement des donnees, preprocessing, definition du modele, entrainement, evaluation et interpretation des resultats.

## Structure du repository

```text
.
├── .gitignore
├── README.md
├── deepLone.ipynb
├── DeepLt.ipynb
└── partie_III_RNN_LSTM_GRU_Seq2Seq_Colab_(1).ipynb
```

## Description des fichiers

### `deepLone.ipynb`

Notebook de classification sur le jeu de donnees Breast Cancer de `scikit-learn`. Il montre comment charger un dataset tabulaire, preparer les donnees, construire un modele avec PyTorch, l'entrainer et evaluer ses performances.

### `DeepLt.ipynb`

Notebook de classification d'images avec le dataset FashionMNIST. Il utilise PyTorch, `torchvision`, des transformations de donnees, des DataLoaders et des metriques d'evaluation pour entrainer et tester un modele sur 10 classes d'images de vetements.

### `partie_III_RNN_LSTM_GRU_Seq2Seq_Colab_(1).ipynb`

Notebook Colab consacre aux modeles sequentiels. Il compare les architectures RNN, LSTM, GRU et Seq2Seq sur une tache de traduction francais vers anglais, avec verification de l'environnement GPU/CPU et entrainement des modeles.

### `.gitignore`

Fichier d'exclusion Git pour eviter de versionner les checkpoints Jupyter, les environnements virtuels, les caches Python et les fichiers d'environnement.

## Technologies utilisees

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## Utilisation

1. Cloner le repository :

```bash
git clone https://github.com/MEEDamrane/deepLearning.git
cd deepLearning
```

2. Ouvrir les notebooks avec Jupyter Notebook, JupyterLab ou Google Colab.

3. Executer les cellules dans l'ordre pour reproduire les experimentations.

## Remarque

Certains notebooks peuvent telecharger automatiquement des jeux de donnees ou necessiter une connexion internet lors de leur execution. Pour les experimentations les plus lourdes, l'utilisation de Google Colab avec GPU est recommandee.
