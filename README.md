NAME-Siddharth Sharma 
company-Codetech It Solution 
Intern ID-CT6WEUR 
Domain-Data science 
Duration-December 2024 to February 2025
Description of the Optimization Model
The code defines and solves a linear programming optimization problem to maximize profit for a factory producing two products, A and B, under constraints for labor and machine hours.

Steps in the Solution
Problem Definition:

Objective: Maximize profit.
Decision Variables: Units of products A and B to produce.
Constraints:
Labor hours available: 200.
Machine hours available: 150.
Mathematical Model:

Objective Function: Maximize 
40
𝑥
𝐴
+
30
𝑥
𝐵
40x 
A
​
 +30x 
B
​
 .
Constraints:
2
𝑥
𝐴
+
1
𝑥
𝐵
≤
200
2x 
A
​
 +1x 
B
​
 ≤200 (Labor).
𝑥
𝐴
+
2
𝑥
𝐵
≤
150
x 
A
​
 +2x 
B
​
 ≤150 (Machine).
Solution:

Solves using the PuLP library.
Displays the optimal production plan and total profit.
Insights:

A visualization shows the feasible region, constraints, and the objective function's profit line.
Python Tools Used
PuLP:

For defining and solving the linear programming problem.
Matplotlib:

For visualizing the feasible region and constraints.
NumPy:

For creating numerical ranges to support visualization.
How to Use
Run the code to find the optimal production quantities and total profit.
Visualize the feasible region, constraints, and objective function.
Adapt the model for other business problems by adjusting the constraints and objective function.







