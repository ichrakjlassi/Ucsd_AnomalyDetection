# Ucsd_AnomalyDetection

## Perentation du Projet

Détection d’anomalies dans des vidéos de surveillance piétonnière à partir du dataset.  
Le but est d’identifier automatiquement les comportements anormaux (la circulation des entité non piétonnes dans les allées(vélo,patineurs,les petits chariots), des mouvement anormaux de piétons (personnes qui traversent une allée ou marchent dans l'herbe), traversé hors zone...) dans des séquences vidéo filmées a l'aide d'une caméra stationnaire monté en hauteur surplombant les allées piétonnes.
## Objectifs métier
L’objectif métier de ce projet est d’améliorer la sécurité dans les espaces publics en détectant automatiquement des comportements anormaux dans des zones piétonnes. Cela permet d’automatiser la surveillance vidéo, de réduire la charge de travail des opérateurs humains, et de réagir plus rapidement en cas d’incident, ou de déplacements inhabituels
## Objectifs data science
Sur le plan data science, le projet vise à prétraiter les séquences vidéo du dataset UCSD, à modéliser le comportement normal à l’aide d’un autoencodeur, puis à détecter les anomalies en analysant l’erreur de reconstruction. Le tout est évalué à l’aide de métriques adaptées comme l’AUC ou l’EER, avec des visualisations pour interpréter les résultats.

## Équipe
- Ichrak JLASSI
- Mejda BEDOUI
- Nawres MNAKBI
- Mohamed Hedi MEGDICHE
- Collaboration sur GitHub

## Méthodologie

1. Téléchargement et exploration des vidéos UCSD
2. Prétraitement des frames (redimensionnement, normalisation)
3. Entraînement d’un autoencodeur sur frames normales
4. Détection d’anomalies via l’erreur de reconstruction
5. Évaluation avec des métriques adaptées
6. Visualisation et interprétation des résultats


