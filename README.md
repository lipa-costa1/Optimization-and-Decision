# README.md

### Description
The report should formulate the problem to be solved, explain
the methods used, and compare the results obtained using proper metrics. 

The chosen problem was the famous Traveling Salesman Problem (TSP).

Given a set of n cities and the distances between each pair of them, the traveling salesman
problem, or TSP for short, consists of finding a roundtrip of minimal length visiting each city
exactly once.
The following site (TSPLIB) contains TSP, ATSP, SOP and CVRP: (http://comopt.ifi.uniheidelberg.de/software/TSPLIB95/). 
Two benchmarks of TSP problems were chosen from the
database, one with about 100 nodes and another with at least 200 nodes.

The problems were solved using Genetic Algorithm, Ant Colony Optimization and Nearest Neighbors and the results compared. 

Final Grade: 18/20

### Data

The data sets used were ch130.tsp and tsp225.tsp. Since no changes were made on the data sets both the interim and processed folders contain both of this data sets. Contains not only the previous data sets mentioned but also others that contain the results of the tuning of the parameters for the genetic algorithm.

### Thesis
Contains the thesis made in LateX, where all the results, comments and figures appear. 
### Notebooks
Contains several different notebooks and fucntions, related to different algorithms used:
- 1.0-FilipaCosta-Genetic-Algorithm.ipynb
- 2.0-FilipaCosta-GA-DataAnalysis.ipynb
Both of these are related to the genetic algorithm.  1.0-FilipaCosta-Genetic-Algorithm.ipynb has the code for the algorithm (with a small analysis of the results) and 2.0-FilipaCosta-GA-DataAnalysis.ipynb has all the comments, graphics and results. All of this is better explained in the notebooks.
- 3.0-CatarinaRodrigues-NN.ipynb.ipynb

This is related to the nearest neighbour algorithm. It has the results, graphics and comments.

- 4.0gr-antcolonyoptimizer.ipynb
- AntColonyOptimizer.py

This is related to the ant colony optimizer algorithm. 4.0gr-antcolonyoptimizer.ipynb has the results, comments and graphics. The AntColonyOptimizer.py is the implemented function. It is included in this folder to be less confusing.

### How to make them work

For the 1.0-FilipaCosta-Genetic-Algorithm.ipynb, 2.0-FilipaCosta-GA-DataAnalysis.ipynb and 3.0-CatarinaRodrigues-NN.ipynb.ipynb all that's needed is to put the data sets, ch130 and tsp225, in the same folder as these notebooks and run them. For the 4.0gr-antcolonyoptimizer.ipynb both the data sets and the AntColonyOptimizer.py need to be in the folder for it to run.
