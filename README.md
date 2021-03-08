# Solve optimization problem with metaheuristic

## Discrete optimization : TSP problem

There are two tsp problems to solve: Djibouti and qatar. The data is from to the [math.uwarterloo.ca](http://www.math.uwaterloo.ca/tsp/world/countries.html)
* Genetic algorithm was choosen as optimization algorithm in both case. After multiples tests of parameters, the bests one closer to the optimal value are :
   - Population : 1000
   - Offspring : 1000
   - Mutation : 0.05
   - Crossover : 0.9
   
**__Djibouti__**

- 38 cities 
- Optimal value is 6656
- Results 
   - Fitness : 9648
   - Computation time : 48 seconds
  
 [Code source](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/djibouti)
 
**__Qatar__**

- 194 Cities
- Optimal value is 9352
- Results
   - Fitness : 36443
   - Computational time : 413 seconds

[Code source](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/qatar)

## Continuous optimization

There are function to optimize from [CEC’2008](). [BFGS](https://transp-or.epfl.ch/courses/optimization2011/slides/09-bfgs.pdf) from Scipy was used for the first function and the lastest are analyzed with [PSO](https://nathanrooy.github.io/posts/2016-08-17/simple-particle-swarm-optimization-with-python/). Each function is evaluated respectively with 50 and 500 dimensions. The detailed information of each function is described [here](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/additional_information).

*  [Sphere function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/sphere)
*  [Schwefel function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/schwefel)
*  [Rosenbrock function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/rosenbrock)
*  [Rastrigin function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/rastrigin)
*  [Griewank function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/griewank)
*  [ackley function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/ackley)



