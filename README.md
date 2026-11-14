# Deep Learning — SUPAERO SDD

Notebooks académiques consacrés aux réseaux de neurones convolutifs et à la classification d’images avec PyTorch.

## Par où commencer ?

Ouvrir [le notebook pratique](vision/1_hands_on.ipynb). Le jeu de données utilisé dans le code porte sur les classes **Clear / Cloudy** d’images satellitaires, même si certains titres hérités du cours mentionnent encore la classification d’avions.

Le notebook couvre l’exploration des données, la séparation entraînement/validation, la normalisation, un dataset PyTorch personnalisé, la construction d’un CNN, l’entraînement et l’évaluation. La sélection du matériel prend en charge CUDA, Apple MPS et le CPU.

## Contenu du dépôt

- `vision/1_hands_on.ipynb` : déroulement de la classification.
- `vision/0_cnns.ipynb` et `0_cnns.ipynb` : notebooks d’introduction aux CNN.

## Exécution

Utiliser un environnement Python pour notebooks avec NumPy, PyTorch, torchvision, Pillow, OpenCV, matplotlib et torchinfo. Le notebook inclut une cellule d’installation de torchinfo et télécharge le jeu de classification nuageuse depuis une URL Google Cloud Storage. Un accès réseau est nécessaire ; l’accélération GPU est facultative. Exécuter les cellules dans l’ordre et vérifier les chemins de chargement des données pour l’environnement utilisé.

Le dépôt ne fournit ni environnement aux versions verrouillées ni contrôle automatisé de l’exécution. Les sorties historiques ne garantissent pas la reproductibilité dans un nouvel environnement.

## Attribution académique

Le notebook pratique cite **Florient Chouteau** et le [cours de deep learning SUPAERO Data Science](https://supaerodatascience.github.io/deep-learning/), avec une mention **CC BY-NC-SA 4.0**. Ce dépôt contient des travaux de cours fondés sur ces supports ; le matériel pédagogique et les exercices d’origine ne sont pas présentés comme des créations originales de ce compte. Conserver les mentions lors de toute réutilisation.

## État du projet

Instantané de travaux de cours. Les notebooks constituent les livrables principaux ; ce README ne revendique aucun benchmark reproduit indépendamment.
