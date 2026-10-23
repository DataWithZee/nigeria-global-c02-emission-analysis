Nigeria and Global CO₂ Emissions: Trends and Comparisons

Project Overview

This project explores historical carbon dioxide (CO₂) emissions data to understand how emissions have changed over time in Nigeria and how Nigeria compares with selected African countries and the global total.

The analysis examines total CO₂ emissions, emissions per capita, changes over time, and the relationship between population and emissions. It uses Python to inspect, prepare, analyse and visualise the data.

Research Questions

* How have Nigeria’s CO₂ emissions changed over time?
* How does Nigeria compare with Ghana, South Africa and Kenya?
* How do total emissions compare with emissions per capita?
* What patterns and limitations can be identified in the data?

Tools and Technologies

* Python
* JupyterLab
* pandas
* NumPy
* Matplotlib
* Seaborn

Dataset

The data comes from Our World in Data’s CO₂ and Greenhouse Gas Emissions dataset.

Source: [https://catalog.ourworldindata.org/emissions/owid_co2/](https://catalog.ourworldindata.org/emissions/owid_co2/)

The analysis focuses on Nigeria, Ghana, South Africa, Kenya and the World aggregate. The available time periods differ between countries.

Key Findings

* Nigeria’s total CO₂ emissions increased substantially over the long term, although the trend included periods of decline.
* Nigeria’s total emissions rose from approximately 110.5 million tonnes in 2015 to 135.8 million tonnes in 2024.
* Nigeria’s emissions per capita remained comparatively low, at approximately 0.58 tonnes per person in 2024.
* South Africa recorded higher average total emissions and emissions per capita than the other selected African countries.
* The analysis found a strong association between population and total CO₂ emissions. This relationship does not establish causation.

Data Quality and Limitations

The dataset contains missing values, particularly in GDP and emissions-related variables. Missing values were not automatically replaced with zero. Rows missing a variable required for a particular analysis were excluded from that analysis.

The analysis focuses on CO₂ emissions rather than all greenhouse gases. Country comparisons are also affected by differences in the available historical periods. Correlation results indicate association, not causation.

Project Files

* co2_emissions_analysis.ipynb — the Jupyter Notebook containing the data preparation, analysis, visualisations and findings.
* owid_co2.csv — the original dataset used for the analysis.
* output/ — the folder for exported charts and analysis results, where available.

Reproducing the Analysis

1. Download or clone this repository.
2. Install Python and the required libraries: pandas, NumPy, Matplotlib and Seaborn.
3. Ensure owid_co2.csv is available at the path expected by the notebook.
4. Open co2_emissions_analysis.ipynb in JupyterLab.
5. Run the notebook cells in order.

Conclusion

This project uses historical data to explore Nigeria’s CO₂ emissions trends and compare them with selected countries and the global total. Examining both total emissions and emissions per capita provides a broader perspective on the differences between countries and highlights the importance of considering data coverage and analytical limitations.
