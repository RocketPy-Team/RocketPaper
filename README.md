[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4279967.svg)](https://doi.org/10.5281/zenodo.4279967)
![GitHub repo size](https://img.shields.io/github/repo-size/Projeto-Jupiter/RocketPaper)

# RocketPaper
This repository holds all the data used for the article **[RocketPy: A Six Degree-of-freedom Rocket Trajectory Simulator](https://doi.org/10.1061/(ASCE)AS.1943-5525.0001331)**, an article that has been published in the Journal of Aeroespace Engeneering at 08/20/2021

### How to cite the paper: 
    @article{ceotto_schmitt_alves_pezente_carmo_2021, 
        title={RocketPy: Six Degree-of-Freedom Rocket Trajectory Simulator}, 
        volume={34}, 
        DOI={10.1061/(asce)as.1943-5525.0001331}, 
        number={6}, 
        journal={Journal of Aerospace Engineering}, 
        author={Ceotto, Giovani H. and Schmitt, Rodrigo N. and Alves, Guilherme F. and Pezente, Lucas A. and Carmo, Bruno S.}, 
        year={2021}, 
        month={Aug}}

### Authors
[Giovani Hidalgo Ceotto](https://orcid.org/0000-0002-1614-3028), 
[Rodrigo Nascente Schmitt](https://orcid.org/0000-0001-7047-1092), 
[Guilherme Fernandes Alves](https://www.linkedin.com/in/guifalves/), 
[Lucas Azevedo Pezente](https://github.com/lucasfourier), 
Prof. [Bruno Souza Carmo](https://orcid.org/0000-0002-2486-7026).

### Article's abstract
RocketPy is a new open-source Python library specialized in trajectory simulations of sounding rockets and high-powered rockets. Having a modular structure and being built on top of a six degree-of-freedom flight dynamics model that includes detailed mass variation effects, RocketPy allows for accurate trajectory prediction of different rocket configurations. Additionally, weather data from several meteorological agencies, such as reanalysis, forecasts, and ensembles, are an innovative feature directly integrated into the library, providing precise information about atmospheric conditions for each simulation. The software was successfully validated for three rockets developed by different universities, with apogee predictions showing deviations of the order of 1% when compared to actual flight data. Furthermore, due to its modular nature, RocketPy can be easily employed in optimization studies and Monte Carlo analyses. The latter was a key aspect of this work, enabling the calculation of landing dispersion ellipses based on input uncertainties. Since running several Monte Carlo analyses is computationally expensive, a new algorithm was proposed to significantly speed up results based on rejection sampling. The code described here and made available online enhances the state of the art represented by several widely used software and can serve as a framework for future research on rocket dynamics, control, flight optimization, and dispersion analysis.

### Acknowledgments
The authors of this work would like to thank the Notre Dame Rocket Team and the École polytechnique fédérale de Lausanne Rocket Team for granting access to their data. We are also thankful for Escola Politécnica of the University of Sao Paulo, for the opportunity to develop this study, and for all the members of Project Jupiter that contributed towards making RocketPy the current robust software.
