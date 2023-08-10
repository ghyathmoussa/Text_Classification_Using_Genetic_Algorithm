# Text Classification Using Genetic Algorithm

In this project, a genetic algorithm was applied to perform text classification. Individuals containing a word list for each class were created by the algorithm, and the best individuals were selected to improve the fitness of the individuals in every generation. The effects of each hyperparameter, including the number of individuals in the population, the word list of the individual, the mutation rate, and the number of iterations, were analyzed by training the algorithm with different hyperparameter combinations. The algorithm was then tested on 5 different datasets to evaluate its performance.

## Method

The genetic algorithm was implemented with individuals containing word lists for each class. The words were selected from a word pool generated from the texts in the dataset. The algorithm improved the fitness of the individuals in each generation by selecting the best individuals as parents and breeding them. Four hyperparameters were considered: population size, word list length, mutation rate, and number of iterations (generations).

## Hyperparameter Analysis

The algorithm was trained using 27 combinations of hyperparameters, including population sizes of 20, 60, and 100; list lengths of 100, 300, and 500; mutation rates of 0.05, 0.1, and 0.2; and 100 generations. Nine graphs were created to analyze the effects of population size, word list length, and mutation rate on the fitness values.

### Population Size and Mutation Rate

<img width="1000" alt="image" src="https://github.com/muhannad125/Text_Classification_Using_Genetic_Algorithm/assets/61150919/905a99c5-2d1b-4038-bda1-ee81f67ff223">

Three graphs were generated to analyze the effect of population size and mutation rate on the fitness values. The best performance was observed with a population size of 100 and a mutation rate of 0.05, yielding a fitness value of 73%, with little difference when the population size was 60 and the mutation rate was the same (fitness value of 72%).

### Population Size and Word List Length

<img width="1000" alt="image" src="https://github.com/muhannad125/Text_Classification_Using_Genetic_Algorithm/assets/61150919/81f717eb-1994-4da2-a075-ec86a3d049a1">

Three graphs were generated to analyze the effect of population size and word list length on the fitness values. The best performance was observed with a population size of 60 and a list length of 600, yielding a fitness value of 78%.

### Word List Length and Mutation Rate

<img width="1000" alt="image" src="https://github.com/muhannad125/Text_Classification_Using_Genetic_Algorithm/assets/61150919/26a899d4-c569-4995-a1be-a3ca90f93385">

Three graphs were generated to analyze the effect of word list length and mutation rate on the fitness values. The best performance was observed with a mutation rate of 0.05 and a list length of 600, yielding a fitness value of 78%.

## Testing on Different Datasets

After determining the best hyperparameters, the algorithm was tested on five different datasets to evaluate its performance across various contexts. Also, The lists of the best individual of every dataset is included at the end of the Document

### IMDB Reviews Dataset

IMDB dataset is the dataset used primarily in this project. The hyperparameters analysis is done using this dataset. The dataset contains reviews for many movies on IMDB labeled as Negative and positive. Below is a graph of fitness across every generation.

<img width="600" alt="image" src="https://github.com/muhannad125/Text_Classification_Using_Genetic_Algorithm/assets/61150919/7fb3e304-209a-4b7a-bbae-6019e179f922">


### Fake and Real News Dataset 

This dataset contains news as labeld True and Fake. Below is a graph of fitness across every generation.

<img width="600" alt="image" src="https://github.com/muhannad125/Text_Classification_Using_Genetic_Algorithm/assets/61150919/23523155-67f5-4731-afb5-1944b2e0f72b">

### Amazon Reviews Dataset
This dataset contains reviews of different products labeled as Positive and Negative. Below is a graph of fitness across every generation.

<img width="600" alt="image" src="https://github.com/muhannad125/Text_Classification_Using_Genetic_Algorithm/assets/61150919/196e19dc-dfe2-44d7-b40e-855aba366dba">

## Contributors

Metin Usta - metin.usta01@hotmail.com

Muhannad Tuameh - muhannadtumah@gmail.com

Project Link: [https://github.com/MetinUsta/Multiple-Choice-Distractor-Generator](https://github.com/MetinUsta/Multiple-Choice-Distractor-Generator)

