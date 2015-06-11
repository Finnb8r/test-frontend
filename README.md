# Test technique frontend AngularJS

## Objectif :

Créer une application qui permet de lire une track depuis Deezer

## Détails :

### Server HTTP

* Installer le module http-server: ```npm install http-server -g```
* Démarrer le serveur de l'application avec la commande "http-server ./app"

### Dépendances

* Loader le [SDK de Deezer](https://developers.deezer.com/sdk/javascript)
* Loader la dernière version de Angular (le mieux est d'utiliser [bower](http://bower.io/))

### Application

* Créer une [application Deezer](https://developers.deezer.com/myapps)
* Initializer le player Deezer
* Ajouter un champ texte "ID de la track Deezer"
* Lorsque le champ n'est pas vide, afficher un bouton play
* Lorsque l'on clique sur le bouton play, la chanson doit commencer à se jouer (clic à nouveau, mettre en pause)
* Subscriber aux évènements du player Facebook et afficher/updater les informations de la track et du player : album, artist, title, duration, position

### Bonus

* Utiliser le framework frontend [foundation](http://foundation.zurb.com/)
* Permettre d'ajouter des tracks au player pour créer une playlist (voir la section DZ.player.addToQueue )
* Permettre de seeker dans une track (voir la section DZ.player.seek dans la [documentation](https://developers.deezer.com/sdk/javascript/controls))

## Contraintes :

* Faire attention au nommage des functions, variables, dossiers et fichiers
* Ne pas ajouter de code Javascript dans le fichier HTML
* Commenter le code à bon escient
* Pusher le code sur Github sur un repository dédié
