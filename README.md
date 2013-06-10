==========
FPE_Sphere
==========

Mathematica notebooks to solve FPEs on the sphere.
--------------------------------------------------

Numerical solutions in terms of a spherical harmonics expansion in three steps

fpe_sphere_matrix_elements.nb
	
	Compute matrix elements <p,q|J|l,m> of operator J.

fpe_sphere_assemble_sparse.nb
	
	Assemble and save sparse matrix representations of the FPE with the matrix elements from (1)

fpe_sphere_solve.nb

	Solve sparse matrix problems assembled in (2)


Step through the three notebooks in order to perform the calculation. I recommend doing it step-by-step and reading the comments.

For a clearer and faster presentation, make sure to set St = 0 in the first operator. This will solve the normal Jeffery equation instead of the complete St > 0 correction.