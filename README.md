


# The Hex'ISEN Game - Projet d'Informatique CSI3

## Cahier des Charges

 **Contexte & définition du projet**
 
 Notre équipe de 3 développeur à pour objectif de réalisé un algorithme en C, celui doit etre un algorithme mettant en œuvre la théorie des Jeux. Notre client nous demande la réalisation du Jeu "HEX".

**Objectif du projet**

Nous devons réalisé le Jeu "Hex" en C avec deux options possible : Humain contre Humain ou Humain contre machine. Nous devons réalisé une interface graphique (GUI).
Nous devons également faire une étude de faisabilité, ainsi qu'un cahier de conception.
Le programme doit etre le moins gourmant et "ressourcauvaure" possible (en termes de Temps, RAM et ROM)


**Description fonctionnelle des besoins**

Fonction principale : Jouer au jeu "HEX"

Fonction secondaire :

 - [x] Création d'une interface graphique : Le but de cette fonction, à la demande du client, est de rendre le jeu jouable intuitivement | Priorité Moyenne

 - [x] Création d'un mode de jeu "Simple" (Humain contre Humain): Permet de prendre en main facilement le jeu avant de jouer contre l'ordinateur | Priorité Haute

 - [ ] Création d'un menu (Jouer, Option, Graphisme, etc...) : Permet de choisir facilement le mode de jeu (H/H ou H/IA) et les options | Priorité Basse

 - [ ] Création d'un mode de jeu "Intelligent" (Humain contre IA) : Demander par le client, il doit utilisé un algorithme de la théorie des jeux | Priorité Haute

**Delais**

Le projet doit-être finalisé pour la soutenance du mois de Janvier. 


## Cahier de conception

**Régles du jeu**

> ***Composition :*** 1 plateau hexagonal 11x11, 13x13 ou 19x19 60 et 61 pions rouges et bleus
> 
> ***Déroulement:*** Les 2 joueurs choisissent une couleur et les pions correspondants. A tour de rôle chacun va poser un pion de sa couleur
> sur le tableau à la condition que ce dernier ne soit pas occupé . On
> ne déplace pas les pion posés !
> 
> ***Fin :*** La partie s'arrête quand un des joueurs a relié entre eux, par une chaîne continue de pions lui appartenant, les deux bords de sa couleur .


**Stratégie Gagnante adopté pour l'IA**

Utilisation de l'algorithme "MinMax" de Von Neumann
Suite [...]


**Diagramme du programme**





## Utilisation

Commande de compilation du programme :

     gcc game.c -c game && ./game


## Moyens & Logiciels utilisés

- Utilisation de DISCORD pour la communication au sein de l'équipe
- Utilisation de GitHub pour le développement en équipe et pour le versionning
- Utilisation de MS Project pour la réalisation d'un diagramme de Gantt

## Team

- Aymeric DELIENCOURT - Chef de Projet
- Antoine ROZIERE
- Aymeric GRATTEPANCHE


## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2018 © <a href="http://des69u.fr" target="_blank">DES69U</a>.
