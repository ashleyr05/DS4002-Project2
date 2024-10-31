# DS4002-Project2

Goal of this project

This repository includes this README file to explain the purpose and function of our repository, as well as a LICENSE file with the MIT license to explain the terms of use of our repository.

There is a SCRIPTS folder that contains all of the source code files for our project. There is a DATA folder that contains all of the data for this project, and there is an OUTPUT folder that contains all of the visualizations generated in our project.

## Software and Platform
### Types of software used
  Visual Studio Code
  
### Packages installed
  Python, Jupyter, Pandas, Seaborn, Matplotlib, Numpy
### Platforms
  Windows and Mac

## Map of Documentation
### DATA Folder
- agriculture_workers_percent_of_employment.csv
- child_mortality_0_5_year_olds_dying_per_1000_born.csv
- children_per_woman_total_fertility.csv
- exports_percent_of_gdp.csv
- gdp_total_yearly_growth.csv
- industry_workers_percent_of_employment.csv
- lex.csv
- owid_education_idx.csv
- service_workers_percent_of_employment.csv
- final_data.csv
- DataAppendix.pdf
### OUTPUT Folder
- corr chart dev.png
- corr nondev.png
- GDP growth.png
- Industry worker %.png
### SCRIPTS Folder
- Corr Charts.ipynb
- data_cleaning.ipynb
- PivotCharts.xlsx

### LICENSE.md File

### README.md File

## Instructions for Reproducing Results

To reproduce the results of our project:

1) Clone this repository from GitHub
2) Open this repository in Visual Studio Code
3) Install Python and Jupyter in Visual Studio Code
4) If you wish to get final_data.csv on your own, download agriculture_workers_percent_of_employment.csv, child_mortality_0_5_year_olds_dying_per_1000_born.csv, children_per_woman_total_fertility.csv, exports_percent_of_gdp.csv, gdp_total_yearly_growth.csv, industry_workers_percent_of_employment.csv, lex.csv, owid_education_idx.csv, and service_workers_percent_of_employment.csv and run data_cleaning.ipynb
5) Run Corr Charts.ipynb to get correlation charts of the variables segmented by developed and developing nations
6) View PivotCharts.XLSX in SCRIPTS to get the excel file and pivot tables used to create 2 of the graphs used in presentation
7) Run P2 Analysis.ipynb to replicate the SARIMAX model

## References
[1]Gapminder, “Gapminder: Unveiling the beauty of statistics for a fact based world view.,” Gapminder.org, 2023. https://www.gapminder.org/
[2]Scikit-learn, “Scikit-learn: Machine Learning in Python,.” Scikit-learn.org, 2023. https://scikit-learn.org/stable/
[3]United Nations, “List of LDCs | Office of the High Representative for the Least Developed Countries, Landlocked Developing Countries and Small Island Developing States,” www.un.org, 2023. https://www.un.org/ohrlls/content/list-ldcs
[4]World Population Review, “Developed Countries List 2020,” worldpopulationreview.com, 2022. https://worldpopulationreview.com/country-rankings/developed-countries
[5]Minitab, ”Modified Box-Pierce (Ljung-Box) Chi-Square Statistic” support.minitab.com, 2023.https://support.minitab.com/en-us/minitab/help-and-how-to/statistical-modeling/time-series/how-to/arima/interpret-the-results/all-statistics-and-graphs/modified-box-pierce-ljung-box-chi-square-statistics/#:~:text=multiples%20of%2012.-,Interpretation,for%20each%20chi%20square%20statistic.
[6] Datascientest, “SARIMAX: What is It?” datascientest.com, 2023. https://datascientest.com/en/sarimax-model-what-is-it-how-can-it-be-applied-to-time-series
[7] Statsmodels, “SARIMAXResults.testheteroskedasticity” statsmodels.org, 2021.https://www.statsmodels.org/dev/generated/statsmodels.tsa.statespace.sarimax.SARIMAXResults.test_heteroskedasticity.html#statsmodels.tsa.statespace.sarimax.SARIMAXResults.test_heteroskedasticity
