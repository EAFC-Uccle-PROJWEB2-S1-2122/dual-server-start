# Développer une appli React avec un backend express.js

Lorsque nous développons une application web avec React pour le client et Express.js pour le serveur, nous utilisons 2 serveurs :

* Un serveur backend Express.js qui, par défaut, reçoit les requêtes sur le port TCP 3000;
* Un serveur de développement React.js qui reçoit les requêtes sur le port TCP 3000 aussi.

Comme vu en bases des réseaux, deux serveurs ne peuvent pas écouter sur le même port TCP en même temps.
C'est donc le premier serveur démarré qui gagne.
Lorsque l'on essaye de démarrer le second, un erreur s'affiche.
