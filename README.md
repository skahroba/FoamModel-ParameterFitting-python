# FoamModel-ParameterFitting
Python script to estimate the STARS foam model parameter from experimental data. This is a python adoption of a Julia script written by A.A. Eftekhari, see https://github.com/simulkade/foamparameters.
The optimization solver does not handle the bound constraints very well. It needs to be improved.
Five parameter estimtation includes dryout function and shear thinning function. 
Seven parameter estimation includes surfactant effect function, dryout function and shear thinning function.
