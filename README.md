# Thesis

Here you can find the Notebooks developed in Mathematica 11.0 for my Ph.D. thesis and other resources.

- We use the [FeynArts and FeynCalc](https://feyncalc.github.io) packages to generate the diagrams and amplitudes.
- For more references about the work, you can read the [Abstract](https://github.com/CarolinaPerdomo/Thesis/blob/20a39403768529fee19db489173bd88e4d053dca/Abstract.pdf) and see the [slides](https://github.com/CarolinaPerdomo/Thesis/blob/20a39403768529fee19db489173bd88e4d053dca/thesis_Carolina_slides.pdf) used in the defense. As I am still preparing the final version of the text with the corrections of the jury and the article in progress, I do not place the final version of the text here.
- The notebooks need to be downloaded and have the corresponding packages downloaded to run them

###  For the electron correction in 2-loop QED:

- The divergent part of the amplitudes is evaluated using the regularization process known as Implicit Regularization (IREG).
- The final 1-loop and 2-loop results for this divergent integrals with IREG can be found [here](https://github.com/CarolinaPerdomo/Thesis/blob/20a39403768529fee19db489173bd88e4d053dca/Integrals_Results.pdf).

### For the electron correction at 1-loop order:

- We also calculate the integrals with finite results. For this, we use [Package-X](https://www.sciencedirect.com/science/article/abs/pii/S0010465517301297?via%3Dihub). Those notebooks and notes can be found in this repository as well.

###  About IREG:
- For more reference on how to apply the IREG method, you can check our articles ["Two-loop renormalisation of gauge theories in 4D Implicit Regularisation: transition rules to dimensional methods"](https://link.springer.com/article/10.1140/epjc/s10052-021-09259-6), ["A Brief Review of Implicit Regularization and Its Connection with the BPHZ Theorem"](https://www.mdpi.com/2073-8994/13/6/956), and ["Two-loop renormalisation of non-Abelian gauge theories in 4D Implicit Regularisation"](https://pos.sissa.it/398/725).
- Basically, IREG is a method where divergent integrals are solved in 4-dimensions and the divergent part of the integral is isolated in the form of what we call a "Basic Divergent Integral" (BDI) that does not need to be solved explicitly. This integral does not depend on physical parameters such as mass or external momentum.

### About regularization methods in general:
- I recommend reading these great articles in [1-looop](https://link.springer.com/article/10.1140/epjc/s10052-017-5023-2) and [2-loops](https://link.springer.com/article/10.1140/epjc/s10052-021-08996-y).
