
# Traveling Salesman Problem Optimization (CS348 Project)
![GA vs SA Comparison](GA_vs_SA_Comparison.png)

by:
Instructor: Dr. Ali Mostafa  
Mohaya Almutairi 431107802 
Fares Alsuhaibani 431107834 
Abdullah Alfayez 431108148 

This project applies two metaheuristic optimization techniques — **Genetic Algorithm (GA)** and **Simulated Annealing (SA)** — to solve the **Traveling Salesman Problem (TSP)**. It compares both methods based on performance, convergence, and solution quality.

##  Project Description

The Traveling Salesman Problem (TSP) asks:  
*"What is the shortest route that visits each city exactly once and returns to the starting city?"*

In this project:
- 10 cities are randomly generated in a 2D plane.
- Each algorithm attempts to find the optimal route.
- A visual comparison of performance is included.

##  Algorithms Implemented

-  **Genetic Algorithm**
  - Population-based
  - Uses crossover and mutation
  - Evolves over generations

-  **Simulated Annealing**
  - Single-solution-based
  - Uses probabilistic acceptance of worse solutions
  - Gradually cools temperature to refine search

##  Results

| Metric             | Genetic Algorithm        | Simulated Annealing         |
|--------------------|--------------------------|------------------------------|
| Best Distance      | ≈ 269.59                 | **≈ 269.38**               |
| Speed              | Steady improvement       | Rapid early improvement      |
| Nature             | Population-based         | Temperature-based jumping    |

##  Project Structure

```
 TSP_Optimization
├── TSP_GA_vs_SA_Notebook.ipynb
├── TSP_GA_vs_SA_Report.pdf
├── GA_vs_SA_Comparison.png
└── README.txt
```

## Tools Used

- Python 3.x
- NumPy
- Matplotlib
- Jupyter Notebook

## How to Run

```bash
pip install numpy matplotlib
jupyter notebook TSP_GA_vs_SA_Notebook.ipynb
```

##  License & Academic Integrity

This project was created for educational purposes as part of CS348: Optimization Techniques.
All code and writing is original. If reused, please credit the author.
