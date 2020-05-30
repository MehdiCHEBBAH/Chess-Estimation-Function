libs : contient les bibliotheques utilsées
NN_save : contient les parametres des reseaux de neurones
user_pc : le programme original (rien n'a ete ajoutée ou modifié) + ajout de 6 fonction d'estimation (estim7, estim8, estim9, estim10, estim11, estim12)

pour la compilation il faut utiliser la commande suivante:

gcc -Wall ./user_pc.c ./libs/fann*.c ./libs/genann.c -o chess.exe -lm
