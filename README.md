# Jeu_de_la_vie-UTC503
Application qui possède des regles de vie ou de mort:

        - Si 0 ou 1 cellule voisine  en vie = mort par isolement
        - Si 4 a 8 cellules voisines en vie = mort par surpopulation

Il existe 2 files .py :

        - JeuDeLaVie.py:
            C'est la class main qui permet de commencer le jeu
        - grille.py :
            C'est la class creant le cadre du jeu et toutes les fonctions principales permettant le bon déroulement 

Les principales fonctions  de grilles.py:

        -activationEvenenment
                activer les evenements des fonctions
        -initialisation
                initialisation des variables utilisées
        -getGrille
                retourner la grille creer
        -creerGrille
                creation de la grille
        -coords_lig_col
                donner les coordonées des lignes et colonnes lors du survol de la souris sur la grille
        -creerCellule
                creation des cellules de vie
        -supprimercellule
                supprimer une cellule (par right click)
        -cell_voisine
                scanner toutes les cellules voisines d'une cellule en vie
        -vie-ou_mort
                decision de la vie ou mort de la cellule
        -change_vit
                changer la vitesse d'evolution du jeu
        -souris_survol
                Afficher les coordonnées ligne/colonne de la souris lors de son survol au-dessus de la grille 
        -start
                creation des cellules si aucune cellule n'a été creer par intervention humaine
        -stop
                stoper le jeu
        -go
                demarrage du jeu après l'avoir stopper
        -restart
                redemarrer le jeu de nouveau 
        -generations
                fonctionner permettant le déroulement continu du jeu
                scan les cellule voisine et decide si la cellule dit mourir ou non 
                etc
