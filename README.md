# CDLC-SAT-Solver
SAT solver for CNF formulas

A SAT Solver using the Conflict Driven Clause Learning (CDCL) algorithm to check the satisfiability of an input Conjuctive Normal Form (CNF) formula in DIMACS format. The SAT Solver returns a satisfying assignment, and UNSAT otherwise if there is no satisfying assignment for the input CNF formula. The SAT Solver also returns a proof of unsatisfiability for only UNSAT problems. The proof of unsatisfiability works on the basis that if an empty clause can be derived from the clauses, then it must follow that the formula is unsatisfiable.
