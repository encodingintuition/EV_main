# Electric Vehicles - Main 
This repository is an aggregation of Electric Vehicles projects. 

#### -- Project Status: [in-process]

## Problem Definition and Motivation
Electric Vehicles are showing up in US driveways in more significant numbers, maybe due to the growing awareness of the climate crisis and/ or monetary incentives. In addition, with the ever-increasing development and use of renewable energy, EVs are critical for individuals to lower their carbon footprint and disrupt the held energy model.  With the power grid being a hundred years old, EVs will be key elements in the evolving DER systems of the future. 

#### Objective of this collection of Projects
1. Understand the physical technology and datasets of EVs.
2. Forecast the load addition load the EVs place on the current electical grid.
3. Innovate in data architectures and methodologies to help forecast and load balance electric grids through the energy transition.


#### Brainstormed Questions 

Vehicles behavor 
- How many vehicles are registered? (veh)
	- only a percentage of the registered vehicles are on the road per day or at a section of time. 
- How many vehicles are on the road daily? (veh-daily )
- How many miles does a vehicle drive per day? (veh-daily-miles)
- At what times does the vehicle drive? (veh-daily-time)
- What geographical routes do these vehicles travel? (veh-daily-routes)
- What was the function of the traveling vehicle(veh-daily-ref)

EVs 
- What is the electrical consumption of EV per mile kWh? (EV-mpkWh)
- How long does it take for an EV to charge, per kWh per connection type? (station-kWhperMin) 
- What times are the EVs being charged? (station-kWhpermin-time)
- Where are EVs being charged? (station-kWhpermin-time-GIS)
- How long is an EV left plugged-in after charging is complete? (station-chargecomplete--pluggedcomplete)
- be plugged in to be charged per connection
-Geographic distribution of commercial charging stations and EV owner's home charging stations? (station-GIS = commercial station-GIS & homeChargingStation-GIS)
    