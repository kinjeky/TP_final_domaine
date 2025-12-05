# TP_final_domaine
## Concept
### Description du projet
Le projet consiste à faire une application (companion app) pour la pêche. Il permet de garder un répertoire des poissons qu'un pêcheur a pêcher durant sa carrière et de donner des points dépandants de : la rareté du poisson, sa longueur, son poid et l'endroit que le poisson a été pêché.
Le but principal du projet est d'aider les biologistes marins dans leur travaille pour pouvoir donner des informations plus précises.

### Type d'utilisateur
Lors de la création d'un compte, l'utilisateur peut decider si son compte est public ou privé.

Un compte public laisse voir toutes les informations qui ne sont pas confidentiels de l'utilisateur. Ces informations sont : le classement de la personne, la salle de trophé de la personne, les endroits où il a attrapés ses poissons et les leures qu'il a utilisés.

Un compte privé cache toutes les informations d'un utilisateur. L'utilisateur avec un compte privée peut rendre les informations de son choix public.

Il est possible de changer un compte public à un compte privé ainsi que de changer un compte privé à un compte public sans frais.

Les informations du compte privé ne sont pas montré au public, mais il est donné au biologistes marins pour pouvoir aider dans leur recherches. Les informations ne sont pas divulgable au public et reste privé.

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

### Système de classement
Le système de classement utlise les points de l'utilisateur pour le placer dans le classement de son choix.

Le système de classement sera divisé en trois catégories : Mondiale, regionale et local. L'utilisateur a la possibilité de choisir le classement auquel il veut participer. Si l'utilisateur ne participe pas à un classement, so score ne contribut pas à ce classement. L'utilisateur peut quand même voir le classement régional et mondiale même s'il n'y participe 
pas. 

L'utilisateur peut choisir de faire un classment local personalisé avec d'autres utilisateurs en faisant un classment local. Il peut ajouter d'autres utilisateurs grâce à un système d`"ami" ou par un lien personalisé qui sera créé lorsque demandé. Le classement local peut être public ou privé selon le choix de la personne qui a fait le classent local.

### Système de trophé
Dans la salle de trophé, l'utilisateur peut choisir 3 poissons qu'il veut montrer sur son compte. 
Il y aura un bouton qui peut choisir automatiquement les trois poissons qui comptent pour le plus de point.
Il est possible de classer les poissond d'un ordre croissant ou décroissant pour aidé l'utilisateur.
Il est possible classé les poissons selons les régions qu'ils ont été pêcher.

### Comment mettre les poissons dans le système



