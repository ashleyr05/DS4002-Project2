# DS4002-Project2

This project looks at whether social media sentiment or team performance is a better predictor of a college football team being televised on a flagship network.

This repository includes this README file to explian the purpose and function of our repository, as well as a LICENSE file with the MIT license to explain the terms of use of our repository.

There is a SCRIPTS folder that contains all of the source code files for our project. There is a DATA folder that contains all of the data for this project, and there is an OUTPUT folder that contains all of the visualizations generated in our project.

## Software and Platform

Types of software used
Visual Studio Code
Packages installed
Python, Jupyter, ipykernel, NLTK package in Python
Platforms
Windows and Mac
Map of Documentation

### DATA
CFB_Analysis_Data.csv
CollegeFootballData.csv
DataAppendix.pdf
P1_Reddit_Data.csv
P1_Reddit_Data_Flair_Analysis.csv
### OUTPUT
Correlation Visualization.png
Elo Scores and Network.png
RecordVariablesCorrelationMatrix.pdf
### SCRIPTS
CollegeFootball.ipynb
Correlation Plot Code.ipynb
Elo and Flagship Network Plot.ipynb
P1_Reddit.ipynb
P1_Reddit_Analysis.ipynb
P1_data_tinkering.ipynb
probit.py
### LICENSE.md
MI4-Project1-Goats.pdf
### README.md

## Instructions for Reproducing Results

To reproduce the results of our project

Clone this repository from GitHub
Open this repository in Visual Studio Code
Install Python and Jupyter in Visual Studio Code
If you wish to get CFB_Analysis_Data on your own, run P1_Reddit.ipynb, P1_Reddit_Analysis.ipynb, and P1_data_tinkering.ipynb in order, using the output of each one in the next one
Download CFB_Analysis_Data.csv and copy the file path, and replace the file path in the code with your file path
Run probit.py in SCRIPTS in order to run the regression.
Correlation Plot Code.ipynb outputs correlation visualization to show multicollinearity between data
Run Elo_and_Flagship_Network_Plots.ipynb to get the violin plots on home and away elo ratings by flagship network
