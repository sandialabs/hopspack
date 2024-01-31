# hopspack - Hybrid Optimization Parallel Search PACKage

HOPSPACK is open source software for solving optimization problems without derivatives. Application problems may have a fully nonlinear objective function, bound constraints, and linear and nonlinear constraints. Problem variables may be continuous, integer-valued, or a mixture of both. The software provides a framework that supports any derivative-free type of solver algorithm. Through the framework, solvers request parallel function evaluation, which may use MPI (multiple machines) or multithreading (multiple processors/cores on one machine). The framework provides a Cache and Pending Cache of saved evaluations that reduces execution time and facilitates restarts. Solvers can dynamically create other algorithms to solve subproblems, a useful technique for handling multiple start points and integer-valued variables. HOPSPACK ships with the Generating Set Search (GSS) algorithm, developed at Sandia as part of the APPSPACK open source software project.

Stephens, J Adam
Adams, Brian

SCR# 1244

The XZ Tar File of original SVN repo is located under Releases.
