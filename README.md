# Prediction of Gender Unemployment Rates for 2023

## SRC
### Installing / Building the Code
To install the code, download the RMD file in the SRC file. Open this in RStudio and run the code. All of the libraries that need to be installed are already included at the top of the file, so the code solely needs to be ran to successfully build the code. 
### Code Usage
This code can be used for forecasing purposes of a time series data about unemployment. The code can be used to visually see the unemployment rate in 2023 for males and females and validation tables to validate the results. 
## DATA
Our data was obtained from the Bureau of Labor Statistics and can be found [here](https://github.com/mra4t/LIVEMAS-proj1/blob/main/Data/Unemployment.xlsx).
### Data Dictionary
| Column  | Description | Potential Values |
| ------ |  ----------- | ----------------
| Timestamp  | Indicates the month and year for which the unemployment rate is being reported  | Every combination of a month (Jan-Dec), followed by a year (1950-2022).  For 2022, only months Jan-Aug are valid. |
| Male  | Provides the reported unemployment rate amongst males in the United States for the given timestamp | A non-negative percentage between 0 and 100. |
| Female | Provides the reported unemployment rate amongst females in the United States for the given timestamp | A non-negative percentage between 0 and 100. |

## FIGURES

## REFERENCES
[1] [Milestone 1: Creating a Hypothesis](https://docs.google.com/document/d/1at2bhZCavVOYFlX82WuMa91ym0iVsscmdqEKFPdcN-A/edit?usp=sharing)

[2] [Milestone 2: Exploratory Data Analysis & Analysis Plan](https://docs.google.com/document/d/1wKe0dPM4gLki5tGYAPK8kjtGr--3sGUSg0mg04wiEy0/edit?usp=sharing)

[3] A. Biswal, “Time Series forecasting in R: Step-by-step guide with examples [updated],” Simplilearn.com, 12-Jul-2022. [Online]. Available: https://www.simplilearn.com/tutorials/data-science-tutorial/time-series-forecasting-in-r. [Accessed: 21-Sep-2022]. 
