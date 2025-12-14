# TP_final_domaine
## Concept
### Description du projet
Le projet consiste à faire une application (companion app) pour la pêche. Il permet de garder un répertoire des poissons qu'un pêcheur a pêcher durant sa carrière et de donner des points dépandants de : la rareté du poisson, sa longueur, son poid et l'endroit que le poisson a été pêché.
Le but principal du projet est d'aider les biologistes marins dans leur travaille pour pouvoir donner des informations plus précises.

### Les parties de l'application

#### L'orientation de l'application
L'application est dans l'orientation "portrait" par défaut.

#### L'écran de départ
Simplement l'écran que l'utilisateur voit quand il ouvre l'application sur son téléphone.
#### Écran princial
C'est l'écran que l'utilisateur utilise comme point de départ pour naviguer les différentes sections de l'application. L'écran principal est la photo du plus grand poisson que l'utilisateur a attrapé. Il peut aussi être changer à la carte d'une région au choix (ex. une carte simplple de la rivère de milles iles).
#### Bouton "home"
Le bouton "home" se situe toujours au coin en bas à gauche de l'écrant et permet de revenir à l'écran de départ.
#### Bouton ""ajouté poisson"
Le bouton "ajouté poisson" est utlisé pour ajouter un poisson dans le système.
#### Bouton "salle des trophées"
Le bouton "salle des trophées" permet d'accéder à la salle des trophées.
#### Bouton "paramètre"
Le bouton "paramètre" permet de changer les paramètre de l'application. Il est possible de changer la langue, si l'applicaition peut utiliser la localisation de l'utilisateur, changer le type de d'utilisateur (privé ou public), connecter d'autres type de connection (email, google gmail, yahoo etc.) et la possiblité de voir les nouvelles mises à jour.
#### Bouton "classement"
Le bouton "classement" permet d'accéder aux types de classement. Il y a un classement mondiale, régional ou local.
#### Bouton "social"
Le bouton "social" permet d'ajouter d'autre utilisateurs comme "ami". Il contient aussi une option de clavardage pour se parler entre pêcheur dans la section social.
#### Bouton "carte"
Le bouton carte permet de voir une carte de la région où l'utilisateur se situe. Si l'utilisateur n'a pas activer la fonction de localisation, il faut alors que l'utilisateur met sa location manuellement.

### Type d'utilisateur
Lors de la création d'un compte, l'utilisateur peut decider si son compte est public ou privé.

Un compte public laisse voir toutes les informations qui ne sont pas confidentiels de l'utilisateur. Ces informations sont : le classement de la personne, la salle de trophé de la personne, les endroits où il a attrapés ses poissons et les leures qu'il a utilisés.

Un compte privé cache toutes les informations d'un utilisateur. L'utilisateur avec un compte privée peut rendre les informations de son choix public.

Il est possible de changer un compte public à un compte privé ainsi que de changer un compte privé à un compte public sans frais.

Les informations du compte privé ne sont pas montré au public, mais il est donné au biologistes marins pour pouvoir aider dans leur recherches. Les informations restent privées et ne sont pas divulguées au public.

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

Le système de classement sera divisé en trois catégories : Mondiale, regionale et local. L'utilisateur a la possibilité de choisir le classement auquel il veut participer. Si l'utilisateur ne participe pas à un classement, son score ne contribut pas à ce classement. L'utilisateur peut quand même voir le classement régional et mondiale même s'il n'y participe 
pas. 

L'utilisateur peut choisir de faire un classment local personalisé avec d'autres utilisateurs en faisant un classment local. Il peut ajouter d'autres utilisateurs grâce à un système d`"ami" ou par un lien personalisé qui sera créé lorsque demandé. Le classement local peut être public ou privé selon le choix de la personne qui a fait le classent local.

### Système de trophé
Dans la salle de trophé, l'utilisateur peut choisir 3 poissons qu'il veut montrer sur son compte.

La salle de trophé peut être vu par tout les utilisateurs si la salle de trophé est publique. Si la salle de trophé est mis 
a "privé", la salle de trophé est alors seulement visible aux amis de l'utilisateur. Il est aussi possible de rendre la salle de trophé "caché" pour que personne à part l'utilisateur puisse voir sa salle de trophé.

Il y aura un bouton qui peut choisir automatiquement les trois poissons qui comptent pour le plus de point.

Il est possible de classer les poissons d'un ordre croissant ou décroissant pour aidé l'utilisateur.

Il est possible classé les poissons selons les régions qu'ils ont été pêcher.

Lorsque l'utilisateur clique sur l'un de ses poissons dans la salle de trophé, il y aura une petite description sur l'espèce du poisson (description courte sur l'espèce et information pour savoir si le poissone est invasif ou est natif de la région) et tout les détails que l'utilisateur a mis lorsqu'il ajoute un poisson dans le systèmes.

### Comment mettre les poissons dans le système
Pour ajouter un poisson dans le système, il faut prendre une photo de profil du poisson dans la section "ajouter poisson" et entrée son espèce, son poids, sa longueurm, l'heure de prisse et la zone de prise et le matériel qui a été utlilser pour l'attraper (canne à pêche, moulinet, ligne de pêche et leurres).

La zone de prise peut être soit entrée d'une façon manuel avec le nom du lac ou de la rivière où le pêcheur est situé. Si le  nom est indisponible il est alors possible d'utiliser le système automatique qui utilise la localisation GPS du téléphone.

Le poisson est alors mis dans la collection de l'utilisateur.

Les photos sont utilisées pour pouvoir avoir plus d'information sur les poissons lors des recherches des biologistes marin. 

### Système "social" ou d'ami
Il permet d'ajouter d'autre utilisateurs comme "ami". Cette fonction permet d'avoir des classements privée juste entre ami. 

Il y a aussi une fontion de clavardage pour pouvoir clavarder avec d'autres utilisateurs. Les utilisateurs publiques peuvent recevoirs des messages de tout les utilisateurs. Pour clavarder avec un utilisateur privé, il faut d'abord devenir ami avec l'utilisateur privé.

### Carte
La carte permet de de voir une carte de la localisation de l'utilisateur. Il est possible d'activer la fonction de voir la carte d'une façon détailler (3D) ou de voir la carte d'une façon simplifier (cette fonction permet de voir la carte sans internet et peut être télécharger sur l'application). 

La carte a une fonction d'épingle qui permet de voir l'endroit exacte où un poisson a été attrapé par l'utilisateur. Les épingles peuvent être publique ou privé. Les épingles publiques peuvent être vu par tout les utilisateur sur la carte publique. Les épingles privées sont seulement visible par l'utilisateur qui l'a créé. Les épingles peuvent aussi êtres créés pour prendre en note des région de pêche que l'utilisateur voudrait retourner. Il est possible de mettre une description de 100 mots sur l'épingle. 

#### Règlementation de la région
La carte permet aussi de voir la réglementation de la région où l'utilisateur se situe. Cela inclu la type d'appât légal, le type d'ammeçon légal, quel poisson est légal de garder, le nombre de poisson qui peut être garder, la taille minimum et la taille macimum pour pouvoir garder le poisson.  

#### Fonction météo
La fonction météo permet, lorsque connecté à internet, de voir la météo de la région où l'utlisateur se trouve et les types de leurres qui sont le plus propice à ce genre de climat.


