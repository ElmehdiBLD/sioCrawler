# projet Sio crawler #

pr‚sentation du projet : le but est de r‚aliser un jeu de r“le permettant un jeu peu massivement multi joueur permettant aux ‚tudiants du bts sio de se divertir pendant les heures de cantine mais surtout d'am‚liorer leurs comp‚tences en d‚veloppement.

Les outils mis en oeuvre :

    * git,
    * Visual studio,
    * mysql,
    * apache.

Le d‚veloppement tourne autour de 3 grandes parties

    1.l'inscription en ligne
    2.d‚veloppement du jeu en lui mˆme permettant l'exploration d'un labyrinthe
    3.la sauvegarde des personnages et du contexte du jeu

|d‚veloppement 	       | langages |	technique de programmation                          |
|----------------------|:--------:|----------------------------------------------------:|
|inscription en ligne  |php, Mysql|	d‚veloppement web MVC avec Code Igniter             |
|sio crawler le jeu    |c# 	      |programmation objet, tests unitaires                 |
|sauvegarde du contexte| c#, mysql|programmation proc‚dural proc‚dures stock‚es en mysql|

## L'inscription en ligne. ##

site web permettant … un joueur de s'inscrire en ligne. le projet pr‚voit le principe suivant pour l'inscription en ligne. 

![acteurfluxinscription.png](https://github.com/ElmehdiBLD/sioCrawler/blob/master/acteurFluxInscription.PNG)
## sio crawler le jeu ##

le joueur poss‚dera les fonctionnalit‚s suivantes.
![ 	useCasePersonnage.PNG](https://github.com/ElmehdiBLD/sioCrawler/blob/master/useCasePersonnage.PNG)

les classes d‚velopp‚es.
![diagrammeClassePersonnage.PNG](https://github.com/ElmehdiBLD/sioCrawler/blob/master/diagrammeClassePersonnage.PNG)

## Sauvegarde du contexte ##

La sauvegarde du contexte se fera dans la base de donn‚es.

![ 	mcdSauvegarde.PNG](https://github.com/ElmehdiBLD/sioCrawler/blob/master/mcdSauvegarde.PNG)