# Mock-Census-Data-Analysis-for-Town-Development-Planning
This repository contains extensive data cleaning and exploratory data analysis of a mock census dataset for a hypothetical modest town. The town, positioned between two cities, possesses an empty plot of land awaiting purposeful utilization. The main objective of this project is to analyze the demographic, socio-economic, and other relevant characteristics of the town's population to identify optimal investment and development strategies for this land. Insights from this data-driven approach can guide decision-making processes for the town's future development.
# Resources
Jupyter Notebook • Packages: Numpy, Pandas, Matplotlib, Seaborn

# About this Mock Census
The mock census you will be given contains randomly generate data using the Faker package in
Python. It has been generated in a similar manner to (and designed to directly emulate the format of)
the 1881 census of the UK wherein only a few questions were asked of the population.The purpose of such a census is to compare different people across then nation and to provide the government with accurate statistics of the population to enable better planning, to develop policies, and to allocate certain funding.
The fields recorded are as follows:
(1) Street Number (this is set to “1” if it is a unique dwelling);
(2) Street Name;
(3) First Name of occupant;
(4) Surname of occupant;
(5) Age of occupant;
(6) Relationship to the “Head” of the household (anyone aged over 18 can be a “Head” – they are
simply the person who had the responsibility to fill in the census details);
(7) Marital status (one of: Single, Married, Divorced, Widowed, or “NA” in the case of minors);
(8) Gender (one of: Male, Female; note that other responses were not implemented in 1881);
(9) Occupation (this field was implemented in a modern style, rather than typical 1881
occupations);
(10) Infirmity (we have implemented a limited set of infirmities following the style of 1881);
(11) Religion (we have implemented a set of real-world religions).

The first task is to clean this dataset. There are missing entries, and, candidly, some responses from the population are outright lies. 

# The Task
The town from the census is a modestly sized one sandwiched between two much larger cities that it is connected to by motorways. The town does not have a university, but students do live in the town and commute to the nearby cities. Once you have a cleaned dataset to analyse, your task is to decide the following:
(a) What should be built on an unoccupied plot of land that the local government wishes to develop?

(b) What the local government should invest in to improve the economy of the town.
