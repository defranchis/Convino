The Convino program allows to combine measurements obtained with simultaneous nuisance parameter fits. These are performed by fitting a model as a function of the parameters of interest and its uncertainties to the measured data. As a result of such a measurement, the uncertainties are correlated among each other and receive constraints from the data as well as from prior assumptions. The best approach for a combination of these measurement would be the maximization of a combined likelihood. To define this likelihood, the full fit model used for each measurement and the original data is required. Only in rare cases, this information is publicly available. The Convino program models a likelihood equivalent to the combined likelihood based on the public result and its covariance or Hessian, only. It provides a text-based user interface alongside a C++ interface. The latter also integrates ROOT histogram and graph classes for simple combination of binned measurements such as differential cross sections. The program is not limited to measurements obtained with simultaneous nuisance parameter fits

For a complete description of the method and the program, see [1].

The manual can be found in the directory “docu”.

[1] J. Kieseler, "A new method and program for the combination of measurements obtained with simultaneous nuisance parameter fits", to appear
