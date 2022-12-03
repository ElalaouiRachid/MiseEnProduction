# MiseEnProduction
Afin de prendre en main l’utilisation de la plateforme Mogenius, on a testé ses fonctionnalités avec un déploiement d’une simple application. Et cela en suivant 
quelques étapes principales :
-	Créons tout d’abord une application Hello World constituée d’un fichier index.html (code source), et un fichier DockerFile (contient les commandes qu’on peut appeler
sur la ligne de commande pour assembler notre image). Et on push le code sur github.
-	Ensuite, on a créé un compte sur Mogenius pour pouvoir créer un cloudSpace en liaison avec notre compte github tout en spécifiant le port 80 pour HTTPS. 
Une fois la liaison établie, c’est Mongenius qui se charge du build de docker en exécutant les commandes spécifiées dans le fichier DockerFile.
-	Finalement, on peut lancer notre application en utilisant l’external hostname.ui
