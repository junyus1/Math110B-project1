# Math110B-project1
The group work is finished by Fangyang Zhang, Jiaxin Li, and Junyu Sui

Our main idea is use deterministic optimization and cvxpy package to solve sudoku problem. Division of work is Fangyang Zhang and Jiaxin Li work on the solver function, Jiaxin Li works on the check function and do_easy_steps function, and Junyu Sui works on the data summary and double check job.

We used deterministic optimization. Firstly, we express the three constraints(Column constraint, Row constraint, Block constraint, and Cell constraint) of Soduku as matrix form. Finally, we use convex optimization solver to solve the above constraints, since linear programming has convex constraints and a convex objective function. Note the objective function we choose is just the L1 norm, since constraint satisfaction is the main part to focus on.
