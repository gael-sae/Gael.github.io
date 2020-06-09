# GPR440.2 Purge the Curse

## Projet
Le jeu a �t� fait dans le module GPR4400.2 en premi�re ann�e � l'SAE concernant L'Inteligence Artificiel (IA) et la g�n�ration proc�durale.
Il doit contenir une carte g�n�r� proc�duralement et une IA d�t�rmin� par le biais d'un pathfinding et doit interagire avec son environnement.

## Introduction

Purge the Curse est un rogue-like, vue en 3/4 o� l'on doit tuer tous les monstres et s'�chapper de la carte pour conjurer le mal�fice.
Le joueur au d�but de chaque partie devient un monstre al�atoire en temps que avatar jouable dans une liste de monstre. Si il meure une premi�re fois,
il aura un temps limit� sous un �tat fantomatique pour contr�ler un monstre proche de son choix pour une seconde et derni�re chance.

## Processus de d�veloppement

Mon col�gue a fait une g�n�ration de carte via un spawn de pr�fab qui se repousse pour g�n�rer la carte du jeu de fa�on al�atoire.
Dans ces pr�fab j'ai mis les waypoints manuellement et sont li� par une liste propre � chaques waypoints inscrit aussi manuellement.

![](https://github.com/gael-sae/Gael.github.io/blob/master/Image/Room7.png)
![](https://github.com/gael-sae/Gael.github.io/blob/master/Image/Room11.png)

Concernant l'AI avec le A* j'ai fait un premier jet fonctionnel mais pas op�rationnel j'ai du me faire aider par mon col�gue pour terminer,
correctement la d�tection de la cible, waypoint ou joueur, tout en passant sur les waypoints pour arriver � la cible.
J'ai plac� par la suite un menu principal avec boutons et sons o� le joueur peut lancer le jeu.


## Conclusion
L'argorithme A* et l'IA peut �tre compl�xifi� gr�ce a des states machines plus ou moins d�velopp�.
La g�n�ration proc�durale peut �tre faite de multiple fa�on suivant le domaine qu'on choisi et le style de jeu.
