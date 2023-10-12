README

In this project, I aim to assess whether a relationship exists between the size of a given city in Texas and the growth / decline of its population. To do so, I analyzed data scraped from the Wikipedia article "List of Municipalities in Texas", which uses census data (from 2010 and 2020), along with population estimates (from 2022) to calculate each municipality's rank, population, change in population, and designation. The data was scraped on 10/9/23 using BeautifulSoup. I used the Pandas package to clean and transform the data, along with the SciPy and MatPlotLib libraries to analyze and visualize the data.

I created this work under the MIT License, which is permissive and allows for redistribution and modification. The original data is licensed under the Creative Commons Attribution-Sharealike 4.0 International License, which also allows for sharing and modification.

Data info by attribute:
Rank - integer - rank assigned to the city based on population size, with 1 being the largest city
City - string - name of the city
Primary County - county that occupies the largest portion of the city
Population - float - estimated population in 2022
2010-2020 change - change in the city's population, as a percentage, between 2010-2020

Package documentation links:
SciPy - https://docs.scipy.org/doc/scipy/
Pandas - https://pandas.pydata.org/docs/
MatPlotLib - https://matplotlib.org/stable/index.html