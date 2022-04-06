# [CAPTURE THE FLAG] À quelle capitale européenne appartiennent ces données ?
*Équipe B3 Big Data - HCA, KBE, LLE, MBA*

## Contexte
Dans le cadres de notre cours sur la Data Visualisation, le formateur nous mets au défi de retrouver la capitale a qui appartient les données présentées.

## Ressources
### 1 - Dataset
Nous avons un dataset nommé "Capitale.xslx" avec deux feuilles
* "SI" : feuille avec les données propres
* "SI -erreurs" : feuille contenant des données propres ainsi que des erreurs
### 2 - Sites météorologiques
Pour pouvoir retrouver la capitale à partir de nos résultats, nous avons à disposition deux sites qui affichent graphiquement les données météorologiques :
* [Dataset Kaggle de SKR sur les données journalières des températures de capitales](https://www.kaggle.com/sudalairajkumar/daily-temperature-of-major-cities)
* [Site de climate-data](https://fr.climate-data.org/europe/)

## Workflow
Le workflow mise en place est le suivant :  
Nettoyage (KBE/MBA) >> Statistiques / Agrégation (LLE) >> Visualisation (HCA) >> Retrouver la capitale (équipe)  
"Nettoyage" et ["Statistiques / Agrégation", "Visualisation"]] font l'objets d'un notebook chacun

## Outils utilisés
Colab pour les notebook  
Librairies Python :
* pandas 1.3.5
* matplotlib 3.2.2
