
# Functional Data Analysis repository

<!-- badges: start -->

![Static Badge](https://img.shields.io/badge/R-language-blue)
![License](https://img.shields.io/badge/License-Apache%202.0%20%2B%20CC%20BY%204.0-teal.svg)
![Static
Badge](https://img.shields.io/badge/Medium-https://medium.com/@vadimtyuryaev-green)
![Static
Badge](https://img.shields.io/badge/LinkedIn-https%3A%2F%2Fwww.linkedin.com%2Fin%2Fvadimtyuryaev%2F-blue)
<!-- badges: end -->

<p align="center">
<img src="Images/DJIA_HAC.jpg" width="600">
</p>

This repository provides a comprehensive exploration of Functional Data
Analysis (FDA) which is a modern branch of statistics that models entire
data trajectories as realizations of underlying functions, rather than
as isolated multivariate points. By shifting perspective from discrete
observations to continuous functional objects, FDA opens the door to
more nuanced insights in fields ranging from biomedical research and
environmental science to finance and engineering.

Designed as both a learning resource and a practical toolkit, this
repository is aimed at:

- Undergraduate and graduate students seeking an accessible entry point
  into FDA;

- Researchers who wish to incorporate FDA techniques into applied or
  theoretical projects;

- Data science practitioners looking to move beyond traditional
  multivariate approaches and capture the dynamics of complex,
  high-dimensional data.

By visiting the website
(`vadimtyuryaev.github.io/Functional-Data-Analysis/`) and actively
engaging with the derivations and code, you will:

1.  Grasp the **core concepts of FDA**, understanding how it differs
    from classical statistics by treating observations as smooth
    functions residing in Hilbert spaces.

2.  Learn the difference between **interpolation and smoothing**.

3.  Explore **basis function expansions**, including detailed examples
    of what **Fourier series** and **B-splines** are and how they are
    used to represent discrete data points as continuous curves.

4.  Implement Functional Clustering, walking through an application of
    **Hierarchical Agglomerative Clustering (HAC)** on the price curves
    of DJIA stocks to identify market sectors.

5.  Explore how two widely used numerical methods, **ODE solvers (RKF45)
    and Nonlinear Least Squares (NLS)**, operate at the algorithmic
    level.

6.  Understand modern advances in parameter estimation such as
    **Generalized Profiling (GP)** for systems of nonlinear differential
    equations.

# References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-Blanchard2015" class="csl-entry">

Blanchard, Philippe, and Erwin Brüning. 2015. “Inner Product Spaces and
Hilbert Spaces.” In *Mathematical Methods in Physics: Distributions,
Hilbert Space Operators, Variational Methods, and Applications in
Quantum Physics*, 213–25. Springer International Publishing.
<https://doi.org/10.1007/978-3-319-14045-2_15>.

</div>

<div id="ref-dash2003fast" class="csl-entry">

Dash, M., H. Liu, P. Scheuermann, and K. Tan. 2003. “Fast Hierarchical
Clustering and Its Validation.” *Data & Knowledge Engineering* 44:
109–38. <https://doi.org/10.1016/S0169-023X(02)00138-6>.

</div>

<div id="ref-ferreira2009comparison" class="csl-entry">

Ferreira, Laura, and David B. Hitchcock. 2009. “A Comparison of
Hierarchical Methods for Clustering Functional Data.” *Communications in
Statistics - Simulation and Computation* 38 (9): 1925–49.
<https://doi.org/10.1080/03610910903168603>.

</div>

<div id="ref-Walter2011" class="csl-entry">

Gautschi, Walter. 2011. *Numerical Analysis*. Birkhäuser Basel.
<https://link.springer.com/book/10.1007/978-0-8176-8259-0>.

</div>

<div id="ref-gradshteyn2014table" class="csl-entry">

Gradshteyn, I. S., and I. M. Ryzhik. 2014. *Table of Integrals, Series,
and Products*. Edited by Daniel Zwillinger. 8th ed. Amsterdam: Academic
Press.
<https://www.sciencedirect.com/book/9780123849335/table-of-integrals-series-and-products>.

</div>

<div id="ref-hubert1985comparing" class="csl-entry">

Hubert, Lawrence, and Phipps Arabie. 1985. “Comparing Partitions.”
*Journal of Classification* 2 (1): 193–218.
<https://doi.org/10.1007/BF01908075>.

</div>

<div id="ref-more1978levenberg" class="csl-entry">

Moré, Jorge J. 1978. “The Levenberg-Marquardt Algorithm: Implementation
and Theory.” In *Numerical Analysis*, edited by G. A. Watson,
630:105–16. Lecture Notes in Mathematics. Berlin, Heidelberg: Springer.
<https://doi.org/10.1007/BFb0067700>.

</div>

<div id="ref-muller2022functional" class="csl-entry">

Müller, Hans-Georg. 2022. “Special Issue on ‘Functional and Object Data
Analysis’: Guest Editor’s Introduction.” *Canadian Journal of
Statistics* 50. <https://doi.org/10.1002/cjs.11690>.

</div>

<div id="ref-park2018parameter" class="csl-entry">

Park, Y., L. Reichel, G. Rodriguez, and X. Yu. 2018. “Parameter
Determination for Tikhonov Regularization Problems in General Form.”
*Journal of Computational and Applied Mathematics* 343: 12–25.
<https://doi.org/10.1016/j.cam.2018.04.017>.

</div>

<div id="ref-patrikalakis2000section14" class="csl-entry">

Patrikalakis, Nicholas M., Shin Maekawa, and Takashi Cho. 2009. “Section
1.4: Bspline Curves and Surfaces.”
<https://web.mit.edu/hyperbook/Patrikalakis-Maekawa-Cho/>.

</div>

<div id="ref-Postnikov2016" class="csl-entry">

Postnikov, E. B., and O. V. Titkova. 2016. “A Correspondence Between the
Models of Hodgkin-Huxley and FitzHugh-Nagumo Revisited.” *The European
Physical Journal Plus* 131: 411.
<https://doi.org/10.1140/epjp/i2016-16411-1>.

</div>

<div id="ref-ramsay2007parameter" class="csl-entry">

Ramsay, J. O., Giles Hooker, D. Campbell, and J. Cao. 2007. “Parameter
Estimation for Differential Equations: A Generalized Smoothing
Approach.” *Journal of the Royal Statistical Society: Series B
(Statistical Methodology)* 69 (5): 741–96.
<https://doi.org/10.1111/j.1467-9868.2007.00610.x>.

</div>

<div id="ref-ramsay2001fda" class="csl-entry">

Ramsay, J. O., and B. W. Silverman. 2001. “Functional Data Analysis.” In
*International Encyclopedia of the Social & Behavioral Sciences*, edited
by Neil J. Smelser and Paul B. Baltes, 5822–28. Oxford: Elsevier.
<https://doi.org/10.1016/B0080430767/00434-4>.

</div>

<div id="ref-Ramsay2005" class="csl-entry">

———. 2005. *Functional Data Analysis, 2nd*. New York: Springer.
<https://doi.org/10.1002/0471667196.ess3138>.

</div>

<div id="ref-ramsay2009functional" class="csl-entry">

Ramsay, James O., Giles Hooker, and Spencer Graves. 2009. *Functional
Data Analysis with r and MATLAB*. Use r! New York: Springer.
<https://doi.org/10.1007/978-0-387-98185-7>.

</div>

<div id="ref-rand1971objective" class="csl-entry">

Rand, William M. 1971. “Objective Criteria for the Evaluation of
Clustering Methods.” *Journal of the American Statistical Association*
66 (336): 846–50. <https://doi.org/10.2307/2284239>.

</div>

<div id="ref-7352306" class="csl-entry">

Shahriari, Bobak, Kevin Swersky, Ziyu Wang, Ryan P. Adams, and Nando de
Freitas. 2016. “Taking the Human Out of the Loop: A Review of Bayesian
Optimization.” *Proceedings of the IEEE* 104 (1): 148–75.
<https://doi.org/10.1109/JPROC.2015.2494218>.

</div>

<div id="ref-shampine1986practical" class="csl-entry">

Shampine, Lawrence F. 1986. “Some Practical Runge–Kutta Formulas.”
*Mathematics of Computation* 46 (173): 135–50.
<https://doi.org/10.2307/2008219>.

</div>

<div id="ref-mathworldFourierSeries" class="csl-entry">

Weisstein, Eric W. 2002. “Fourier Series.”
<https://mathworld.wolfram.com/FourierSeries.html>.

</div>

<div id="ref-XU2020337" class="csl-entry">

Xu, Hongyan. 2020. “Chapter 7 - Big Data Challenges in Genomics.” In
*Principles and Methods for Data Science*, edited by Arni S. R.
Srinivasa Rao and C. R. Rao, 43:337–48. Handbook of Statistics.
Elsevier. https://doi.org/<https://doi.org/10.1016/bs.host.2019.08.002>.

</div>

</div>
