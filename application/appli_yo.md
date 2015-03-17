Une application YO: 

Création d'une application simili-YO avec Ionic, AngularJS (coder pour iOS ou Android selon votre préférence).
L'application n'est pas obligée d'être fonctionnelle : son fonctionnement peut être simulé en local. 

Les vues demandées : 
- La liste des yo envoyés. : YO envoyé à Will le 10/05/2014
- La liste des yos recus : YO reçu de Max le 11/12/2014
- Une liste de contacts, permettant d'envoyer des YOS à la personne de son choix. 
- La modale d'envoi
- La modale de confirmation

Pour recupérer les contacts et gérer les YOs, il faut passer via notre API : 
	- GET:  https://kokotweb-staging.herokuapp.com/api/v1/recrutement/users
		(pour récupérer la liste des utilisateurs)
	- POST: https://kokotweb-staging.herokuapp.com/api/v1/recrutement/yos
		(pour envoyer des Yos aux utilisateurs (il faut transmettre le [receipient_id] pour chaque yo envoyé)
	- GET: https://kokotweb-staging.herokuapp.com/api/v1/recrutement/yos
		(récupérer les Yos que j'ai reçu)

Recommandations (pour les stagiaires): 
- Utiliser un maximum les balises Ionic dans un premier temps. tu pourras faire un design plus personnalisé si tu le souhaites (couleur principale : #f0535c !)
- N'hésite pas à challenger les choix techniques et le design proposé (UX, UI) pour l'exercice, en fonction de ton expérience ou de tes préférences techniques. 
- Nous évaluons avec cet exercice les compétences front. Le minimum requis est d'avoir une application non fonctionnelle mais avec un minimum de design (au moins un design ionic homogène) et l'ensemble des vues et du routing présent.

Organisation : 
Je te mettrai à disposition un repo GIT. Tu seras jugé sur : 
	- La réalisation du projet
	- L'organisation et la clarté du code
	- L'utilisation maligne des ressources existantes.
	- La régularité des comits
	- L'originalité de l'appli rendue !



A YO Application :

Creation of a Yo-like mobile application with Ionic, Angular JS and phonegap. The app must not be functionnal, the sending of yo can be simulated in local

The app will be composed off 3 screens :
    - The list of sended Yos (example : Yo sended to will the 10/05/2014)
    - The list of received Yos (example : Yo received from max on the 11/12/2014)
    - A contact list allowing to send yo to the person you want
    - A sending modale
    - A confirm modale

You will be able to get contacts and generate Yos via the following API :
   	- GET:  https://kokotweb-staging.herokuapp.com/api/v1/recrutement/users
   		(to get the list of contacts)
   	- POST: https://kokotweb-staging.herokuapp.com/api/v1/recrutement/yos
   		(to send a Yo to a contact (you have to transmit the [receipient_id] as a parameter for each yo you send)
   	- GET: https://kokotweb-staging.herokuapp.com/api/v1/recrutement/yos
   		(to get the yo received)

Organisation:
I will provide you a git repo. The code will be evaluated on :
    - project realisation
    - organisation and clarity of the code
    - smart use of online ressources
    - commit regularity
    - the originality of the final app !

