### BUSINESS UNDERSTANDING

Improving traffic safety is a significant concern for any large city. In 2018, the U.S. alone saw 36,560 fatalities related to car crashes. To address and reduce these fatalities, initiatives like Vision Zero have been launched. Cities such as New York and Chicago have adopted this initiative to enhance traffic safety. The fundamental principle of Vision Zero is that traffic crashes are preventable, and even one fatality is too many.

The goal of this project is to create a predictive model that can analyze the primary causes of car crashes. An accurate model can help city authorities take effective measures to prevent crashes. By understanding the reasons behind accidents, cities can strategize and implement targeted actions to reduce the occurrence of such incidents. In this project, I will analyze car crash data from Chicago to develop a predictive model for the causes of crashes and identify trends in these incidents.

### PROBLEM STATEMENT
in Chicago city many car accidents are occuring hence there is need to investigate the cause. I am tasked to build a model to predict the primary contributory cause of a car accident, given information about the car, the people in the car, the road conditions as data analysis is an essential activity for the city management, the police and the residents to learn how to mitigate the accidents.

### OBJECTIVES
The main Objective of this dataset is to:

a) Investigate the primary cause of the road accidents

b) To investigate the correlation between different causes of road accidents.

### DATA UNDERSTANDING
The Traffic Crashes data comes from the Chicago Data Portal, an open data source maintained by the city of Chicago. The dataset contains all traffic crashes that were reported by the police within the city limits. Linked to the crash dataset are two datasets corresponding to Vehicles and Persons involved in the crash. Each crash incident has a unique crash record ID and report number associated with it, which allows for cross-referencing on the dashboards provided for the datasets.

The Crashes dataset contains a number of details related to the incident, such as location/time information, conditions of the road and traffic safety device functionality. The most important detail available is the primary contributory cause for the crash as determined by the office who reported the crash. A link to the main dataset can be found here: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

### MODELLING
I used logistic regression, decision trees and K-Nearest Neighbors. K-Nearest Neighbours was our best performing model.

### Discussion and Conclusions
In conclusion, my best  model was done with K_Nearest_Neighbors run with selected key features resulting in an accuracy score of 87%. These features were DEVICE_CONDITION, WEATHER_CONDITION, LIGHTING_CONDITION, ROADWAY_SURFACE_COND, CRASH_DAY_OF_WEEK. 

### RECOMMENDATIONS
After Analysis of this dataset we have come up with the following recommendations:

a) Educate the masses on road safety measures.

b) Encourage drivers to take actions that prevent accidents.

c) People should be discouraged from driving during bad weather conditions

d) People should be discouraged from using faulty vehicles.

e) Encourage the male gender and the young people to be careful in their driving.

