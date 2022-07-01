<img src="https://www.univ-nantes.fr/medias/photo/logotype-nantes-u-noir-72dpi_1638965800927-png?ID_FICHE=1482184" alt="Nantes Université" width="200"/>
<img src=../pictures/LOGO_PRINCIPAL_IUT_NANTES_CMJN.png alt="IUT Nantes" width="200"/>

# Mini-projet de GPO2 d'année BUT1-Info 2022 : Platoon de véhicules

Le sujet d'étude est un **Platoon de véhicules**.
On imagine une entreprise ElectroIUT qui souhaitent produire des véhicules qui peuvent rouler en train en se suivant les uns les autres.
Elle réalise alors un premier projet pour créer un **prototype de platoon de véhicule**.

Nous allons traiter la première partie du projet en mettant en oeuvre l'ensemble du contenu du module de GPO2 et en produisant un cahier des charges.
Imaginons que votre trinôme est la première équipe de l'entreprise qui va faire toute l'étude et qui confiera ensuite le cahier des charges à une équipe chargée de faire un prototype (il s'agit d'un projet classique pour des étudiants de 2ème année l'an prochain).

## Cas d'étude

**Description du projet :** 
Avant d’envisager d’avoir des véhicules complétement autonomes, les industriels et chercheurs ont étudié les platoons de véhicules. 
Il s’agit de véhicules qui se suivent et qui communiquent entre eux pour s’informer mutuellement de leur position et vitesse. 
Si la voiture autonome semble obnubiler les travaux désormais, il existe encore des projets réalistes pour créer des platoons de semi-remorques formant des « trains » sur l’autoroute.

Nous étudions un projet de développement d’un logiciel de tels véhicules à partir de robots Lego. 
Le but est de faire se déplacer plusieurs robots (de 1 à 3) d'un point à un autre. 
Ces robots devront s'arrêter en cas d'obstacles (en particulier d'autres robots) et optimiser leur déplacement pour arriver à destination dans un temps raisonnable en toute sécurité. 
La télécommande du platoon sera faite par ordinateur (ce qui simule le conducteur du premier véhicule).

On considère uniquement le projet sur maquette et pas le système réel.

Voici plusieurs exemples concrets où le premier véhicule est conduit par un professionnel pendant que les autres véhicules suivent sans action des passagers :
[https://www.youtube.com/watch?v=tQnVGOoVvVk](https://www.youtube.com/watch?v=tQnVGOoVvVk)
[https://www.youtube.com/watch?v=lx9EFJ6qgZc](https://www.youtube.com/watch?v=lx9EFJ6qgZc)

Plusieurs projets d’étudiants au département ont travaillé sur un platoon de véhicule Lego. 
Nous avons aussi publié des travaux de recherche sur la vérification de leur comportement :
[https://costo.univ-nantes.fr/application/vehicle-exemple/](https://costo.univ-nantes.fr/application/vehicle-exemple/)


## Déroulement du travail.

L'étude de ce cas d'étude avec l'ensemble des techniques vues en GPO2 en produisant un cahier des charges est un travail réalisable en **24h** (à répartir entre 3 étudiants et dont la moitié sera faite pendant 3 créneaux de TD de GPO2 avec le professeur).
La date de rendu est le **jeudi 2 juin, à 19h**.

Comme vous le voyez, le travail se passe ici, sur gitlab, nous allons voir en TD comment se servir de cet outil.
En bref, votre travail sera à rendre dans gitlab, le professeur récupérera votre travail à cette date 
(même si vous faites quelque chose ensuite, il peut choisir la version qu'il évalue. 
Si vous avez vraiment besoin qu'il considère une version en retard, il faudra lui demander et il y aura des pénalités.)
Nous préférons mettre une note par trinôme, mais nous aurons accès à votre travail individuel et des disparités anormales seront prises en compte.

Vous allez utiliser les outils vues en TD 
(youtrack et les outils de uncloud.univ-nantes.fr : traitement de texte, tableur, diagramme, mindmap/WBS) 
pour faire votre étude, 
mais le rendu se fera dans un fichier du même type que celui que vous êtes en train de lire : au format markdown.
Il s'agit d'un langage basique pour mettre en forme du texte grâce à des caractères spéciaux (cela à l'avantage d'être du texte brut facilement versionnable avec git).

Dans les "files" du "repository", vous trouverez un dossier cahier_des_charges. J'y ai déposé un fichier préformé de cahier des charges, nommé *SpecificationPlatoonVehicules.md*. 
Ce sera à vous de le modifier et de le versionner dans votre propre projet gitlab une fois que vous aurez fait un fork de ce projet (pas de panique, on le fera ensemble au TD7 de GPO2).

