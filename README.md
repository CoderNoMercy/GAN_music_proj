# GAN_music_proj

This is a project I did from March,2018 to June,2018.

In this project, our signal form is music. We choose midi file as our training data to make sure the input and output of our neural network is digital signal. 

From midi file, we extract notes, pitch and chord to compose our training data. First train the discriminator for 10 times and then train generator for 1 time. 

Repeat this process until the output of discriminator reach Nash Equilibrium, which means the discrinimator can no longer distinguish the fake one and true one from the output of generator.

For the algorithm introduction, you can see my own website https://codernomercy.github.io/generic.html
