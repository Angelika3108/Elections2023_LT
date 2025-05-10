Here I solved interview tasks for Data analytics for Lithuanian national data agency for 2023 year in Python.
I attach solution for Junior and Mid-level tasks.

Junior 
Made Python code with conditional logic (if...else) for evaluation of election’s (presidential, mayor, Seimas) and referendum’s (consultative, mandatory, constitutional) outcomes based on Lithuanian electoral laws. User inputs total number of registered voters in election district, number of voters who participated, candidate’s name and his votes count at election or votes count for passing the decision on referendum. And then user gets the answer: which candidate won or if there will be 2nd round of election or if the decision will be passed into motion.

Mid-level is evaluation of 2nd round of elections outcome which were held at 2023 year for the mayor of the municipality. 
Here I used Pandas, GeoPandas, Matplotlib, Contextily libraries, and proportions_ztest function from statsmodels.stats.proportion for:
making a new dataframe of all candidates that got statistically higher support from voters in municipalities by mail;
making a Lithuanian map with all the districts where voters support by mail was statistically higher.

![Chart 1](map_new.jpg)
