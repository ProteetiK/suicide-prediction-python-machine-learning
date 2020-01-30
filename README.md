# suicide-prediction-python-machine-learning

Problem Statement: Predict the possibility of a person committing suicide using a fitting machine learning model,
based upon a number of affecting factors such as age, their country of residence, the annual GDP of the countries concerned etc.

Data Description: 
United Nations Development Program. (2018). Human development index (HDI). Retrieved from http://hdr.undp.org/en/indicators/137506
World Bank. (2018). World development indicators: GDP (current US$) by country:1985 to 2016. Retrieved from http://databank.worldbank.org/data/source/world-development-indicators#
[Szamil]. (2017). Suicide in the Twenty-First Century [dataset]. Retrieved from https://www.kaggle.com/szamil/suicide-in-the-twenty-first-century/notebook
World Health Organization. (2018). Suicide prevention. Retrieved from http://www.who.int/mental_health/suicide-prevention/en/
 The data columns available to us while working on this project are as follows:
1.	country- a list of countries
2.	year- a list of years
3.	suicides_no- the no. of individual suicides recorded in a particular country in a particular year
4.	sex- gender of the persons concerned
5.	age- page of the persons in question
6.	population- the population of a given country
7.	suicides/100k pop- the no. of suicides recorded in a particular country in a particular year per 100,000 persons
8.	country-year- a column combining country and year columns
9.	HDI for year- HDI for all concerned countries
10.	generation- the colloquial name assigned to each generation
11.	gdp_for_year($)- GDP of the countries in each year
12.	gdp_per_capita($)- GDP per capita of the countries in each year
Of the aforementioned variables, “suicides/100k pop” i.e. the number of suicides recorded in a country during a particular year per 100,000 people constituting the population of the country, serves as the independent variable, while the rest contribute to the determination of the possibility of a certain person committing suicide.

