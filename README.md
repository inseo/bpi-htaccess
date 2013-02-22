#bpi-htaccess
Le dépôt bpi-htaccess regroupe les règles de configuration serveur détaillées dans le livre [Intégration web - les bonnes pratiques](http://www.eyrolles.com/Informatique/Livre/integration-web-les-bonnes-pratiques-9782212133707) publié aux Éditions Eyrolles.

##Règles de configuration
Les instructions proposées ici sont tirées du fichier `.htaccess` du projet [HTML5 Boilerplate](http://html5boilerplate.com) et ont été agrémentées de commentaires français.  
Toutes les règles d'origine n'ont pas été reprises en totalité. Si vous souhaitez les compléter, je vous invite à consulter le fichier initial.

##Effets
Ce fichier permet :

* d'interdire le mode de compatibilité sur Internet Explorer ;
* d'autoriser l'accès aux fichiers de fontes personnalisées depuis un domaine tiers ;
* de paramétrer les en-têtes HTTP ;
* de compresser les fichiers texte ;
* de contrôler la date d’expiration des ressources ;
* de renforcer les paramètres de sécurité ;
* d'éviter le contenu dupliqué ;
* et de permettre de personnaliser les pages d’erreurs.

##Utilisation
La mise en place du fichier `.htaccess` nécessite d'avoir les droits suffisants pour modifier les paramètres serveur.  
Dans l'optique où vous auriez accès au fichier de configuration serveur, il est conseillé d'y reporter ces insctructions directement : le fichier `.htaccess`  permet certes de surcharger les paramètres à la volée, mais en contrepartie son contenu est vérifié à chaque requête navigateur.



