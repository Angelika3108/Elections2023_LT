Here I solved interview tasks for Data analytics for Lithuanian national data agency for 2023 year in Python.
I attach solution for Junior and Mid-level tasks.

Junior is evaluation of elections(presindetial, mayor, member of Seimas) and referendums(consultative, mandatory, mandatory constitutional) outcomes according to Lithuanian electoral laws,  I used usual Python code here with if... else conditions.

Mid-level is evaluation of 2nd round of elections outcome which were held at 2023 year for the mayor of the municipality. 
Here I used Pandas, GeoPandas, Matplotlib, Contextily libraries, and proportions_ztest function from statsmodels.stats.proportion for:
making a new dataframe of all candidates that got statistically higher support from voters in municipalities by mail;
making a Lithuanian map with all the districts where voters support by mail was statistically higher.

![Chart 1](map_new.jpg)
