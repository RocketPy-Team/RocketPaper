[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Projeto-Jupiter/RocketPaper/blob/main/NDRT_2020_launch_vehicle/NDRT_ROCKETPY.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Projeto-Jupiter/RocketPaper/main?filepath=NDRT_2020_launch_vehicle%2FNDRT_ROCKETPY.ipynb)


## 2020 NDRT Launch vehicle
The contents in this folder regard the comparison between RocketPy's simulations and real flight data.
The rocket analyzed here is the 2020 NDRT Launch vehicle, build by the Notre Dame Rocketry Team (NDRT) and launched in 2020, in The United States (Michigan). 
To know more about NDRT, please follow their website [here](https://ndrocketry.weebly.com/).

## Files description:
- plots/ :
    
      Folder containing two plots created using the current data. 
      The file "Comparison_NDRT_TitleYES.pdf" was actually presented in the final paper.
      
- Cesaroni_4895L1395-P.eng :
    
      An engine file containing the most important information about the Rocket Motor.
     This files was dowloaded from the following website: [thrustcurve.org](https://www.thrustcurve.org/motors/Cesaroni/4895L1395-P/)
    
- NDRT_ROCKETPY.ipynb : 

      Jupyter notebook where the flight simulation was performed.
      The initial cells regarding the google drive mouting can be ignored.
      
- README.md :
    
      Markdown file describing the contents in the present folder.
      
- env_23.nc :

      File containing all the atmospheric details used in the flight simulation.
     This files was dowloaded from the following website: [copernicus](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-pressure-levels?tab=form)
      
- fullscale_2-23_raven1_crop.csv :

      The actual file containing flight data obtained by the avionics system.
      First colunm : Time-Axial Accel (Gs)	
      Second column: Axial Accel (Gs)	
      Third column : bILBA - useless
      Fourth column: Time (s) - Time in seconds
      Fifth column : Altitude (Ft-AGL)- Vertical position (altitude), in feet, measured during the flight
      Sixth column : bILBA - useless
      Apogee at row: 343

## More about the 2020 NDRT Launch vehicle:
The launch vehicle is 134 in. long with a loaded mass of 798 oz. The final motor choice is a Cesaroni L1395, which will allow the vehicle to attain the target altitude of 4,444 ft after launching from a 12 ft 1515 rail. The drogue parachute is a FruityChute CFC-24 and will deploy at apogee, and at 600 ft. the main parachute, a FruityChute Iris Ultra 120 Compact, will deploy. (NOTRE DAME ROCKETRY TEAM FLIGHT READINESS REVIEW)

### Picture or render of the Rocket:
![alt text](https://ndrocketry.weebly.com/uploads/1/3/2/4/132422406/published/output-onlinepngtools-3.png?1592450602)
