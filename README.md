# OPTIMIZATION-MODEL-TASK-4

*COMPANY NAME: CODTECH IT SOLUTION

NAME:BANDIKARLA ACHYUTHVIVEK

INTERN ID:CT08DZ1113

DOMAIN NAME:DATA SCIENCE

DURATION:8 WEEKS

MENTOR: NEELA SANTOSH

Task Description :–
Optimization Model: Production Optimization Problem
1. Introduction
Optimization techniques, specifically Linear Programming (LP), are widely used to solve decision-making problems where resources are limited, and the goal is to maximize or minimize a certain objective. Linear programming helps in determining the best outcome from a set of linear constraints and an objective function. In this case, we are using Python and the PuLP library to solve a production optimization problem for a factory that manufactures two products, Product A and Product B.

#### **Problem Overview:**

We aim to maximize the **profit** for a factory that produces two products, **Product A** and **Product B**, given constraints on machine time. The objective is to decide the optimal number of each product to produce in order to maximize profit while respecting machine time constraints.

#### **Mathematical Formulation:**

1. **Decision Variables**:

   * $x_A$: Number of **Product A** to produce.
   * $x_B$: Number of **Product B** to produce.

2. **Objective Function (Profit Maximization)**:

   $$
   \text{Maximize } Z = 50x_A + 40x_B
   $$

   Where:

   * Profit from Product A = \$50 per unit
   * Profit from Product B = \$40 per unit

3. **Constraints**:

   * **Machine 1**: $x_A + 2x_B \leq 100$ (Time constraint for Machine 1)
   * **Machine 2**: $2x_A + x_B \leq 150$ (Time constraint for Machine 2)
   * **Non-negativity**: $x_A \geq 0$, $x_B \geq 0$

---

#### **Steps to Solve**:

1. **Define the problem** as a maximization problem.
2. **Set decision variables** $x_A$ and $x_B$.
3. **Maximize profit** with the objective function $50x_A + 40x_B$.
4. **Add constraints** for machine times and non-negativity.
5. **Solve the problem** using a linear programming solver (PuLP in Python).

---

#### **Solution Example**:

* **Optimal Production**: Produce **25 units of Product A** and **37.5 units of Product B**.
* **Maximum Profit**: \$2375.

#### **Graphical Representation**:

* Plot the **feasible region** (the area satisfying the constraints).
* Mark the **optimal solution** where the profit is maximized.

---

### **Summary**:

This model uses **Linear Programming (LP)** to maximize the profit while considering machine time constraints. The key formulas are:

$$
\text{Maximize } Z = 50x_A + 40x_B
$$

$$
\text{Subject to: }
$$

$$
x_A + 2x_B \leq 100 \quad \text{(Machine 1 constraint)}
$$

$$
2x_A + x_B \leq 150 \quad \text{(Machine 2 constraint)}
$$

$$
x_A, x_B \geq 0 \quad \text{(Non-negativity)}
$$

This formulation provides a solution to maximize profits while ensuring resource constraints are satisfied.

Output:-

<img width="774" height="590" alt="image" src="https://github.com/user-attachments/assets/fb5f031f-9e12-4a42-8e94-ab36438f225d" />

Optimal number of Product A to produce: 25.0
Optimal number of Product B to produce: 37.5
Maximum profit: $ 2375.0


