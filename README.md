# Solve optimization problem with metaheuristic

## Discrete optimization : TSP problem

There are two tsp problems to solve: Djibouti and qatar. The data is from to the [math.uwarterloo.ca](http://www.math.uwaterloo.ca/tsp/world/countries.html)
* Genetic algorithm was choosen as optimization algorithm in both case. After multiples tests of parameters, the bests one closer to the optimal value are :
   - population : 1000
   - offspring : 1000
   - mutation : 0.05
   - crossover : 0.9
**Djibouti

- 38 cities 
- Optimal value is 6656
- Results 
   - fitness : 9648
   - computation time : 48 seconds
 [Code source]()
 
**Qatar

- 194 Cities
- Optimal value is 9352
- Results
   - fitness : 36443
   - computation time : 413 seconds
[Code source]()

## Continuous optimization

There are function to optimize from [CEC’2008](). [BFGS](https://transp-or.epfl.ch/courses/optimization2011/slides/09-bfgs.pdf) from Scipy was used for the first function and the lastest are analyzed with [PSO](https://nathanrooy.github.io/posts/2016-08-17/simple-particle-swarm-optimization-with-python/).

-  [Sphere function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/sphere)
-  [Schwefel function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/schwefel)
-  [Rosenbrock function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/rosenbrock)
-  [Rastrigin function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/rastrigin)
-  [Griewank function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/griewank)
-  [ackley function](https://github.com/Sohou08/Metaheuristic_optimization_exam/tree/main/ackley)



