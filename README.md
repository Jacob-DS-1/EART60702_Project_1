# Urban Climate Vulnerability: Long-term Trends in Warming, UHI, and Extreme Weather

**Project Overview**
<br>This project investigates the evolution of Urban Heat Island (UHI) intensity and extreme weather events in Northwich, Cheshire (Greater Manchester fringe) from 2006 to 2080. The study assesses urban vulnerability under future high-emission scenarios using daily climate model output.

**Core Research Goals**
<br>Analyze Warming Trends: Evaluate long-term temperature increases from 2006 to 2080.
<br>Quantify UHI Intensity: Measure how urbanization amplifies heat exposure beyond background warming.
<br>Assess Extreme Events: Identify frequency changes in TX90p (extreme heat) and R95p (extreme precipitation).
<br>Evaluate Compound Extremes: Study the growth of concurrent heat and heavy rain events.

**Technical Implementation**
<br>The analysis is executed via Project_1_V4.ipynb using a structured data science pipeline:
<br>Baseline Definition: The period 2006–2035 serves as the reference for calculating extreme thresholds.
<br>Variable Validation: Physical relationships (e.g., Snowfall vs. Temperature) were used to identify key variables like TREFMXAV_U.
<br>Thresholding Method: Monthly percentile-based thresholds (90th for heat, 95th for wet-day rain) are used to capture seasonality.

**Key Findings**
<br>Observed Warming Trends: The data reveals a significant and steady rise in temperatures over the study period, supported by a strong correlation coefficient of r=0.922.
<br>UHI Amplification: Urban Heat Island intensity is projected to increase by +0.35K, suggesting that local urbanization will further exacerbate thermal stress beyond regional warming.
<br>Shift in Extreme Heat: The frequency of TX90p events is expected to more than triple, with extreme heat days potentially reaching ~135 days per year by the late 21st century.
<br>Escalating Compound Risks: We observed a nearly five-fold increase in concurrent heat and precipitation events, which poses a substantial threat to urban infrastructure and drainage systems.

**Environment Requirements**
<br>Language: Python 3.x
<br>Primary Libraries: pandas, numpy, matplotlib, seaborn, scipy, folium.
<br>Dataset: project_1.csv containing 27,374 daily meteorological records.

**Authors：Jacob Woodland, Shiyu Wang, Hanjin Yue**
