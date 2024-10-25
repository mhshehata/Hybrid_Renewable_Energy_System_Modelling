# Hybrid Renewable Energy System Modelling & Analysis


## Description
This analysis aims to find the optimum setup of renewable energy facilities in terms of wind turbines, photovoltaics, and storage capacity in two different US locations (Traverse, Michigan and Tucson, Arizona).

## Goals
- Developing a MATLAB model to simulate a hybrid renewable energy system in the two locations to identify cost-effective solutions that maximize renewable energy use in each location.
- Investigating the system's performance metrics (coverage ratio, residual load, unused energy, supply-demand mismatch) based on weather data and load profile.
- Calculating the LCOE and developing scenario analysis to assess the optimum system setting.

## Key Findings

#### Traverse, Michigan

<img src="Irradiance in Traverse.jpg">

<img src="CR%20vs.%20PV%20%40WT%20-%20Traverse%2C%20Michigan.jpg">


#### Tucson, Arizona
<img src="Irradiance in Tucson.jpg">

<img src="CR%20vs.%20PV%20%40WT%20-%20Tucson%2C%20Arizona.jpg">

#### Specific Investment Cost (SIC):

Electrolysis has a significantly higher SIC (1000 €/kW) compared to steam-methane reforming (530 €/kW). This suggests that the initial capital investment required for electrolysis is substantially greater.

#### Levelized Cost of Hydrogen (LCOH):

Electrolysis also has a higher LCOH (30 cent€/kWh) than steam-methane reforming (7.5 cent€/kWh). This indicates that the overall cost of producing hydrogen over its lifetime is significantly lower for steam-methane reforming.

#### CO₂ Emissions:

Electrolysis produces significantly lower CO₂ emissions (11.5 Mn tCO₂e) compared to steam-methane reforming (5.8 Mn tCO₂). This makes electrolysis a more environmentally friendly option.

### Implications:

#### Cost vs. Environmental Impact:
The choice between these two methods involves a trade-off between cost and environmental impact. Steam-methane reforming offers a lower cost but has higher emissions, while electrolysis has higher costs but lower emissions.

#### Technological Advancements: 
As technology advances, the costs and efficiencies of both methods may change. Future developments could potentially reduce the cost gap between electrolysis and steam-methane reforming.

#### Policy and Market Factors: 
Government policies, market demand, and the availability of renewable energy sources can also influence the choice between these methods. For example, incentives for renewable energy can make electrolysis more economically attractive.

---------------------------------------------------------------

<img src="RES_CO2.PNG">

### Key Result

The optimum setup in terms of the number of wind turbines, PV elements, and storage capacity can achieve a reasonable coverage ratio of 66-70% and LCOE of 0.12 €/kWh, which is equivalent to that of a conventional electricity power plant.

## Final Thoughts
- The ENERCON E-115 wind turbine was chosen for its power output and efficiency, which helped reduce wind shear and turbulent flow. While installation costs were high, the LCOW was acceptable. Other turbines had either too much unused energy or high installation costs.
- The chosen PV elements 
