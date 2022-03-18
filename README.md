# Are We Due for Another Prohibition?  

**Study Summary**  
With the use of data on retail sales of alcoholic beverages, I wish to research whether the United States is in for another "Prohibition." Prohibition in the United States was a constitutional ban on the production, importation, transportation, and sale of alcoholic beverages from 1920 to 1933, across the nation. The constitutional ban was enforced due to an alarming rise in the faith of alcohol and its benefits against influenza. Although the average alcohol consumption every year fell just before the Prohibition, consumption rebounded to pre-Prohibition levels within 10 years of being repealed. I hypothesize that with the dawn of a new pandemic (from 2020 - 21), alcohol consumption has reached, and exceeded the levels recorded during the influenza pandemic (1918 - 19), calling for a new, revised, and more successful Prohibition Act.  
  
During my research I will be combining the datasets from the FRED, NIH (Alcohol Abuse and Alcoholism), and Statista to analyze the similarities in alcohol consumption in 1918 - 19 and 2020 - 21. By the end of this research project, I will predict how alcohol consumption may change in the near future, without any intervention.  
  
**Datasets**  
[Apparent per capita ethanol consumption, United States, 1850–2016](https://github.com/chakraoishee/prohibition_analysis/blob/main/data/data-mjDxu.csv) - dataset from [NIH](https://pubs.niaaa.nih.gov/publications/surveillance110/tab1_16.htm) that presents the gallons of ethanol, based on population age 15 and older prior to 1970 and on population age 14 and older thereafter  
[Retail Sales in a Pandemic Recession](https://github.com/chakraoishee/prohibition_analysis/blob/main/data/fredgraph.csv) - data on grocery store, alcohol, pharmacies and drug, men's clothing, sporting goods, warehouse clubs and other superstores, and online sales from January 2019 to June 2020 from FRED used to compare how alcohol sales increased, in relation to other sales, during the pandemic.  
  
The primary dependent variable is year (ranging from 1850 to 2021 across all datasets and denoted as "Year"). Independent variables include:  
- percent change in retail sales in grocery stores, alcohol, pharmacies and drug, men's clothing, sporting goods, warehouse clubs, and other superstores denoted as "MRTSSM4451USS_NBD20200101," "MRTSSM4453USS_NBD20200101," "MRTSSM44611USS_NBD20200101," "MRTSSM44811USS_NBD20200101," "MRTSSM451USS_NBD20200101," "MRTSSM45291USS_NBD20200101," and "MRTSSM4541USS_NBD20200101," respectively in [Retail Sales in a Pandemic Recession](https://github.com/chakraoishee/prohibition_analysis/blob/main/data/fredgraph.csv)
- per capita ethanol consumption denoted as "Beer," "Wine," and "Spirits," respectively, in [Apparent per capita ethanol consumption, United States, 1850–2016](https://github.com/chakraoishee/prohibition_analysis/blob/main/data/data-mjDxu.csv)
  
 **Goals**  
 - [X] Analyze trends in alcohol consumption along with other retail sales
 - [X] Analyze per capita trends and predict what the liquor consumption will look like in this next decade (2020 - 2040)
   - [X] Present a table with predicted per capita values
 - [X] Discuss how Prohibition helped reduce consumption levels and how a new preventive Prohibition can do the same  

**Project Questions and Answers**  
1. Describe the project. Don’t worry if you end up changing your idea, that’s fine as long as
you tell us what you are doing. (4 points)  
With the use of data on retail sales of alcoholic beverages, I wish to research whether the United States is in for another "Prohibition." Prohibition in the United States was a constitutional ban on the production, importation, transportation, and sale of alcoholic beverages from 1920 to 1933, across the nation. The constitutional ban was enforced due to an alarming rise in the faith of alcohol and its benefits against influenza. Although the average alcohol consumption every year fell just before the Prohibition, consumption rebounded to pre-Prohibition levels within 10 years of being repealed. I hypothesize that with the dawn of a new pandemic (from 2020 - 21), alcohol consumption has reached, and exceeded the levels recorded during the influenza pandemic (1918 - 19), calling for a new, revised, and more successful Prohibition Act.  
During my research I will be combining the datasets from the FRED, NIH (Alcohol Abuse and Alcoholism), and Statista to analyze the similarities in alcohol consumption in 1918 - 19 and 2020 - 21. By the end of this research project, I will predict how alcohol consumption may change in the near future, without any intervention.  

2. Explain in a few sentences why you selected this project, and if you learned what you
had hoped to learn by doing this project (from your proposal). (4 points)  
Upon recently learning about the history of Prohibition and reading about the detrimental effects that alcohol has on an individual, especially in the midst of a pandemic, I was curious to learn if there was any trend in alcohol consumption during the COVID-19 pandemic and whether a similar trend was seen in the previous (Influenza) pandemic.  

3. Describe the two major class themes selected (any concept from any lecture is fair
game!), why you selected them, and how they are applied in the project. (5 points)  
I used advanced data structures and using tidyverse in R to analyze my datasets.  

4. What you would do differently if you were to have an opportunity to redo this project and
why. (4 points)  
Given more time, I would search for more data on grocery sales and pharmaceuticals, from other countries (where alcohol consumption levels are of concern), to predict their future alcohol consumption and determine whether they should enforce some controlling legislation.  

5. How to run your project. If your project requires a dataset, please include it if possible. Note that sometimes, you can’t share datasets. That’s fine as long as you can demonstrate the project’s functionality, perhaps with mocked-up data. (4 points). 
As mentioned in the Datasets section, this project was based on retail sales and per capita ethanol consumption data. Any data analysis and data preparation can be found in the .Rmd file.  

6. Was the project challenging in the way you expected? What did you overcome? (4
points)  
This project helped me test my limits with data visualization. My primary use of data visualization relied on base R prior to this project--during this project, I used ggplot2 to bring my data to life with figuress.  

7. Cited sources, appropriate acknowledgements. Explain how each source applied to your project. (5 points)  
Please refer to the .bib file that contains all of my reference material that was used for this project (also refer to in-text citations).  

8. If you attempted the extra credit, explain how you successfully met the criteria.  
I attempted to do the extra credit by using different and new libraries that I had never encountered before including jTools, stargazer, broom, forecast, and janitor to help with my data analysis.  
