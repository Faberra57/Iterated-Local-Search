# Heat Network Optimization Project

## Overview

This project was completed during the first year of my engineering studies at IMT Atlantique. The primary goal of this project was to understand and apply optimization techniques, specifically the Iterative Local Search (ILS) method.

## Project Context

The project involved optimizing a heat network system. In this scenario, each habitation was represented as a node in the network. The objective was to determine the configuration that minimizes the deployment cost of the heat network while adhering to various constraints.

# Key Concepts

- Iterative Local Search (ILS): A metaheuristic algorithm used for solving optimization problems by iteratively improving a candidate solution.
- Heat Network: A system designed to distribute heat generated in a central location to multiple buildings or nodes.
- Constraints: Various conditions that must be satisfied during the optimization process, such as budget limits, geographical restrictions, and network connectivity requirements.

### Objectives

- Optimization: Minimize the total deployment cost of the heat network.
- Constraints Handling: Ensure that all predefined constraints are respected during the optimization process.

### Approach

- Modeling the Problem: Represent the heat network as a graph where each habitation is a node and connections between them are edges.
- Prüfer Code Representation: To enhance the efficiency of the optimization process, we used the Prüfer code representation of a graph. The Prüfer code is a sequence that uniquely encodes a labeled tree and allows for efficient manipulation and generation of spanning trees. By converting the graph into its Prüfer code representation, we optimized the execution time of various functions involved in the Iterative Local Search (ILS) algorithm. This representation reduced the computational complexity associated with tree operations, making the optimization process faster and more efficient.  
- Applying ILS: Implement the Iterative Local Search technique to iteratively improve the configuration of the heat network. The use of Prüfer code assists in efficiently exploring the solution space and managing potential solutions. 
- Evaluating Solutions: Assess each candidate solution based on deployment cost and adherence to constraints. The Prüfer code representation aids in quickly evaluating and adjusting solutions during the optimization process.

## Future Improvements

There are several areas where the project could be enhanced:

- Experiment with Different Perturbation Operators: Investigate various perturbation operators and compare their effectiveness in improving the optimization process. This could provide insights into more efficient or effective search strategies. 
- Implement Bayesian Optimization: Explore the use of Bayesian optimization techniques to fine-tune hyperparameters. This approach could improve the performance of the Iterative Local Search algorithm by systematically optimizing its parameters.
