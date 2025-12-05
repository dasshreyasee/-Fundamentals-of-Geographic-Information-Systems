---
title: Low-Income Areas & Schools Near Landfills (Los Angeles)
layout: default
---

<h1 align="center">Low-Income Areas with Schools Near Landfills </h1>
<h3 align="center">Los Angeles County GIS Analysis</h3>


## The Project
In this project, we examined the presence of methane-producing landfills near schools in low-income areas. The objective was to inform policymakers and school districts on how this could have serious health and environment risks, especially for children in these schools. Using GIS tools, we identified eight census tracts in District 1 where schools are located within 0.5 kilometers of methane-emitting landfills, and found that all of these tracts fall below the median income per capita (≤ $23, 674). This spatial pattern highlights the overlap between environmental hazards and socioeconomic vulnerability, showing that low-income families bear a disproportionate share of these externalities. Children living and attending school in these neighborhoods face elevated risks to respiratory health and cognitive development, which can translate into long-term educational and economic disadvantages. This map illustrates where environmental justice concerns are most concentrated and where targeted policy interventions may have the greatest impact.

## Map
<p align="center">
  <img src="LA Low-Income Areas with Schools Near Landfills.png" alt="Map of low-income areas and schools near methane landfills in Los Angeles" width="900">
</p>

## GIS Tools & Skills Used
- Created a 0.5 km buffer around methane-producing landfills  
- Selected schools within the City of Los Angeles  
- Used spatial joins to identify schools within buffer zones  
- Identified census tracts containing these schools  
- Filtered those tracts to the bottom 50% of income per capita  
- Retrieved supervisorial district (sup_district) attributes for final analysis  
