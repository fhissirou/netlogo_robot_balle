# WorkforceWeb
---

|   Ngoc Hoan NGUYEN     &   Fodé HISSIROU           |
---


## Objectif

- Mise en place d'un système ou d'une platforme pour permettre de la mise en relation entre les clients et l'entreprise en recherche des main d'oeuvre disponibles sur le marché.

## Les prescriptions techniques 

Concevoir le site Workfoce en tenant compte des aspects

- Type des technologies: Web

- CMS: Drupal 8

- Fonctionnement: JQuery, JavaScript

- Type de programmation: PHP, Synfony 3

- Type de base de donnée : MongoDB

- Type d'analytiques : Google, Webmaster Tools

- Système de protection Anti spammer

- Référencement du site

- Accessibilité aux réseaux sociaux : Facebook, Twitter, Linkedin

- Système de paiment en ligne : PayPal, Amazon paiement , (bancaire optionnel).

- Système d'authentification : OAuth

- IDE : MySQLWorkBench, Visual Code


## Le développement de la platforme : 


### BackEnd :
------------

##### - La refonte, conception et la réalisation de la platforme web en tenant compte de la mise à jour du noyau du CMS.


##### - Trois types de compte : Admin, partenaire, utilisateur : 

		1.	Admin : Doit avoir la possibilité effectuée toute opération  et la visibilité globale sur le platforme. il  s'occupe de la gestion du web (mise a jour, sauvergades des données, sécurisation, ...) et tout types de taches liées au bon fonctionnement de la plateforme.
		2.  Partenaire sont les entreprises qui sont abonnées a laplateforme. Leurs accès aux offres devrait etre prioritaire selons leur statut abonnées, doivent avoir l'accès au offres selons leurs domaines. 
		3. Utilisateur : publie l'offre sur platforme et l'admin tranfère leur offre aux partenaires compétentes. 
		
		
##### - Mise en place d'un système de messagerie :

		1. La mission est d'envoyer des appels d'offres aux partenaires
		2. Envoi des mails de confirmation / evaluation aux clients
		3. Système de notifications et de validations : une fois offre est diffusé aux partenaires, un questionnaire satisfaisant sera envoyé aux utilisateurs, et leur réponse sera envoyé aux partenaire. en cas d'annulation d'offre, le partenaire sera notifié de cette annulation

##### - Base de donnée :	


##### - Status d'offre dans la partie du partenaire:	
	L'offre peut prendre 3 status différents qui sont gérés par différence couleur:
	- rouge -> En attente d'être accepté par un partenaire
	- jaune -> L'offre a été accepté et en attente d'être valider par le partenaire
	- vert -> fin de process du status, avec un envoi de questionnaire 

	Si jamais, l'offre a été validé par l'un de partenaire, alors les autres partenaire seront informés que l'offre n'est plus disponible.
		
##### - Partenaire :	
	- Partenaire verra la description de l'offre et le code postal sans le contact de l'utilisateur.
	- Pour accepter l'offre, le partenaire doit obligatoirement se connecter à son compter.	
	- Si le crédit est 0 alors un bouton de recharge du crédit est disponible, Le partenaire doit acheter à nouveau crédit. 	- Une fois le crédit est disponible, il pourra faire l'accceptation et le décomptage du crédit disponible fera automatique de -1 de son crédit actuel. En suite, il verra le contact du client.
	
### FontEnd :
------------
	- se référer au template : JANGO

