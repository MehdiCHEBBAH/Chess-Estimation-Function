libs : Contains the used libraries
NN_save : Contains neural network parameters
user_pc : The original program (Nothing modified) + Added 6 estimation function (estim7, estim8, estim9, estim10, estim11, estim12)

To compile you have to run the following commend:

gcc -Wall ./user_pc.c ./libs/fann*.c ./libs/genann.c -o chess.exe -lm
