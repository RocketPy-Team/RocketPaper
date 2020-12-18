[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Projeto-Jupiter/RocketPaper/blob/main/Valetudo_RocketPy/Valetudo_Monte_Carlo_Dispersion_Analysis.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Projeto-Jupiter/RocketPaper/main?filepath=Valetudo_RocketPy%2FValetudo_Monte_Carlo_Dispersion_Analysis.ipynb)


## Valetudo_RocketPy

The contents in this folder regard the Valetudo flight simulations using [RocketPy](https://github.com/Projeto-Jupiter/RocketPy). 
The software version 0.9.6 was used, and the simulations presented here include a Monte Carlo analysis.

### Files description:

- Cd_PowerOff.csv :

      Valetudo's drag coefficient (axial) as a function of mach number, considering that the motor is not burning.

- Cd_PowerOn.csv :

      Valetudo's drag coefficient (axial) as a function of mach number, considering that the motor is burning.

- LASC2019_Reanalysis.nc :

      File containing all the atmospheric details used in the flight simulation.

- README.md :

      Markdown file describing the contents in the present folder

- Valetudo_Monte_Carlo_Dispersion_Analysis.ipynb :

      Jupyter notebook used for performing both single flight and Monte Carlo simulations.

- Valetudo_basemap_final.png :

      Picture of the Basemap used in the simulations' results.
      At center is the launch pad location.
      The red circle has its radius equals to 1km.

- environment_valetudo.ipynb :
      
      Jupyter notebook used to create plots regarding the Atmospheric conditions used in the paper.

- valetudo_ROCKETPY_CFD.csv :

      Data exported from rocketpy's main simulation.

- valetudo_reanalysis.valetudo_disp_in.txt : 

      The input of each simulation performed for the Monte Carlo analysis.

- valetudo_reanalysis.valetudo_disp_out.txt :

      The ouput of each simulation performed for the Monte Carlo analysis.
      
- valetudo_weather_atmospheric_new.pdf  and  valetudo_weather_ensemble_new.pdf:

      Plots created using the 'environment_valetudo.ipynb' jupyter notebook
      
