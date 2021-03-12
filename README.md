## GDP and Internet Usage

![UNlogo](../main/Images/UNlogo.png)


## Table of Contents
* [General Information](#general-information)
* [Technologies](#technologies)
* [Files in this Repository](#files)
* [Data Exploration Questions](#data)
<br>

## <a name="general-information"></a>General Information
The goal of this individual project was to explore data from the United Nations, specifically looking at GDP per capita and the percent of the population's internet access across a ten year timeframe (2004-2014).  The two datasets were merged and analyzed with Python.
<br>
<br>

## <a name="technologies"></a>Technologies
Project is created with:
* Python 
* Packages: pandas, numpy, matplotlib, seaborn
* Jupyter Notebook
<br>

## <a name="files"></a>Files in this Repository
All python scripts are in the UN-data-gdp-internet-usage.ipynb file in the notebooks folder. 
<br>
<br>

## <a name="data"></a>Data Exploration Questions
* Merge the two DataFrames to one. Merge **all rows** from each of the two DataFrames. 
* Subset the combined DataFrame to keep only the data for 2004, 2009, and 2014. Check that this happened correctly.
* Create three new DataFrames, one for 2004, one for 2009, and one for 2014. Give them meaningful names that aren't too long.
* Which country had the highest percentage of internet users in 2014? What was the percentage? (Try typing the first 3 letters of your DataFrame name and hitting the tab key for auto-complete options).
* Which country had the lowest percentage of internet users in 2014? What was the percentage?
* Repeat for 2004 and 2009.
* Which country had the highest gdp per capita in 2014? What was the gdp per capita?
* Which country had the lowest gdp per capita in 2014? What was the gdp per capita?
* Create some scatterplots:  
    2004 Percent Using the Internet vs GDP Per Capita  
    2009 Percent Using the Internet vs GDP Per Capita  
    2014 Percent Using the Internet vs GDP Per Capita  
* Are there differences across years? What do the plots tell you about any relationship between these two variables? Enter your observations as a markdown cell.
* Look at the distribution of gdp per capita values for 2014. Is it unimodal?
* Look at the distribution of Internet Use for 2014. Is it unimodal?
* What are the top 5 countries in terms of internet use in 2014?
* Create a DataFrame called top_5_internet **from the combined DataFrame that has all three years _for the 5 countries that had the greatest 2014 internet usage_**. You should have 15 rows. Check that this is true.
* Create a seaborn FacetGrid to show the internet usage trend across the years 2004, 2009, and 2014 for these 5 countries (those with the highest reported internet use in 2014). Which country had the greatest growth between 2004 and 2014? Is there a plotting issue with Bermuda? Can you fix it?
* Repeat the steps above to look at the trend for the 5 countries with the lowest 2014 internet usage. Which country has consistently had the least internet use?
* Find the top 5 countries for 2014 in terms of GDP per capita; create a DataFrame to look at 10-year trends (use 2004, 2009, 2014 to look at the 10-year trend) in gdp per capita for the 5 countries with the highest 2014 GDP per capita. Use a seaborn facet grid for this.
* Repeat this one more time to look at 10-year trend for the 5 countries for 2014 with the lowest GDP per capita.
* Is there anything surprising or unusual in any of these plots? Searching on the internet, can you find any possible explanations for unusual findings?
