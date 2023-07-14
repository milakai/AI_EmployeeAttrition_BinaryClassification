
# IA Attrition Employées Classification Binaire


## Introduction

L'entreprise de produits pharmaceutiques HumanForYou basée en Inde emploie environ 4000 personnes. Cependant, chaque année elle subit un turn-over d'environ 15% de ses employés nécessitant de retrouver des profils similaires sur le marché de l'emploi.

La direction trouve que ce niveau de turn-over n'est pas bon pour l'entreprise car :

- Les projets sur lesquels étaient les employés quittant la société prennent du retard ce qui nuit à la réputation de l'entreprise auprès de ses clients et partenaires.

- Un service de ressources humaines de taille conséquente doit être conservé car il faut avoir les moyens de trouver les nouvelles recrues.

- Du temps est perdu à l'arrivée des nouveaux employés car ils doivent très souvent être formés et ont besoin de temps pour devenir pleinement opérationnels dans leur nouvel environnement.

La direction fait donc appel à nous, spécialistes de l'analyse de données, pour déterminer les facteurs ayant le plus d'influence sur ce taux de turn-over et leurs proposer des modèles afin d'avoir des pistes d'amélioration pour donner à leurs employés l'envie de rester.

## Problématique:

- Les projets sur lesquels étaient les employés quittant la société prennent du retard ce qui nuit à la réputation de l'entreprise auprès de ses clients et partenaires.

- Un service de ressources humaines de taille conséquente doit être conservé car il faut avoir les moyens de trouver les nouvelles recrues.

- Du temps est perdu à l'arrivée des nouveaux employés car ils doivent très souvent être formés et ont besoin de temps pour devenir pleinement opérationnels dans leur nouvel environnement.

## Objectif:

- Déterminer les facteurs ayant le plus d'influence sur ce taux de turn-over.
- Proposer des modèles afin d'avoir des pistes d'amélioration pour donner à leurs employés l'envie de rester.

## Données fournies:

- Données du service des ressources humaines: qui est un fichier csv contennant les informations générales des employés
- Dernière évaluation du manager: qui est un ficher csv contennant la dernière évaluation de chaque employé faite pas son manager.
- Enquête qualité de vie au travail: qui est un fichier csv contennant le retour concernant la qualité de vie au travail de chaque employé.
- Horaires de travail: qui est un fichier csv contennant les horaires d'entrée et de sortie des employés sur une période de l'année.

## Solution:

Suite aux données et informations fournies, on a mis en oeuvre une analyse du problème courant afin de trouver une solution en passant par les étapes suivantes:

### Imports python générique

Plusieurs bibliothèques ont été requise afin d'effectuer notre analyse, les plus importantes:

- OS : Afin gérer nos intéractions avec les fichiers de données.
- pandas : Afin travailler avec des dataframe.
- datetime : Si nous devons intéragir avec des dates.
- matplotlib : Afin afficher des données de manière plus graphique.
