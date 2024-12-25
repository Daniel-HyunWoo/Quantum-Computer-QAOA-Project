# Quantum-Computer-QAOA-Project

This is the repository about Quadratic Apporoximate Optimization Algorithm(QAOA) Project I conducted by using real Quantum Hardware IBM Chip Eagle located at Yonsei University, Rep of Korea

The main purpose of this porject is to solve Knapsack Problem, which is NP-Complete problem in terms of computer science, by uitlizing QAOA Method

I made 3 functions and 1 program script
[knapsack_argument] is a function that solve multi option Knapsack Problem quickly with the help of MinimumEigenOptizer that is a function of qiskit_optimization.algorithms package.
[formulate_qp] & [solve_qp_with_qiskit] do similar job as [knapsack_argument] but It transforms given problem condition to Quadratic Problem from with Constraints so that I am able to visualize QAOA Ansatz to Quantum Circuit.

Codes below "Making Quantum Circuit of QAOA Ansatz" is the procedure of remaining QAOA. 

Please read, enjoy & criticize!


