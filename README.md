This project contains solutions to multiple linear programming problems, implemented in Python using matplotlib for graphing and numpy for mathematical computations. Each problem involves graphical methods to solve optimization tasks, such as maximizing profit, minimizing cost, and allocating resources for different production scenarios.

Prerequisites
Before running the Python scripts, make sure you have the required libraries installed. You can install the required packages using pip:
pip install numpy matplotlib
- Run the following command to install the required packages:
```bash
- pip install jupyter
- pip install pandas
- pip install numpy
- pip install matplotlib

Overview of Problems
1. Maximizing Profit for a Factory
Objective: Maximize the profit by optimizing production quantities subject to given constraints on resources.
Methodology:
Plot constraints representing the limits on production resources.
Find the feasible region where all constraints are satisfied.
Identify corner points and the optimal solution for maximizing profit.
Key equations:
2x + 3y <= 12
x + 2y <= 8
2. Minimizing Cost for a Manufacturer
Objective: Minimize the cost of manufacturing by choosing optimal quantities of products.
Methodology:
Plot constraints and feasible regions.
Identify the optimal production levels that minimize cost while meeting constraints.
Key equations:
x + 2y >= 6
2x + y >= 5
3. Maximizing Production with Multiple Resources
Objective: Maximize production subject to multiple resource constraints (e.g., labor, material, and machine time).
Methodology:
Use multiple constraints to determine the feasible production quantities.
Identify the optimal solution that maximizes production.
Key equations:
2A + B <= 20 (Labor)
3A + 2B <= 30 (Material)
A + 2B <= 18 (Machine time)
4. Maximizing Revenue from Sales
Objective: Maximize the revenue from two products subject to advertising and production capacity constraints.
Methodology:
Plot constraints and the feasible region.
Identify the optimal production levels for maximum revenue.
Key equations:
A + 2B <= 20 (Advertising budget)
A + 2B <= 15 (Production capacity)
5. Resource Allocation for Two Projects
Objective: Allocate resources to two projects to maximize profit.
Methodology:
Plot constraints and the feasible region for resource allocation.
Determine the optimal allocation of resources.
Key equations:
3x1 + 4x2 <= 12 (Labor hours)
2x1 + x2 <= 6 (Capital constraint)
6. Production Planning for a Bakery
Objective: Maximize profit by determining the optimal production of two types of cakes (chocolate and vanilla).
Methodology:
Plot the constraints and the feasible region for the bakery.
Identify the optimal production quantities for maximum profit.
Key equations:
x1 + 2x2 <= 8 (Baking time)
3x1 + 2x2 <= 12 (Flour constraint)
Running the Code
Each question has its own Python script that can be run individually. To execute the code:

Download the script or copy it into a Python file (e.g., problem1.py).
Run the script using Python:
bash
Copy code
python problem1.py
Each script will:

Plot the constraints and feasible regions.
Display the optimal solution, including the coordinates of the optimal point and the corresponding value of the objective function.
Methodology
Each problem uses a graphical approach to solve linear programming problems:

Constraints are represented as lines or curves on a graph.
The feasible region is the area where all constraints intersect.
The optimal solution is found at the corner points of the feasible region, where the objective function (profit, cost, revenue) is maximized or minimized.
Intersection points are calculated by solving systems of equations.
Corner Points
Each solution method identifies corner points where constraints meet. These points are evaluated to find the optimal solution.

Objective Function
The objective function represents the quantity that needs to be maximized or minimized (e.g., profit, cost). The optimal point corresponds to the maximum or minimum value of the objective function within the feasible region.

Output
The output for each question will be:

Graphical plot showing the constraints, feasible region, and corner points.
Optimal solution:
The coordinates of the optimal point.
The value of the objective function at that point.
Example output for Question 1 (Maximizing Profit for a Factory):

Plot displaying constraints and feasible region.
Optimal point: (8, 0) with a maximum profit value.
