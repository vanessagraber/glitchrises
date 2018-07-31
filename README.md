# Glitch rises as a test for rapid superfluid coupling in neutron stars

This repository provides two Jupyter notebooks and accompanying files to recreate the results and plots of [Graber et al. (2018)](http://arxiv.org/abs/1804.02706). Please cite Graber et al. (2018) as well as [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1324469.svg)](https://doi.org/10.5281/zenodo.1324469) when using this material

## Description

The Jupyter notebook `rapid_crust_coupling.ipynb` contains code to integrate the TOV equations for a specific neutron star crust model and calculate the mutual friction coefficients as a function of cylindrical radius and relative mass fraction. It subsequently allows numerical integration of a simple three-component neutron star toy model, providing the time evolution of the angular velocities, to determine the characteristic shape of the glitch rise of a Vela-like pulsar. A preliminary comparison between these theoretical predictions and the first single-pulse radio observations by [Palfreyman et al. (2018)](https://www.nature.com/articles/s41586-018-0001-x) as discussed in Section 5 of Graber et al. (2018) is provided in the Jupyter notebook `data_comparison.ipynb`.

The file `microscopic_parameters.txt` contains the microscopic parameters for the inner crust as given in Table 1 of Graber et al. (2018). Moreover, `41586_2018_1_MOESM1_ESM.csv` consists of the data for the observed glitch provided by Palfreyman et al. (2018), whereas the files `model_residuals_Bcore5e-5.txt` and `model_residuals_Bcore_comparison.txt` contain the corresponding predictions as obtained from theoretical models.

We also provide the environment file that has been used to create our results. It can be installed by running `conda env create -f environment.yaml`
and has been tested under Linux, Mac OS and Microsoft. Please contact the author if you have any problems.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
