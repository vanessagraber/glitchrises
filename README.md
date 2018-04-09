# Rapid crust coupling and glitch rises in superfluid neutron stars

---

This repository provides a Jupyter notebook and accompanying files to recreate the results and plots of [Graber et al. (2018)](http:).
Please cite Graber et al. (2018) when using this material.

## Description

The Jupyter notebook `rapid_crust_coupling.ipynb` contains code to integrate the TOV equations for a specific neutron star crust model and calculate the mutual
friction coefficients as a function of cylindrical radius and relative mass fraction. It subsequently allows numerical integration of a simple three-component
neutron star toy model, providing the time evolution of the angular velocities, to determine the characteristic shape of the glitch rise of a Vela-like pulsar.

The file `microscopic_parameters.txt` contains the microscopic parameters for the inner crust as given in Table 1 of Graber et al. (2018).

We also provide the environment file that has been used to create our results. It can be installed by running `conda env create -f environment.yaml`
and has been tested under Linux, Mac OS and Microsoft. Please contact the author if you have any problems.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
