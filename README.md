# grust

A skeleton project aims to build a next version of ggdmc using Rust, C++, R and Python.

This will be a slow moving project to refactor the ggdmc and update it with the time-varying components in the drift rate. The aim is to expand the dynamic component into also the boundary separation and standing points. They will probably from some code that I used in another project (still in the private repository). 

## Main Objective One
Refactor the code in Rust to make the memory usage more efficient (faster Bayesian computation)

## Main Objective Two
Create a Python interface to help the Python ethusiastists to enjoy also the wonderful DMC concept.

## Secondary Objective One
Clear up the interwined code struture in the original R and C++ code

## Secondary Objective Two
Apply S4 R interface 

A small experimental part has implemented some S4 interface in "eam", a tentative name given to a private package.

## Secondary Objective Three
Collect some published data in the literature studied in time-varying models.

## Secondary Objective Four
Link to well-known R packages which provide beautifual Bayesian plots.

## Secondary Objective Five
Implement Bayesian Factors in model comparisons in the decision-diffusion, the accumulator, and the dynamic diffusion models.

An experimental version has been implemented also in "eam" for my current work.

## Secondary Objective Six
(Possibly) implement an automated mechanism to do post-predictive model simulation.  






