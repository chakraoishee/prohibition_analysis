# Are We Due for Another Prohibition?  

**Study Summary**  
With the use of data on retail sales of alcoholic beverages, I wish to research whether the United States is in for another "Prohibition." Prohibition in the United States was a constitutional ban on the production, importation, transportation, and sale of alcoholic beverages from 1920 to 1933, across the nation. The constitutional ban was enforced due to an alarming rise in the faith of alcohol and its benefits against influenza. Although the average alcohol consumption every year fell just before the Prohibition, consumption rebounded to pre-Prohibition levels within 10 years of being repealed. I hypothesize that with the dawn of a new pandemic (from 2020 - 21), alcohol consumption has reached, and exceeded the levels recorded during the influenza pandemic (1918 - 19), calling for a new, revised, and more successful Prohibition Act.  
  
During my research I will be combining the datasets from the FRED, NIH (Alcohol Abuse and Alcoholism), and Statista to analyze the similarities in alcohol consumption in 1918 - 19 and 2020 - 21. By the end of this research project, I will predict how alcohol consumption may change in the near future, without any intervention.  
  
**Datasets**  
[Apparent per capita ethanol consumption, United States, 1850–2016](https://github.com/chakraoishee/maps_30550_from_data_to_manuscript_in_R/blob/main/data/data-mjDxu.csv) - dataset from [NIH](https://pubs.niaaa.nih.gov/publications/surveillance110/tab1_16.htm) that presents the gallons of ethanol, based on population age 15 and older prior to 1970 and on population age 14 and older thereafter  
[Retail Sales in a Pandemic Recession](https://github.com/chakraoishee/maps_30550_from_data_to_manuscript_in_R/blob/main/data/retail_sales_in_a_pandemic_recession.xls) - data on grocery store, alcohol, pharmacies and drug, men's clothing, sporting goods, warehouse clubs and other superstores, and online sales from January 2019 to June 2020 from FRED used to compare how alcohol sales increased, in relation to other sales, during the pandemic.  
  
The primary dependent variable is year (ranging from 1850 to 2021 across all datasets and denoted as "Year"). Independent variables include:  
- percent change in retail sales in grocery stores, alcohol, pharmacies and drug, men's clothing, sporting goods, warehouse clubs, and other superstores denoted as "MRTSSM4451USS_NBD20200101," "MRTSSM4453USS_NBD20200101," "MRTSSM44611USS_NBD20200101," "MRTSSM44811USS_NBD20200101," "MRTSSM451USS_NBD20200101," "MRTSSM45291USS_NBD20200101," and "MRTSSM4541USS_NBD20200101," respectively in [Retail Sales in a Pandemic Recession](https://github.com/chakraoishee/maps_30550_from_data_to_manuscript_in_R/blob/main/data/retail_sales_in_a_pandemic_recession.xls)
- per capita ethanol consumption denoted as "Beer," "Wine," and "Spirits," respectively, in [Apparent per capita ethanol consumption, United States, 1850–2016](https://github.com/chakraoishee/maps_30550_from_data_to_manuscript_in_R/blob/main/data/data-mjDxu.csv)
  
 **Goals**  
 - [X] Analyze trends in alcohol consumption along with other retail sales
 - [X] Analyze per capita trends and predict what the liquor consumption will look like in this next decade (2020 - 2040)
   - [X] Present a table with predicted per capita values
 - [X] Discuss how Prohibition helped reduce consumption levels and how a new preventive Prohibition can do the same  
