# AI-Genetic-Algorithm <br><br>

## Project Overview <br>
This project is centered around using a genetic algorithm to optimize a solution to a range of problems including, sudoku, matching rows, matching columns, checkered board. Genetic algorithms are a type of evolutionary algorithm inspired by the process of natural selection, used to generate high-quality solutions for optimization and search problems.

Representation
Checkerboard Grid: The board can be setup of different sizes.

## Genetic Algorithm Parameters
Fitness Function: The fitness function labeled "Checker" is used to evaluate the quality or fitness of each individual solution (checkerboard configuration) in the population. The exact details of this function would depend on the specific problem you're solving but typically involve assessing how close the current solution is to the optimal solution.

### Population Size: <br>
This parameter determines the number of individual solutions (checkerboards) in each generation of the genetic algorithm. A larger population size can improve the algorithm's ability to explore the solution space but may also increase computation time.

### Percentage of Individuals Mutated: <br>
Mutation introduces random changes to some individuals in the population, helping to maintain genetic diversity and allowing the algorithm to explore new areas of the solution space.

### Percentage of Random Genes Inserted: <br>
This parameter controls how many genes (cells in the checkerboard) are randomly altered in each generation, promoting variability in the population.

### Percentage of Elite Genes that Survive: <br>
Elite genes refer to the best-performing solutions in the current population. By ensuring a certain percentage of these solutions survive to the next generation, the algorithm retains high-quality solutions and builds upon them.

## Genetic Algorithm Process

Evaluation: Use the fitness function to evaluate each individual in the population, assigning a fitness value based on how well it solves the problem. <br>

Selection: Select individuals for reproduction based on their fitness values. Higher fitness individuals have a higher chance of being selected. <br>

Crossover: Combine pairs of individuals to produce offspring. This process mimics biological reproduction and allows for the mixing of genes from two parents. <br>

Mutation: Apply random changes to some of the offspring to introduce genetic diversity. <br>

Replacement: Form a new population by selecting the best individuals from the current population and the offspring, ensuring a mix of elite individuals and new solutions. <br>

Iteration: Repeat the evaluation, selection, crossover, mutation, and replacement steps for a set number of generations or until a satisfactory solution is found. <br>

## Fitness Over Time
The graph on the right side shows the progress of the genetic algorithm over 900 generations. It tracks: <br>

Max Fitness (Blue Line): The fitness of the best individual in each generation. This line typically increases over time as the algorithm finds better solutions. <br>

Avg Fitness (Purple Line): The average fitness of the population in each generation. This line gives an overall sense of how the population is evolving. <br>

Min Fitness (Green Line): The fitness of the worst individual in each generation. This line remains relatively flat, indicating that the least fit individuals do not improve much, but they still play a role in maintaining genetic diversity. <br>

## Conclusion
This project demonstrates the application of a genetic algorithm to optimize a checkerboard problem. The visual representation of the fitness values over generations shows the algorithm's effectiveness in finding increasingly better solutions. The parameters you have set allow for a balance between exploration (random genes and mutation) and exploitation (elite survival), which is crucial for the success of a genetic algorithm.

<img width="1245" alt="image" src="https://github.com/BilalNaseer7773/AI-Genetic-Algorithm/assets/90666694/38be9018-2973-4c39-a17d-0427fb4f43f3"> <br> <br>


<img width="122" alt="image" src="https://github.com/BilalNaseer7773/AI-Genetic-Algorithm/assets/90666694/4c3fa043-f3aa-4c57-a566-2be3f9519817">

