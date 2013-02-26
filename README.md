# Aerie's Guard V8.0

Ceci est le *repository* pour les sources de montage HTML du site Aerie's Guard V8.

Les sources utilisent JADE pour la partie HTML et LESS pour la partie CSS, il faut donc compiler le projet avant de pouvoir obtenir des pages HTML classiques.

## Installation
### Pré-requis
La première des choses à faire est d'installer [NodeJS](http://nodejs.org/) si vous ne l'avez pas déjà.

Le projet utilise [Grunt](http://gruntjs.com) pour se compiler, vous devez donc installer la partie client (Grunt-Cli) sur votre poste afin de pouvoir lancer la commande de *build*.

Pour cela ouvrez une invite de commande en mode administrateur (ou SUDO sous Linux) et lancez la commande `npm install -g grunt-cli`

### Compiler une version
Récupérez les sources sur votre disque puis ouvrez une invite de commande et positionnez-vous sur le répertoire racine du projet.

Lancez la commande `npm install` pour installer les dépendances du projet.

Une fois l'installation des dépendances faite, lancez la commande `grunt.cmd` (ou juste `grunt` sous Linux) pour exécuter la compilation qui produira le résultat dans le répertoire `public`.
