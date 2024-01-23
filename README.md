# Pokemon Battle Simulator 😾
## Machine Learning Proyect to predict Pokémon battles results
(From Wikipedia) Pokémon is a Japanese media franchise managed by The Pokémon Company, a company founded by Nintendo, Game Freak, and Creatures. The franchise was created by Satoshi Tajiri in 1996,[4] and is centered on fictional creatures called "Pokémon". In Pokémon, humans, known as Pokémon Trainers, catch and train Pokémon to battle other Pokémon for sport.

In this assignment we present you a dataset with the results of several Pokémon battles.

Your objective will be to produce a ML model that can predict the outcomes of any Pokémon battle.

At first, in this notebook, you will apply some of the basic ML approaches that we have seen in class. At this point you can also work with the small versions of the dataset if you want.

Later, on the pokemon-competition.ipynb notebook, you will train a model using all the data that will be used to predict real Pokémon battles.

Dataset Description

Within the datasets.zip file that you can download from the virtual campus, you will find the following datasets:

data.train -> Full data available to train the models
data_inverse.train -> Same data as data.train but each combat is seen from the other player's perspective (i.e. pokemon1 becomes pokemon2 and viceversa)
small.train -> Subsample of data.train to allow fast prototyping
small_inverse.train -> Subsample of data_inverse.train to allow fast prototyping
data.hidden -> Dataset with no label available
data_inverse.hidden -> Same as data.hidden but the pokemons are inverted
The datasets *.hidden are the ones used to get the tournament score, so the true label is unknown. All the other datasets are available to you to use however you want.

Gotta Train 'Em All!
