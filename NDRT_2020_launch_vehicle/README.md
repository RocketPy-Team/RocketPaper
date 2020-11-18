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
      In the future, authors may change some lines to include integration with google collab directly from Github.
      
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
      Max velocity at row: 
      Apogee at row: 
      Impact at row:     

## More about the 2020 NDRT Launch vehicle:


### Picture or render of the Rocket:
- Optional
