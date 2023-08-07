# Application pour la soutenance de Master 2
## LIBELLE DU THEME:
Application web de gestion de stock
## PROBLEMATIQUE:
Comment concevoir et développer une application web de gestion de stock efficace et conviviale, capable de suivre en temps réel les entrées et sorties de stock, de fournir des alertes de réapprovisionnement, tout en optimisant les niveaux de stock pour minimiser les coûts et maximiser la disponibilité des produits ?
## Cahier de charge
On souhaite développer une application de gestion de stock pour répondre aux besoins de nos clients. Cette application permet de :
- Créer des profils pour chaque entreprise
- Une Entreprise a un ou plusieurs utilisateurs
- Paramétrer les catégories d'articles (produit)
- Une Entreprise a un ou plusieurs articles (produit)
- Une entreprise a un ou plusieurs Client, Fournisseurs,
- Passer des commandes clients
    •	Une commande client a un seul client
    •	Une commande client a un ou plusieurs articles (produits)
    •	Une commande client effectue une sortie de stock pour les articles en question
- Passer des commandes fournisseurs
    •	Une commande fournisseurs à un seul fournisseur
    •	Une commande fournisseurs à un ou fournisseurs articles (produits)
    •	Une commande fournisseurs effectue une entrée de stock pour les articles en question
- Effectuer des ventes au magasin
    •	Une vente a un ou plusieurs articles (produit)
    •	Une vente effectue une sortie de stock pout les articles en question
- Consulter l'état du stock de chaque article
    •	Voir la quantité de stock de l’article en temps réel
    •	Effectuer des corrections de stock (mettre à jour le stock)
## OBJECTIFS SPECIFIQUES:
L’application devra etre capable :
    •	Concevoir et developper une application web (Gestion de stock)
    •	Developper le backend (Spring)
    •	Developper le Front avec Angular (la version 10 ou recente)
Dockeriser l'application (l'environnement)
    •	Conteneur pour la BDD
    •	Conteneur Pour l'application backend
    •	Conteneur Pour l'application frontend	
AWS 
	  •	Cloud
	  •	AWS console management
	  •	Terraform pour IaC (Insfrastructure as Code)
Environnement de travail
	  •	JAVA 8 min ou 11 recommende
	  •	IDE (Eclipse)
    •	MySql (Xamp ou Wamp)
Plan de travail
  - backend
	  •	Conception (UML: Diagramme de classes)
	  •	Creer un projet Spring boot
	  •	Configurer le projet
	  •	creer les entites (models), les services, ...
	  •	Configuerer Swagger (API documentation)
	  •	Generer le Swagger.json => Generer les services, model pour l'application front
	  •	MySql (Xamp ou Wamp)
- backend
    •	Ceer et exliquer le projet Angular
    •	decouper l'applicationen components
    •	creer les components
    •	creer les services
  	•	developper les interfaces (Les ecrans)
- DevOps
	- Creer des image Docker (BDD,Backend[API],Frontend)
	- faire fonctionner l'application en dehors des IDE
