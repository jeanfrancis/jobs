# Exercice 1:

Il s'agit pour toi de faire une interface front à partir des données reçues avec l'url suivante :
http://kokotweb-staging.herokuapp.com/api/v1/recrutement/receipts

Explication des données reçues:
Il te faudra exploiter une matrice de dépenses telles qu'elles apparaissent dans notre base de données.
Une dépense est définie par :
- son ID unique (pour information)
- son libéllé (le titre du restaurant généralement)
- une url renvoyant à la photo
- Le total ttc, ht, et la tva
- un commentaire

1ere partie :
Il te sera demandé d'afficher sur une page ces receipts, en 3 colonnes (en format metro design, ci dessous une image en exemple)
http://metroui.com/img/DotNetBarMetroTiles.png￼

il faut que l'on voie la photo sur chaque tab, et celle ci devra être carrée
il faut un hoover quand on passe la souris par dessus la receipt, la photo est grisée et deux infos s'affichent : le libellé et le total (total en gros chiffres).

2 e partie:
Quand on clique sur la souris, une modale s'ouvre qui nous permet de voir la photo en grand, avec toutes les informations sur le coté droit de la dépense. (ci dessous un exemple de modale générée grâce à bootstrap)
http://getbootstrap.com/javascript/
(aller dans live demo, puis cliquer sur launch modal pour avoir un exemple de modale)

￼

# Exercice 2:
Objectif recruteur : Evaluer la qualité du code, l’adaptabilité du candidat sur une problématique concrète.
Durée : 48h
Objectif candidat : Développer une application AngularJS permettant d’afficher une map Google Maps, via l’api Google Maps v3.
Consignes: L’application sera composé d’une vue centrale (celle de la carte google maps), ainsi que d’une vue latérale.
Cette vue latérale devra implémenter 3 fonctionnalités.
1) Ajouter un cercle : Cette fonctionnalité, qui permettra à l’utilisateur de dessiner un ou plusieurs cercles sur la carte, sera composée :
1a) - D’un input text où l’utilisateur pourra saisir le rayon du cercle voulu.
1b) - D’un input text où l’utilisateur pourra saisir le centre géographique du cercle voulu.
1c) - D’un bouton “Dessiner le cercle”, qui dessinera le cercle sur la carte et réinitialisera les inputs précédents afin d’autoriser
la création de nouveaux cercles.
2) Ajouter un polygone : Cette fonctionnalité, qui permettra à l’utilisateur de dessiner un ou plusieurs polygones sur la carte,
sera composée:
2a) - D’un input text où l’utilisateur pourra saisir les coordonnées du polygone désiré. Les couples {latitude;longitude} devront être séparés par le symbole “+”. Les latitudes et les longitudes de chaque couple devront être séparées par le symbole “$"
Exemple:
lat1$lon1+lat2$lon2+lat3$lon3
2b) - D’un bouton “Dessiner le cercle”, qui dessinera le cercle sur la carte et réinitialisera les inputs précédents.

3) Réinitialiser la carte : Cette fonctionnalité est composé d'un unique bouton qui permettra à l'utilisateur de détruire les formes géométriques
déjà dessinées, et de vider les inputs des précédentes fonctionnalités. Un clic sur ce bouton revient donc à réinitialiser l'interface.

Unités
Le système WGS84 sera utilisé pour les coordonnées géographiques.
L’unité de distance acceptée pour la création des cercles est le kilomètre.
Note:
Une grande attention sera portée à la propreté/qualité du code, au respect des coding styles javascript,
au découpage judicieux des différentes vues angular composant l'application, à l’indentation..
Le design de l’application n’est pas nécessaire (pas de CSS requis)
Le code de l’application devra être pushé 48h après réception du mail, sur le repository git@bitbucket.org:******/google-maps-api-test.git
Bonne chance !