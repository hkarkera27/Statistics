# Analysing Rainfall in India

## Objective 

Using the data recorded for Rainfall in India from 1901 to 2017 we plot various visualizations to draw suitable conclusions about the rainfall pattern. 
With the help of these visualizations, we go on to test various hypothesis and predict the annual rainfall using linear regression.

## Data Description

The rainfall data is obtained from https://data.gov.in/ which is an open government data platform. It presents details on the amount of rainfall received (in mm) by various Subdivisons in India for the period of 1901 - 2017.
Below is the description of the variables in the dataset:
1) SUBDIVISION: Represents the 36 subdivisions of India.
2) Year: The period for which rainfall is recorded.
3) The next 12 columns (JAN, FEB-NOV, DEC) represent the amount of rainfall received in the 12 months in a year.
4) ANNUAL: The annual rainfall received by a subdivision in a particular year.
5) JF: The amount of rainfall received in January & February.
6) MAM: The amount of rainfall received in March, April & May.
7) JJAS: The amount of rainfall received in June, July & August.
8) OND: The amount of rainfall received in October, November & December

### Programming Language : R
### Libraries used : tidyverse, ggplot2, ggthemes, PerformanceAnalytics, fitdistrplus, graphics, stats
