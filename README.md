# Hybrid Renewable Energy System Modelling & Analysis


## Description
This analysis aims to find the optimum setup of renewable energy facilities in terms of wind turbines, photovoltaics, and storage capacity in two different US locations (Traverse, Michigan and Tucson, Arizona).

## Goals
- Developing a MATLAB model to simulate a hybrid renewable energy system in the two locations to identify cost-effective solutions that maximize renewable energy use in each location.
- Investigating the system's performance metrics (coverage ratio, residual load, unused energy, supply-demand mismatch) based on weather data and load profile.
- Calculating the LCOE and developing scenario analysis to assess the optimum system setting.

## Key Findings

#### Traverse, Michigan
- The optimal setup of PV panels for the given location and available surface area was considered. It was found that at an elevation angle of up to 15°, an irradiance of 120 kWh/m² could be achieved for all azimuth angles. Increasing the elevation angle to accommodate more panels would result in lower irradiance.
<img src="Irradiance in Traverse.jpg">

- The optimal mix of PV panels, wind turbines, and storage capacity was determined based on coverage ratio and economic analysis. It was found that 12 wind turbines without PV panels could achieve a coverage ratio of 60%, and each additional turbine increased the coverage ratio by 1%. This information, along with load and time-of-day data, was used to identify the most suitable combination of components.
<img src="CR%20vs.%20PV%20%40WT%20-%20Traverse%2C%20Michigan.jpg">


#### Tucson, Arizona
- The optimal setup of PV panels for the given location and available surface area was considered. It was found that at an elevation angle of up to 15°, irradiance of 180 kWh/m² could be achieved for all azimuth angles. Increasing the elevation angle to 45° at azimuths from 0-45° could achieve 200 kW/m². This suggests that Tucson has better geographical conditions for power yield and flexibility compared to Traverse.
<img src="Irradiance in Tucson.jpg">

- It was found that 19 turbines were sufficient to achieve around 60% coverage ratio at the given location. Adding more turbines provided minimal increase in coverage. Traverse was concluded to be geographically better than Tucson in terms of wind power yield and flexibility.
<img src="CR%20vs.%20PV%20%40WT%20-%20Tucson%2C%20Arizona.jpg">


## Key Result

The optimum setup for the number of wind turbines, PV elements, and storage capacity can achieve a reasonable coverage ratio of 66-70% and LCOE of 0.12 €/kWh, equivalent to that of a conventional electricity power plant.

## Final Thoughts
- The ENERCON E-115 wind turbine was chosen for its power output and efficiency, which helped reduce wind shear and turbulent flow. While installation costs were high, the LCOW was acceptable. Other turbines had either too much unused energy or high installation costs.
- The chosen PV elements were found to have relatively low power output compared to the wind turbines and their costs. Despite this, a PV facility was considered to contribute to the coverage ratio on days with no wind or significant irradiance. It was suggested that the PV elements should be replaced with more efficient ones, especially in Tucson due to its higher irradiance than Traverse.
- The storage system was limited by installation costs, which negatively affected the LCOE. Technological advancements in electricity storage were expected to allow for better utilization of unused energy. Mechanical storage and consumer household storage versus utility-scale storage were suggested for further feasibility and economic analysis.
