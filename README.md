# IAM 961 Numerical Linear Algebra

University of New Hampshire, fall 2017  
Instructor: John Gibson, john.gibson@unh.edu  
Lecture: MW 9:40-11:00am, Kingsbury N389  
Office hours: t.b.d. Kingsbury N309E, or after class

**Official course description**: Introduction to numerical analysis and computational methods for linear systems. Topics include: IEEE floating point arithmetic; vector norms and induced norms; conditioning; LU decomposition; QR decomposition; Gram-Schmidt orthogonalization; Householder triangularization; singular value decomposition; least squares problems; stability, conditioning, and accuracy; eigenvalue problems; power iterations; QR algorithm; Krylov methods; Arnoldi iteration; GMRES; Lanczos iteration; conjugate gradient algorithm; and preconditioning. Prereq: scientific programming and linear algebra.

**Descriptive course description**: Numerical linear algebra is the science of solving systems of linear equations ￼Ax=b and the eigenvalue problem ￼Av = &#955;v on a digital computer –problems that are at the root of the vast bulk of scientific computation. Compared to classical linear algebra, the finite precision and computational cost of numerical mathematics brings in a number of important new concepts, including conditioning, stability, accuracy, and efficiency. We will develop these ideas and learn the most important numerical linear algebra algorithms: QR, LU, SVD decompositions, Gramm-Schmidt orthogonalization, the QR eigenvalue algorithm, and Krylov subspace methods. Time permitting, we will also study key algorithms for function optimization and the solution of systems of nonlinear equations. 

**Julia**: Programming for this course is in the [Julia programming language](http://www.julialang.org/). That includes lecture demos, example codes, and homeworks. Julia is a flexible as Python, as numerically focused as Matlab, and as fast as C. It's the future of scientific computing. Get on board now!

**Text:** [Numerical Linear Algebra](http://bookstore.siam.org/ot50/) by Trefethen and Bau, SIAM Press. This is an unusually readable textbook. Lectures will follow it closely. I strongly recommend you buy a paper copy. You can get it for only $50 with a student SIAM membership. 

## Course outline

We will follow Trefethen and Bau's text pretty closely, chapter by chapter, with additional introductory material here and there on Julia. Here's a slightly different conceptual organization of the course than provided by Trefethen and Bau's table of contents, with rough dates. By the end of the semester, you should have a pretty good grasp of each of the topics mentioned herein.

1. **Fundamentals**, Aug 28 -- Sep 22
    - Why Julia?
    - linear algebra review: vector spaces, matrix-vector, matrix-matrix multiplication, inverses, span, rank, etc.
    - orthogonality, norms, SVD
    - Trefethen lectures 1-5
2. **Direct methods**, Sep 25 -- Oct 27
    - QR factorization: Gramm-Schmidt algorithms, Householder algorithm, least squares
    - floating point arithmetic
    - conditioning, stability, accuracy
    - LU decomposition
    - Trefethen chapters 6-23
3. **Iterative methods**, Oct 30 -- Dec 12
    - eigenvalue algorithms: Rayleigh quotient iteration, inverse iteration, QR algorithm
    - SVD algorithm (time permitting)
    - Krylov subspace methods: Arnoldi iteration, GMRES, and conjugate gradients
    - Trefethen chapters 24-40
    
## Grading and homework

Course grades will be determined from roughly six homework assignments. Some homeworks will be proof-oriented pencil-and-paper assignments, others will be algorithmic in nature and distributed as Julia notebooks. 
