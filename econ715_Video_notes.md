# Econ 715 Notes
**Mathematical Economics**
---

### Week 1: August 23 - August 29

**Video: Couse overview**

Economics - a Subfield of Optimization Theory

Economics is the study of how individuals, firms, and society make choices in the presence of scarcity. 

Thus, any economic problem is constrained optimization:

![Screen Shot 2021-08-24 at 6 46 09 PM](https://user-images.githubusercontent.com/31806435/130712859-0927f260-6928-421a-a92a-78ccf9688a85.png)

Estimation is also Optimization

1. Ordinary Least Squares:

![OLS](https://user-images.githubusercontent.com/31806435/130713267-ce246856-13e2-49e2-b7d9-8f1e6bcc9e1d.png)

2. Maximum Likelihood:

![max_likelihood](https://user-images.githubusercontent.com/31806435/130713293-dbdea10b-c100-4ab7-9dac-121c2f9b51e0.png)

3. Almost any Machine Learning algorithm is an optimziation problem.
* Main goal of the course - **develop tools for solving optimization problems.**

This Course Structure

1. Linear Models and Matrix Algebra
2. Limits and Differential Calculus
3. Optimization

Matlab

1. Mathematical software is useful for visualizing concepts in math.
2. Many practical problems cannot be solved without computers.
3. Matlab is available for free to all CSU students.
4. Matlab is easy to use.


**Video: Linear systems**

Linear system of _m_ linear equations with _n_ unknowns:

![linear_system](https://user-images.githubusercontent.com/31806435/130714614-d40fdb21-0da1-4626-ae2c-91334b530df9.png)

* left hand side of every equation is a linear function, or a weighted average of some unknown variables (i.e. the x's)
* ![gif](https://user-images.githubusercontent.com/31806435/130714770-968b192e-7d3c-4d4a-a00a-eb630c832990.gif) - unknown variables
* ![gif](https://user-images.githubusercontent.com/31806435/130714856-3ca48d84-1f63-4ee2-bb61-9f30b073ad60.gif) - coefficients (known numbers, scalars, weights) in equation _i_ on variable ![gif](https://user-images.githubusercontent.com/31806435/130714897-5bb9d6e0-4e7d-4fdf-a074-b0eb7e52a736.gif)
* ![gif](https://user-images.githubusercontent.com/31806435/130714962-4a8ceed3-6dfa-434d-a0fe-a99ef45dc7d1.gif) - are given known numbers on right hand side, are scalars
* what makes the system linear is that each left hand side as a function of _x_ is a linear function or a weighted average of the unknown variables _x_'s 

linear system with 3 equations and 3 unknowns (_m_ = 3, _n_ = 3):

![Screen Shot 2021-08-24 at 7 21 33 PM](https://user-images.githubusercontent.com/31806435/130715787-c5850b5b-d040-4811-acd3-a3a75fc5bc14.png)

linear system with 2 equations and 3 unknowns (_m_ = 2, _n_ = 3):

![Screen Shot 2021-08-24 at 7 23 05 PM](https://user-images.githubusercontent.com/31806435/130715916-f62949dc-2759-4acc-9c70-2e98b4470a86.png)


linear system with 3 equations and 2 unknowns (_m_ = 3, _n_ = 2):

![Screen Shot 2021-08-24 at 7 23 55 PM](https://user-images.githubusercontent.com/31806435/130715989-b428ae81-9535-4d3a-94b6-fc3d845780fc.png)


nonlinear system (because of quadratic terms and square roots): 

![Screen Shot 2021-08-24 at 8 05 33 PM](https://user-images.githubusercontent.com/31806435/130719693-5afdff89-6439-4f18-9522-ec213442c079.png)


Why are we interested in Linear Systems?

* some economic models are described as linear systems.
* solution and analysis of non-linear systems often utilize linear methods.

Solutions to Linear Systems

Definition: a **solution** to linear system is an _n_-tuple x = x_1, x_2, ..., x_n (or a list of unknown variables), which satisfies each of the equations. The set of all the solutions to a linear system is called the **solution set**.

Key questions:
1. Does a solution exist?
2. Under what conditions there exists a unique solution?
3. How to compute the solutions, if they exist?

**General Result about solution of linear systems**

Theorem: the solution set to any linear system with _m_ equations and _n_ unknowns either _(i)_ contains a unique solution, _(ii)_ empty (no solution), or _(iii)_ contains infinitely many solutions.

Verify the above theorem for single linear equation with one unknown: ![gif](https://user-images.githubusercontent.com/31806435/130720567-3a5fadcf-ab6d-42f1-b7d1-a1cdae3c5b18.gif)

There are only three possibilities regarding the solution set of such equations:
1. Unique solution, when _a_ ≠ 0. In this case, the unique solution is given by ![gif](https://user-images.githubusercontent.com/31806435/130720702-8e242506-15de-4d94-ab06-b187c54f4fcb.gif).
2. No solution, when _a_ = 0 and _d_ ≠ 0. There is no _x_ that satisfies 0 · _x_ = 5 for example.
3. Infinitely many solution, when _a_ = 0 and _d_ = 0. Any _x_ satisfies 0 · _x_ = 0.
