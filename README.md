# TP_final_domaine
## Concept
### Description du projet
Le projet consiste à faire une application (companion app) pour la pêche. Il permet de garder un répertoire des poissons qu'un pêcheur a pêcher durant sa carrière et de donner des points dépandants de : la rareté du poisson, sa longueur, son poid et l'endroit que le poisson a été pêché.
Le but principal du projet est d'aider les biologistes marins dans leur travaille pour pouvoir donner des informations plus précises.

### Système de point
Les points seront donnés selont la rareté, le poids, la longueur et l'endroit que le poisson sera pris.
Les poisssons plus rares donneront plus de point que les poissons communs.
Les poissons plus longs donnes plus de point.
Les poissons plus lourds donneront plus de point.
Les poissons pris dans des zones moins pêcher donnneron aussi plus de point.
Le calcule de point est : (1 points de base) x rareté x (poids x 10) x (longueur x 10) x la zone de pise.

#### Système de rareté
- Commun : 10 points
- Rare : 20 points
- Epic : 50 points
- Légendaire : 100 points
- Secret : 200 points
  
Ex. de rareté : Perchaude = commun et Esturgeon = légendaire

#### Système de mesure du poisson
##### Poids
Le poids du poisson est calculé en livres.

Il y a une possibilité de mettre le poids en Kg pour la facilité d'ulisation. Les Kg sont simplement transformés en Lb durnat le calcul des points.
##### Longueur
La longuer est pris en cm.

Il y a une possibilité de mettre la longueur en pouce pour la facilité d'utilisation. Les pouces sont simplements transformé en cm durant le calcul des points.

##### Zone de prise
La zone de prise donne un montant de points selon la qualité de pêche.
- Zone peu pêcher = 100 points
- Zone régulièrement pêcher = 50 points
- zone fortment pêcher = 25 points
- Zone surpêcher = 10 points

Le type de zone est décidé par les recherches passées des biologistes marins de la région et par le montant d'utilisateurs qui ont attrapés des poissons dans la régions.
Les utlisateurs sont une aide pour découvrir si une zone est surpêcher, mais des sources concrètes sur la région maritime sont priorisées pour décider le type de zone.


