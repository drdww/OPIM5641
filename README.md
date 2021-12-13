# Welcome to OPIM 5641: Business Decision Modeling!
Dr. Dave Wanik - Dept. of Operations and Information Management - University of Connecticut

## Course Description

Discusses business modeling and decision analysis. Covers topics such as optimization, simulation, and sensitivity analysis to model and solve complex business problems. As Python* is often used as a software tool for optimization, the course will emphasize developing high quality code to ensure that the objectives of the model are clear, defining the calculations, good design practices, testing and presenting the results.

*This course will be taught using Python - special topics week on Excel at the end of the semester!

## Course Objectives

By the end of the semester, students should be able to: 

* Describe and analyze data using Python.
* Translate business problems into mathematical models (objective functions, decision variables, constraints.)
* Solve linear programming (allocation, covering, blending, network, integer) and nonlinear programming problems using Python.
* Perform sensitivity analysis and calculate shadow prices for binding constraints.
* Use Monte Carlo simulation to explore decision-making under uncertainty.

## Course Outline and Objectives

### Module 1: Python Bootcamp/Exploratory Data Analysis/Brute Force  
* Develop well-designed Colab notebooks (organized layout, text cells with beautiful formatting; code cells with lots of comments)
* Describe, summarize and visualize data in Python
* Enrich existing data with external sources (like Wikipedia and Github)
* Implement Monte Carlo simulation and interpret the output probabilistically
* Solve optimization problems in Python using the 'brute force' method


### Module 2: Mathematics for Linear Programming (Graphical Method, Simplex Algorithm)

* Define the elements of a linear programming problem (objective function, decision variables, constraints)
* Solve 2D linear programming problems using the graphical method.
* Solve 2D and 3D linear programming problems using the Simplex algorithm.

### Module 3: Linear Programming Models (Allocation, Covering, Blending)

* Translate narrative word problems into a basic mathematical formulations (build a mathematical representation of reality).
* Solve allocation (packing) and covering problems using Pyomo.
* Convert proportions into linear constraints and solve blending problems.
* Identify binding constraints and calculate shadow prices.
* Generate and interpret the 'Sensitivity Report' using Pyomo and GLPK.

### Module 4: Integer Optimization

* Change the domain of decision variables to force decision variables to take on integer values.
* Identify and define binary constraints and use them for project selection problems. 
* Identify and define fixed and variable costs, and use linking contraints to ensure consistency. 
* Use linking constraints to apply min/max thresholds and quantity discounts.


### Module 5: Network Optimization 

* Conceptualize, draw and solve the transportation problem (where supply >= demand) for a minimum cost flow example.
* Generalize the transportation model to a two-stage trans-shipment problem (requires a compound objective function).
* Conceptualize, draw and solve the 'reduction in flow' example (where demand > supply) and the 'expansion in flow' example (also known as 'laddering' in the finance world).
* Apply Monte Carlo simulation techniques to network problems.

### Module 6: Nonlinear Optimization

* Model a problem as a nonlinear optimization model and solve it using Pyomo. Separate model from data and using data structures to create Pyomo models (for constraints/calculations).
* Understand the differences between local optimal solutions and global optimal solutions. Apply techniques to improve your chances of identifying global optimal solutions for nonlinear optimization problems
* Implement Monte Carlo simulation and interpret the output probabilistically
* Use real-time stock price data to allocate a portfolio and maximize returns for a given level of risk
