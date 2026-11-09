# Estimation de la profondeur dans les champs de bleuets par apprentissage profond

## Présentation du projet

Ce projet a été réalisé dans le cadre de ma maîtrise en mathématiques et informatique appliquées à l'Université du Québec à Trois-Rivières (UQTR), au Canada.

L'objectif est d'estimer la profondeur d'une scène naturelle à partir d'une image RGB, en utilisant des techniques d'apprentissage profond.

L'application porte sur des images de champs de bleuets nains, un environnement présentant des défis particuliers en raison de la végétation, des variations d'éclairage et de la complexité des scènes.

## Technologies utilisées

- Python
- PyTorch
- GLPN (Global-Local Path Networks)
- OpenCV
- NumPy
- Google Colab

## Méthodologie

Les données proviennent d'une caméra Intel RealSense, permettant l'acquisition d'images RGB et de cartes de profondeur correspondantes.

Le projet repose sur l'adaptation d'un modèle GLPN préentraîné à des scènes agricoles naturelles.

Les principales étapes comprennent le prétraitement des images, l'augmentation des données, l'entraînement du modèle et l'évaluation des prédictions de profondeur.

## Principaux défis techniques

Les difficultés rencontrées comprennent les variations d'éclairage, la complexité de la végétation et la présence de mesures de profondeur invalides.

Le traitement des données et l'adaptation du modèle ont été des éléments importants pour répondre à ces difficultés.

## État actuel du projet

Le projet est en cours de préparation pour améliorer sa reproductibilité. Les notebooks d'entraînement et d'évaluation font l'objet d'une vérification, et les résultats expérimentaux définitifs n'ont pas encore été reproduits indépendamment à partir des fichiers disponibles.

## Auteur

Ibrahima Diouf

Maîtrise en mathématiques et informatique appliquées — UQTR.
