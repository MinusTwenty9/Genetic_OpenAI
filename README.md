# Genetic OpenAI

This is a genetic algorithm that tries to optimize the weights of a simple neural network. The network chooses the action to  
take based on the environment state. A population of randomly initialized agents is introduced and tested. A percentage of 
the agents with the top fitness score is selected to be the parents of the next generation. The children are crossovers 
of the parent networks - here called mutated - and randomly changed parent networks - here called randomized.
