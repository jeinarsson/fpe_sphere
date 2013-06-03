FPE_Sphere
==========

Mathematica notebooks to solve FPEs on the sphere.

Numerical solutions in terms of a spherical harmonics expansion in three steps

1. fpe_sphere_matrix_elements.nb
Compute matrix elements <p,q|J|l,m> of operator J.

2. fpe_sphere_assemble_sparse.nb
Assemble and save sparse matrix representations of the FPE with the matrix elements from (1)

3. fpe_sphere_solve.nb
Solve sparse matrix problems assembled in (2)