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

License
-------

This program is released under the MIT License: http://opensource.org/licenses/MIT

Copyright (c) 2013 Jonas Einarsson
Origov. 6B, 41296 Gothenburg, Sweden
jonas.einarsson@physics.gu.se

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.