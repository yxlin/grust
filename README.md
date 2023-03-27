# grust

A skeleton project aims to build a next version of ggdmc using Rust, C++, R and Python.

This will be a slow moving project to refactor the ggdmc and update it with the time-varying components in the drift rate. The aim is to expand the dynamic component into also the boundary separation and standing points. They will probably from some code that I used in another project (still in the private repository). 

## Main Objectives 
1. Refactor the code in Rust to make the memory usage more efficient (faster Bayesian computation)

2. Create a Python interface to help the Python ethusiastists to enjoy also the wonderful DMC concept.

## Secondary Objectives 
1. Clear up the interwined code struture in the original R and C++ code

2. Apply S4 R interface 

A small experimental part has implemented some S4 interface in "eam", a tentative name given to a private package.

3. Collect some published data in the literature studied in time-varying models.

4. Link to well-known R packages which provide beautifual Bayesian plots.

5. Implement Bayesian Factors in model comparisons in the decision-diffusion, the accumulator, and the dynamic diffusion models.

An experimental version has been implemented also in "eam" for my current work.

6. (Possibly) implement an automated mechanism to do post-predictive model simulation.  

## Tertiary Objectives 
1. Provide a JavaScript and HTML interface to show case interesting cases.
2. Use more the MSVC debugging tool to clear up the C++ structure.  



