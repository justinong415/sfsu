# Econ 715: Mathematical Economics

Notes from lecture videos and official lecture notes with addendums.

## Addendum: Matrix & Linear Algebra Definitions

#### Determinant of a Matrix

![Screen Shot 2021-09-01 at 5 34 29 PM](https://user-images.githubusercontent.com/31806435/131763004-2dc7e94d-0f01-47ee-bed4-26be73a00d16.png)

#### Idempotent (Idempotence)

An idempotent matrix is a matrix which, when multiplied by itself, yields itself. (i.e. Matrix _A_ is idempotent if ![gif](https://user-images.githubusercontent.com/31806435/131763270-8918db7f-86fb-48c5-b82a-5ecb2a7f8ab4.gif))

![Screen Shot 2021-09-01 at 5 39 09 PM](https://user-images.githubusercontent.com/31806435/131763348-c944a720-97ae-42fb-b86b-1a15ec74cae9.png)

#### Square Matrix

A square has the same number of rows as the number of columns. (i.e. _m_ = _n_) 

<img width="481" alt="Screen Shot 2021-09-01 at 5 43 18 PM" src="https://user-images.githubusercontent.com/31806435/131763668-83479f2c-7fb8-4874-b5d6-d1f5901f9e11.png">

#### Column Vector, Row Vector, Scalar

1. Column Vector: A matrix with one column (_n_ = 1)
2. Row Vector: A matrix with one row (_m_ = 1)
3. Scalar: A matrix with only one element or a number (_m_ = _n_ = 1)

<img width="481" alt="Screen Shot 2021-09-01 at 5 46 39 PM" src="https://user-images.githubusercontent.com/31806435/131763911-8d488cfc-bc8b-4a6f-9550-80cd745c5fed.png">

#### Symmetric

A symmetric is a square matrix that is equal to its tranpose (i.e. A = A')

![Screen Shot 2021-09-01 at 5 51 34 PM](https://user-images.githubusercontent.com/31806435/131764264-87144d07-d300-4213-88c6-2c355e17788b.png)

Note: Symmetric matrices must be square and have ![gif](https://user-images.githubusercontent.com/31806435/131764510-d0aeaf8f-b291-4988-b8ee-75c3e7ebae03.gif).

#### Diagonal

A [diagonal](https://en.wikipedia.org/wiki/Diagonal_matrix) is a square matrix that has all off-diagonal elements equal to zero and at least one element on the diagnoal not zero. (i.e. Where the entries outside the [main diagonal](https://en.wikipedia.org/wiki/Main_diagonal) are all zero.)

![Screen Shot 2021-09-01 at 6 08 31 PM](https://user-images.githubusercontent.com/31806435/131765413-fad39f83-c56f-47f1-b3ec-6e11ff220c42.png) 

![Screen Shot 2021-09-01 at 6 08 41 PM](https://user-images.githubusercontent.com/31806435/131765416-b9d2ecff-26f3-429d-b687-e06890862cd2.png)

#### Identity Matrix (denoted _I_ or ![gif](https://user-images.githubusercontent.com/31806435/131765484-40d66682-7da5-4add-88ce-737766c1f428.gif))

An [identity matrix](https://en.wikipedia.org/wiki/Identity_matrix) of size _n_ is the _n_ × _n_ square matrix with ones on the main diagonal and zeros elsewhere

![Screen Shot 2021-09-01 at 6 12 56 PM](https://user-images.githubusercontent.com/31806435/131765722-e690f934-b7fd-4470-8e7f-3d1c48d26d3a.png)

#### Null Matrix

A matrix with all elements equal to zero. Denoted by 0 or ![gif](https://user-images.githubusercontent.com/31806435/131765957-f4f9937f-a90f-49f2-9606-745d2ddb67a0.gif)

<img width="261" alt="Screen Shot 2021-09-01 at 6 32 53 PM" src="https://user-images.githubusercontent.com/31806435/131767212-eaf02307-d654-48fb-a239-5117e4f1ffca.png">

#### Invertible or nonsingular

1. If the inverse of a matrix _A_ exists, it is invertible or nonsingular.
2. If the inverse does not exist, it is non-invertible or singular.

![gif](https://user-images.githubusercontent.com/31806435/131766946-ae1847d5-87ff-4544-bcbd-8ce4cbcc1c93.gif)

![deepai](https://user-images.githubusercontent.com/31806435/131766987-83eb0790-746b-4a04-be0e-158d2ad5f993.png)

#### Conditions under which matrix product is Well Defined

Matrix product _AB_ is only well defined if number of columns in _A_ is the same as number of rows in _B_.

i.e. if ![gif](https://user-images.githubusercontent.com/31806435/131767531-b1dce5b2-d324-42c0-a72e-658a1468b39a.gif) and ![gif-1](https://user-images.githubusercontent.com/31806435/131767550-68673b48-4d5f-4ddb-b818-335ccf3b8a2d.gif), then ![gif-2](https://user-images.githubusercontent.com/31806435/131767572-eac5fca5-15e2-4bc1-adf6-032847df50aa.gif) for ![gif-3](https://user-images.githubusercontent.com/31806435/131767630-604a49b2-65c5-4485-b0c7-0a1e6a0a282a.gif).

<img width="578" alt="Screen Shot 2021-09-01 at 6 39 29 PM" src="https://user-images.githubusercontent.com/31806435/131767662-c488df1d-d57c-4dea-8ddc-5dc59346022e.png">

#### Conditions under which matrix addition ![gif](https://user-images.githubusercontent.com/31806435/131767720-7158fbc7-e160-499e-a1bc-efb7a6ef5ddb.gif) is Well Defined (where ![gif-1](https://user-images.githubusercontent.com/31806435/131767752-77c08f56-f8ca-4e78-9448-0fe27c59ef3c.gif))

1. _A_ must be a square matrix
2. _m_ = _n_
3. _A_ must be symmetric
4. _A_ must be idempotent

## Week 1: Course overview

#### Economics - a Subfield of Optimization Theory

Economics is the study of how individuals, firms, and society make choices in the presence of scarcity. 

Thus, any economic problem is constrained optimization:

![Screen Shot 2021-08-24 at 6 46 09 PM](https://user-images.githubusercontent.com/31806435/130712859-0927f260-6928-421a-a92a-78ccf9688a85.png)

#### Estimation is also Optimization

1. Ordinary Least Squares:

![OLS](https://user-images.githubusercontent.com/31806435/130713267-ce246856-13e2-49e2-b7d9-8f1e6bcc9e1d.png)

2. Maximum Likelihood:

![max_likelihood](https://user-images.githubusercontent.com/31806435/130713293-dbdea10b-c100-4ab7-9dac-121c2f9b51e0.png)

3. Almost any Machine Learning algorithm is an optimziation problem.
* Main goal of the course - **develop tools for solving optimization problems.**

#### This Course Structure

1. Linear Models and Matrix Algebra
2. Limits and Differential Calculus
3. Optimization

#### Matlab

1. Mathematical software is useful for visualizing concepts in math.
2. Many practical problems cannot be solved without computers.
3. Matlab is available for free to all CSU students.
4. Matlab is easy to use.

#### Linear systems

Linear system of _m_ linear equations with _n_ unknowns:

![linear_system](https://user-images.githubusercontent.com/31806435/130714614-d40fdb21-0da1-4626-ae2c-91334b530df9.png)

 1. left hand side of every equation is a linear function, or a weighted average of some unknown variables (i.e. the x's)
 2. ![gif](https://user-images.githubusercontent.com/31806435/130714770-968b192e-7d3c-4d4a-a00a-eb630c832990.gif) - unknown variables
 3. ![gif](https://user-images.githubusercontent.com/31806435/130714856-3ca48d84-1f63-4ee2-bb61-9f30b073ad60.gif) - coefficients (known numbers, scalars, weights) in equation _i_ on variable ![gif](https://user-images.githubusercontent.com/31806435/130714897-5bb9d6e0-4e7d-4fdf-a074-b0eb7e52a736.gif)
 4. ![gif](https://user-images.githubusercontent.com/31806435/130714962-4a8ceed3-6dfa-434d-a0fe-a99ef45dc7d1.gif) - are given known numbers on right hand side, are scalars
 5. what makes the system linear is that each left hand side as a function of _x_ is a linear function or a weighted average of the unknown variables _x_'s 

#### Example

linear system with 3 equations and 3 unknowns (_m_ = 3, _n_ = 3):

![Screen Shot 2021-08-24 at 7 21 33 PM](https://user-images.githubusercontent.com/31806435/130715787-c5850b5b-d040-4811-acd3-a3a75fc5bc14.png)

linear system with 2 equations and 3 unknowns (_m_ = 2, _n_ = 3):

![Screen Shot 2021-08-24 at 7 23 05 PM](https://user-images.githubusercontent.com/31806435/130715916-f62949dc-2759-4acc-9c70-2e98b4470a86.png)

linear system with 3 equations and 2 unknowns (_m_ = 3, _n_ = 2):

![Screen Shot 2021-08-24 at 7 23 55 PM](https://user-images.githubusercontent.com/31806435/130715989-b428ae81-9535-4d3a-94b6-fc3d845780fc.png)

nonlinear system (because of quadratic terms and square roots): 

![Screen Shot 2021-08-24 at 8 05 33 PM](https://user-images.githubusercontent.com/31806435/130719693-5afdff89-6439-4f18-9522-ec213442c079.png)

#### Why are we interested in Linear Systems?

 1. some economic models are described as linear systems.
 2. solution and analysis of non-linear systems often utilize linear methods.

#### Solutions to Linear Systems

Definition: a **solution** to linear system is an _n_-tuple x = x_1, x_2, ..., x_n (or a list of unknown variables), which satisfies each of the equations. The set of all the solutions to a linear system is called the **solution set**.

Key questions:
1. Does a solution exist?
2. Under what conditions there exists a unique solution?
3. How to compute the solutions, if they exist?

#### General Result about solution of linear systems

Theorem: the solution set to any linear system with _m_ equations and _n_ unknowns either 
1. contains a unique solution
2. empty (no solution)
3. contains infinitely many solutions.

Verify the following theorem for single linear equation with one unknown:

![gif](https://user-images.githubusercontent.com/31806435/130720567-3a5fadcf-ab6d-42f1-b7d1-a1cdae3c5b18.gif)

There are only three possibilities regarding the solution set of such equations:
1. Unique solution, when _a_ ≠ 0. In this case, the unique solution is given by ![gif](https://user-images.githubusercontent.com/31806435/130720702-8e242506-15de-4d94-ab06-b187c54f4fcb.gif).
2. No solution, when _a_ = 0 and _d_ ≠ 0. There is no _x_ that satisfies 0 · _x_ = 5 for example.
3. Infinitely many solution, when _a_ = 0 and _d_ = 0. Any _x_ satisfies 0 · _x_ = 0.

#### What's next?

* The rest of Chapter 1 is devoted to matrix algebra methods used for answering the key questions
  * Does a soluton exist?
  * Under what conditions there exists a unique solution?
  * How to compute the solutions, if they exist? (focus on (_i_) Gaussian Elimination, (_ii_) Matrix Inversion, and (_iii_) Cramer's rule).  
* Also, applications to economics

## Week 2: Introduction to Matrix Algebra

#### Linear Systems in Matrix Form

Linear systems of _m_ linear equations with _n_ unknowns:

![Screen Shot 2021-08-31 at 6 23 48 PM](https://user-images.githubusercontent.com/31806435/131597481-b7cd3d58-cb43-4559-afb8-d4bf56544c0a.png)

Matrix form, _Ax_ = _d_:

![Screen Shot 2021-08-31 at 6 24 18 PM](https://user-images.githubusercontent.com/31806435/131596613-82fa6237-fa6b-48a8-b779-82700f0646df.png)

Linear system:

![Screen Shot 2021-08-31 at 6 41 02 PM](https://user-images.githubusercontent.com/31806435/131597888-45fa6713-f067-4790-9a58-9ba2e96da685.png)

In matrix form:

![Screen Shot 2021-08-31 at 6 41 33 PM](https://user-images.githubusercontent.com/31806435/131597928-18ed7b96-2610-448e-a6c4-afcb59847774.png)

#### Advantages of Matrix Form

1. _Ax_ = _d_ is compact and elegant notation.
2. Matrix algebra tools help (i) determine if a unique solution to a linear system exists and (ii) how to find it.
3. We can determine if a unique solution to _n_ × _n_ system exists by calculating a single number from the matrix _A_ - the determinant of the matrix: |_A_| or det(_A_). A unique solution _n_ × _n_ exists ↔ |A| ≠ 0.
4. If a unique solution to _n_ × _n_ system exists, it can be represented like a solution to single euqation with one unknown:

![Screen Shot 2021-08-31 at 6 48 09 PM](https://user-images.githubusercontent.com/31806435/131598464-c307b735-dd0c-4da4-9deb-2292cfc72a0c.png)

#### Ch 1.2: Basic Concepts of Matrix Algebra

1. Definition of matrices.
2. Special matrices (square, symmetric, diagonal, triangular, idempotent).
3. Matrix operations (addition, multiplication, transpose, determinant, inverse).
4. Matrix algebra tools developed in this chapter are useful not only for linear systems, but also for non-linear systems (Ch. 2).

