# DraftKings Optimization

## Overview

This project focuses on optimizing DraftKings fantasy sports lineups using **linear programming (LP)** with `Pyomo` and the `appsi_highs` solver. The optimization aims to maximize projected player points while adhering to salary cap constraints. The results are presented in an interactive **HTML file** that includes data visualizations and analytical insights.

The analysis is structured into two key parts:

1. **Linear Programming Optimization**  
   - Uses `Pyomo` and the `appsi_highs` solver to find the optimal lineup.
   - Ensures the lineup remains within budget constraints while maximizing expected performance.
   - Constraints include player position limits, salary cap, and selection rules.

2. **Exploratory Data Analysis & Visualization**  
   - Uses `Matplotlib` and `Seaborn` to analyze player salaries, point distributions, and optimization outcomes.
   - Highlights trends in player performance, cost efficiency, and value selection.
   - Provides graphical representations of the optimal lineup versus alternative selections.

## Technologies Used

- **Pyomo** – Formulates and solves the linear programming problem.
- **appsi_highs** – A high-performance LP solver used for optimization.
- **Matplotlib & Seaborn** – Generates visualizations for data exploration.
- **Pandas & NumPy** – Processes and structures the dataset for analysis.
- **Jupyter Notebook** – Used for initial development and testing.
- **HTML (via Jupyter Export)** – Displays the final results in a structured, interactive format.

## View the Analysis  
Click [here](https://raw.githubusercontent.com/sophiaremington/NFL-DraftKings-Optimization-Project/refs/heads/main/FinalProject%20(2).html) to open the **DraftKings Optimization Report**.


