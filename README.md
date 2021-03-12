## UN GDP and Internet Usage

![UNlogo](../main/Images/UNlogo.png)

<br>
<br>

## Table of Contents
* [General Information](#general-information)
* [Technologies](#technologies)
* [Files in this Repository](#files)
* [Data Exploration Questions](#data)
* 
<br>
<br>

## <a name="general-information"></a>General Information
The goal of this individual project was to explore data from the United Nations, specifically looking at GDP per capita and the percent of the population's internet access across a ten year timeframe (2004-2014). 
<br>
<br>

## <a name="technologies"></a>Technologies
Project is created with:
* Python 
* Packages: pandas, numpy, matplotlib, seaborn
* Jupyter Notebook
<br>
<br>

## <a name="files"></a>Files in this Repository
<br>
<br>

## <a name="data"></a>Data Exploration Questions
\6.	Take a look at the datatypes for the columns in each DataFrame.
99. Take a look at the last 10 rows of each DataFrame in turn.
7.	Drop the `value footnotes` column from both DataFrames. Check that this worked as expected.
8.	Change the columns for the GDP Per Capita DataFrame to ‘Country’, ‘Year’, and ‘GDP_Per_Capita’.
9.	Change the columns for the Internet Users DataFrame to ‘Country’, ‘Year’, and ‘Internet_Users_Pct’.
10.	Merge the two DataFrames to one. Merge **all rows** from each of the two DataFrames. Call the new DataFrame `gdp_and_internet_use`.
11.	Look at the first five rows of your new DataFrame to confirm it merged correctly.
12.	Look at the last five rows to make sure the data is clean and as expected.
13.	Subset the combined DataFrame to keep only the data for 2004, 2009, and 2014. Check that this happened correctly.
14.	Create three new DataFrames, one for 2004, one for 2009, and one for 2014. Give them meaningful names that aren't too long.
15.	Which country had the highest percentage of internet users in 2014? What was the percentage? (Try typing the first 3 letters of your DataFrame name and hitting the tab key for auto-complete options).
16.	Which country had the lowest percentage of internet users in 2014? What was the percentage?
17.	Repeat for 2004 and 2009.
18.	Which country had the highest gdp per capita in 2014? What was the gdp per capita?
20.	Which country had the lowest gdp per capita in 2014? What was the gdp per capita?
21.	Create some scatterplots:  
    a.  2004 Percent Using the Internet vs GDP Per Capita  
    b.	2009 Percent Using the Internet vs GDP Per Capita  
    c.	2014 Percent Using the Internet vs GDP Per Capita  
22.	Are there differences across years? What do the plots tell you about any relationship between these two variables? Enter your observations as a markdown cell.
23.	Look at the distribution of gdp per capita values for 2014. Is it unimodal?
24.	Look at the distribution of Internet Use for 2014. Is it unimodal?
25.	What are the top 5 countries in terms of internet use in 2014?
26.	Create a DataFrame called top_5_internet **from the combined DataFrame that has all three years _for the 5 countries that had the greatest 2014 internet usage_**. You should have 15 rows. Check that this is true.
27.	Create a seaborn FacetGrid to show the internet usage trend across the years 2004, 2009, and 2014 for these 5 countries (those with the highest reported internet use in 2014). Which country had the greatest growth between 2004 and 2014? Is there a plotting issue with Bermuda? Can you fix it?
28.	Repeat the steps above to look at the trend for the 5 countries with the lowest 2014 internet usage. Which country has consistently had the least internet use?
29.	Find the top 5 countries for 2014 in terms of GDP per capita; create a DataFrame to look at 10-year trends (use 2004, 2009, 2014 to look at the 10-year trend) in gdp per capita for the 5 countries with the highest 2014 GDP per capita. Use a seaborn facet grid for this.
96. Repeat this one more time to look at 10-year trend for the 5 countries for 2014 with the lowest GDP per capita.
30.	Is there anything surprising or unusual in any of these plots? Searching on the internet, can you find any possible explanations for unusual findings?


### Bonus exercise:
1.    Download another data set from the UN data (http://data.un.org/Explorer.aspx) to merge with your data and explore.
