## Bella_Lui_Kaltbrunn
The contents in this folder regard the comparison between RocketPy's simulations and real flight data.
The rocket analyzed here is the Bella Lui, a launch vehicle build by the EPFL Rocket Team (ERT) launched in 2020, in Switzerland. 
To know more about ERT, please follow their website [here](https://epflrocketteam.ch).

## Files description:
- graphs/ :
    
      Folder containing two plots created using the current data. 
      The file "Comparison_EPFL_TitleYES.pdf" was actually presented in the final paper.
      
- AeroTech_K828FJ.eng :
    
      An engine file containing the most important information about the Rocket Motor.
     This files was dowloaded from the following website: [thrustcurve.org](https://www.thrustcurve.org/motors/AeroTech/K828FJ/)
    
- ERT_KaltBrunn_avionics_clean.csv :

      The actual file containing flight data obtained by the avionics system.
      First colunm : Index - used to account for the time in seconds
      Second column: Time not in seconds - time registered by the eletronics sensors
      Third column : Time in seconds - time converted to seconds
      Fourth column: Vertical position (altitude), in meters, measured during the flight    
      Fifth column : Vertical velocity, in meter/second, measured during the flight
      Max velocity at row: 35
      Apogee at row: 179-180
      Impact at row: 574

- ERT_KaltBrunn_avionics_clean.xlsx :

      The Microsoft Excel file used to generate the .csv file with the same name.
      It provides an alternative method to create and plot graphs from these flight data.

- Kaltbrunn_RocketPy_simulation_AVIONICS_clean.html :

      Simple report created when the authors finished the flight analysis.
      It was created by exporting and converting the Jupiter Notebook below.

- Kaltbrunn_simulation.ipynb : 

      Jupyter notebook where the flight simulation was performed.
      The initial cells regarding the google drive mouting can be ignored.
      In the future, authors may change some lines to include integration with google collab directly from Github.
    
- README.md :
    
      Markdown file describing the contents in the present folder

## More about the Bella Lui Kaltbrunn mission:
Bella Lui is a modern and robust rocket made by the EPFL Rocket Team (ERT) in 2019.
Since that date, several missions were performed by making some adjustments in the vehicle.
One of this misson was the lauch of 22th february 2020 in Kaltbrunn (SWI). Kaltbrunn is actually a municipality in Switzerland.

### Picture or render of the Rocket:
- ~Optional~
