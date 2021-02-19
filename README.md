# Tensors, differential forms, and computer graphics
A textbook on the application of differential forms to computer graphics. This book is 100% complete as of Nov. 9 2020.

## Abstract

Below is the abstract for my senior thesis at Carleton College. I'm including it here because it serves as a good overview of this textbook.

Differential geometry is in many ways a thorough investigation and reorganization of the integral theorems of “vector calculus”. Remember div, grad, and curl? Green’s theorem? The divergence theorem? Maybe Stokes’ theorem? These ideas are beautifully generalized by the notion of differential forms, which are algebraic objects invented to be integrated over “multidimensional surfaces”. We will briefly introduce differential forms and present the generalized Stokes’ theorem, which is a very general version of the fundamental theorem of calculus. The generalized Stokes’ theorem is deceptively simple in appearance; it looks simpler than the theorems it generalizes!

After introducing differential forms, we ponder a central theme of calculus: using limiting processes to produce smooth objects from finite ones. Can we do anything interesting if we reverse this process? That is, what if we start with a smooth theory and then discretize? We will present how differential forms, when discretized, can be utilized to solve problems in computer graphics. Namely, we will show how discrete differential forms can be used to “smooth out details” on a surface and to wrap a two-dimensional map around a globe in an angle-preserving manner.

## Table of contents

Review sections:

1. Review of logic, proofs, and functions
2. Review of linear algebra

Part I: Multilinear algebra and tensors

3. A motivated introduction to tensors
4. Bilinear forms, metric tensors, and coordinates of tensors
5. Exterior powers, the determinant, and orientation

Part II: Calculus and basic topology

6. Review of calculus
7. Basic topology

Part III: Differential forms

8. Manifolds
9. Differential forms on manifolds

Part IV: Computational applications of differential forms

10. Discrete differential geometry and computer graphics
10.1. Discrete differential geometry
10.2. Smoothing with the Laplacian
10.3. Surface parameterization

## Chapter 1: review of logic, proofs, and functions

As of Jan. 25 2021, an in-progress chapter on logic and proofs is now included in the book. Though incomplete, this section may still be helpful. In particular, a proof-writer of any level might appreciate the section on the implication operator =>, as this operator is often only halfway understood and badly explained. The chapter is complete up until the "Set difference and set complement" section. (A historical note: the content of this chapter that is complete was written in 2020, long before Jan. 25 2021; it is on Jan. 25 2021 that I decided to include this material in the compiled PDF). 

## Copyright

This textbook is intended to be downloaded and read for free. If you would like to repurpose the content of this book, please clearly state that you have done so and credit this textbook as a reference.
