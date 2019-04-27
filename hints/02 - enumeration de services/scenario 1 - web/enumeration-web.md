Parmi les nombreux points de vulnérabilités, le web se pose comme un point sur lequel il faut porter un très grand intérêt. En effet les langages web sont aujourd'hui très puissants et peuvent servir pour exécuter tout un panel de commandes système. Ces dernières peuvent permettre l'exécution de code arbitraire en vue de (liste non exhaustive):

* voler des données
* saboter des éléments sur le serveur
* latéraliser une attaque
...

Avant de chercher des vulnérabilités sur les applicatifs du serveur, le plus simple est d'en chercher une sur les applications exposées au travers des différents services (les sites/applications web notamment). Pour cela, il s'avère essentiel d'effectuer une bonne énumération sur le contenu disponible.

Un très grand nombre d'outils d'énumérations existent, la plupart sont même open-source. Parmi ces derniers, les outils "dirb" et "dirbuster" permettent de rapidement parcourir tout le contenu accessible sur le web afin de lister des erreurs de sécurisation. Le but va être notamment de récupérer d'éventuels dossiers d'intérêt qui ne devraient pas être librement accessibles.

Une fois des éléments significatifs trouvés, il sera possible de s'orienter vers des vulnérabilités connues, comme celles concernant les CMS (wordpress / joomla / drupal...) ou encore des composants serveurs bien connus et disposant de nombreuses vulnérabilités (struts, tomcat...)  

**NB:** Le but de cette étape n'est pas forcément d'exploiter directement une vulnérabilité mais bien d'identifier de potentiels vecteurs d'attaque