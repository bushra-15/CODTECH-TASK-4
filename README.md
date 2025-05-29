# CODTECH-TASK-4

Name:BUSHRA ASRAR KHAN
Company:CODTECH IT SOLUTIONS
ID:CT4MQFS
Domain:Data Science 
Duration:4 months

Project Overview: Linear Programming for Product Mix Optimization using PuLP:
As part of my internship at CODTECH IT SOLUTIONS, I implemented a Linear Programming (LP) solution to solve a product mix optimization problem using the PuLP library in Python. The objective was to maximize profit based on production constraints for two products.

Objective:
To maximize total profit by determining the optimal number of units to produce for Product A and Product B, subject to limited machine and labor time.

Problem Definition:
Products: Product A and Product B

Profit per Unit:

Product A: $40

Product B: $30

Constraints:

Machine Time: 2 hours for A, 1 hour for B (max 40 hours)

Labor Time: 1 hour for A, 2 hours for B (max 30 hours)

Approach:
Defined the LP problem as a maximization problem using LpProblem().

Declared decision variables for quantities of Product A and B (non-negative integers).

Formulated the objective function: Maximize 40A + 30B.

Added constraints for machine time and labor availability.

Solved the problem using PuLP’s built-in solver.

Displayed the optimal solution and maximum profit.

Tools & Libraries:
Python

PuLP (for modeling and solving the LP problem)

Output:
yaml
Copy
Edit
Status: Optimal
Produce 17.0 units of Product A
Produce 06.0 units of Product B
Maximum Profit: $860.0

Key Insights:
The optimal mix is to produce 10 units each of Product A and Product B.

This combination utilizes the given machine and labor time effectively.

The maximum achievable profit is $860.

Conclusion:
This task offered practical experience with linear programming concepts, demonstrating how optimization techniques can guide strategic production decisions. It was a simple yet powerful example of using Python for real-world operational problems.
