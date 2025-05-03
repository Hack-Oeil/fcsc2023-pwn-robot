# FCSC 2023 Robot

La startup FunWithRobots & Co. souhaite proposer un service interactif, qui tourne sur un serveur distant et qui simule un robot avec beaucoup de réalisme. Mais la veille de l’inauguration, le chef de projet se souvient d’une vague mention concernant des exigences de sécurité…

Comme vous êtes la personne chargée de la sécurité, il a besoin de votre validation. Selon lui, cela n’est qu’une simple formalité car le code a été relu par leurs meilleurs développeurs et le binaire s’exécute avec toutes les protections classiques (canaris, W^X, ASLR, etc.).

Vérifiez s’il est possible de lire le fichier flag.txt qui se trouve sur le serveur distant.



Fichiers:
- [robot](robot)  (Application)
- [robot.c](robot.c) (Code source)



Auteur : AMI


Origine : [Robot](https://hackropole.fr/fr/challenges/pwn/fcsc2023-pwn-robot/)



-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc robot.cyrhades.fr 4000

-----------

## Ou directement avec netcat
> nc localhost 4000


-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2023-pwn-robot.git

> cd fcsc2023-pwn-robot


-----------


## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/pwn/fcsc2023-pwn-robot/