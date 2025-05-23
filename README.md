# Power-BI-project

World Population Analysis 
The World Population analysis project is an analysis of international population data. It contains female and male data, as well as the aggregate data of different countries around the world.
Team
This report is done by a combined effort done by Elson Ricafrente and Navdeep Kaur Pannu. 

METADATA
World population analysis is based on the analysis done on the data collected from an external source, World Bank open data. The data tables are obtained from https://data.worldbank.org/indicator/SP.POP.TOTL .In the BI workbook, after working on the external raw data, we are left with eight different tables for our analysis. 
The tables details are as follows:
TABLE 1: The first table used in the analysis is names as Total population. This population table has 5 columns and 13,608 rows. The names of five columns are Country, Code, Year, Population, and Region. 
TABLE 2: The second table that we are using for the analysis is named as Total Male population. This table has five columns and 13,608 rows. The names of columns are Country, Code, Year, Population, and percent population. 
TABLE 3:  The third table that we are using for the analysis is named as Total Female population. This table has five columns and 13,608 rows. The names of columns are Country Name, Country Code, Year, Population, and percent population. 
TABLE 4:  The fourth table that we are using for the analysis is named as Total International Migrant stock. This table has five columns and 1,264 rows. The names of columns are Country, Code, Year, Population, and percent population.
TABLE 5:  The fifth table that we are using for the analysis is named Total Labor Force. This table has 4 columns and 6,132 rows. The names of columns are Country, Code, Year, and Population.

ANALYSIS QUESTIONS:
Following are the analysis questions for our analysis:
1.	What is the world’s average population growth rate?
2.	What are the top five most populated countries in the last ten years?
3.	What is the world’s total male and female population as of 2022?
4.	What country has the highest labor force?
5.	What country has the highest International migrant stock?

PREPARATION FOR FINAL ANALYSIS
The data for analysis was taken from the World Bank open data. In order to get our results, we downloaded nine different tables. These tables had data like total population, percentage of population, Male population, female population. But the data was scattered in all the tables and was not comparable. So, after downloading the data, various steps were taken to clean the data. Using transform data, the data type of various columns was changed in order to use them for various comparison. Then their top row was changed to use them as headers. One of the columns of the tables named  Country name had names of various countries but it also included data for various regions put together in one row which made the comparison difficult and results more unreliable. So, new tables were created to make the data apt for the comparison. Different tables were combined to create five final tables. 
The table of Total population was renamed, and the data looked as in the following screenshot.

 ![image](https://github.com/user-attachments/assets/33eb4ccb-56b0-4ade-a4b9-dae7c9338af0)

The Unpivot Other Columns command was used to get the yearly data organised. Also, Regions were separated from the countries names and given a separate column name.

 ![image](https://github.com/user-attachments/assets/dcbd962c-b2c1-48e7-918a-2c7236f4d1ce)

After all the editing done in Transform Data for the table of total population, there are five rows which includes the data from Country, Code, Region, year and Population.

![image](https://github.com/user-attachments/assets/b3f93f80-1e84-4572-85ad-a3e90623bf48)
 
In the table of total male population, following transformations can be seen. To obtain this table, columns were renamed, and data types were set as required. The table of percent male population was also organised so that merge can be used. From the data on percent Male population, columns were removed, and then organised as country, region. Unpivot was applied to the table to organize the data in more readable form. In the same way Male population table was organised. 
In the following screenshot, you can see that two tables were combined in to one which shows total population as well as the percentage of male population. 

![image](https://github.com/user-attachments/assets/eea18c22-d97e-4de6-8b2c-f34e9b21f2a5)


In the table of female population, similar steps were applied as in Total male population table. Data was obtained from two different tables female population and percentage female population. Then it was organized in regions and countries.   

![image](https://github.com/user-attachments/assets/e6540c5e-16a9-444a-8f97-ff3d6589be42)


![image](https://github.com/user-attachments/assets/2031144e-77d1-48a5-9a7d-a29674bb73ca)

Unpivot was applied on both the tables and then merged resulting in our final table Total Female population which is used for our analysis. The final table of Total Female population is below:

![image](https://github.com/user-attachments/assets/8e95f8fa-9a7e-496a-90fe-977e7be2e79a)

Our fourth table is Total International Migrant Stock, the following transformations can be seen. To obtain this table, two tables were used, International migrant stock and percent international migration. Columns were renamed, and data types were set as required. The table of percent international Migration was also organised so that merge can be used. From this data, tables were organised as country, region. Unpivot was applied to the table to organize the data in more readable form. The final table was as follows. 
  
![image](https://github.com/user-attachments/assets/357778e6-f189-4916-8f30-1d8c22bbe9d9)

Our final table for analysis is Total Labor force. The table was transformed by removing unwanted columns and then Unpivot to organise data yearly. Our final table has four columns named Country, Code, Year and population. 

![image](https://github.com/user-attachments/assets/0bb02ac5-62ce-4b18-81d5-012d60ae5cad)


RELATIONSHIPS:
	Four different relationships are used in this analysis. After getting our final five tables, four relationships were created among them as shown in the screenshot below. Data model can be seen in the next screenshot.
 
![image](https://github.com/user-attachments/assets/433c1470-56a5-4d09-b1da-7461b860938f)


![image](https://github.com/user-attachments/assets/e4bfa0a6-74ce-4fae-80d9-9541560f8ff9)
 


VISUALIZATION and CONCLUSIONS:
To answer our questions in the data analysis, the following graphs were created. The visualization is a line graph, and it shows how world population has been increasing over the years. The world population has been increasing at a very constant rate and has shown steep upward growth until 2020 but after that there has been a change. Population growth from the year 2020 to 2022 has changed dramatically showing a very shallow graph as compared to previous years. Since 1969, World population growth has been shown a growth between 0.7 billion and 0.9 billion. But from the year 2020 to 2022, the world population has growth of only 0.1 billion which is 0.7 billion difference from average growth over the past years. 

![image](https://github.com/user-attachments/assets/a1cf7b94-97b0-4709-af93-1ffde124974c)
 
The graph shows the top 5 most populated countries in the world. A bar graph is used to present the data and countries are color coded for more clarity.

![image](https://github.com/user-attachments/assets/deec25b7-c4a8-44a6-bdab-c158156df620)
 

Our analysis of the world data shows that China has highest population in the world up until 2020. It also shows that the China has been consistently having high population over the years since 2012 to 2020. India has been having second highest population in the world from 2012 to 2020. But in the year 2020, India’s population growth has come very close to China. It looks like that China has controlled the population growth rate and India’ population growth is still showing an upward trend as previous years. In 2022, India seems to be having highest population the World. With some difference comes China at second position with its population control policies. 
United Nations, Indonesia and Pakistan are at rank three, four, and five, respectively. These three countries have shown consistent growth over the period of 2012 to 2022. The population growth rate in these three countries has not shown any considerable change in the past ten years. All three countries have an upward trend but a very shallow slope.
Overall, this graph shows that China is the only country that showed downward trend in the population growth. India has higher population growth rate than other top five countries. United States, Indonesia and Pakistan has upward but shallow and consistent population trend.

Graph 3 

![image](https://github.com/user-attachments/assets/c9a0c405-9254-4baf-b392-3cab57c9ccca)

Graph 3 shows the comparison of male and female population over the years. This graph shows female population in pink and male population in blue. It clearly indicates that the population growth ratio of male and female has been very consistent over the years. Number of males has been lesser than the number of females. The male population in the year 2022 was 3.94 billion as compared to 3.98 billion females around the world.
The next graph shows a very important resource in any country’s development i.e., Working population. This graph compares the workforce population among various countries. It shows that India and China having maximum population also have very high workforce available as well. The size of the dots shows a clear comparison between various countries’ working population.

![image](https://github.com/user-attachments/assets/c3d41b28-1825-4723-bc1f-ed487ddef2a9)

 
![image](https://github.com/user-attachments/assets/e12ac0ab-7ec8-4cc0-a3e7-2eeb6ff96473)
  

The last graph shows countries’ comparison about which country has the highest migrant population. It compares the migration growth over various years. It shows data every five years from 1990, 1995, 2000, 2005,2010, 2015. It shows that United States of America has been consistently having the highest migration population over the years. Migration growth to other countries like Canada, has been changing over the years. The migration to the United States of America has been showing upwards trends for all our years under study.
As shown in our analysis, all our analysis questions have been answered and the comparison of these analysis are shown in the visualizations.

REFERENCE:
1.	World Bank (n.d.). Population, total. World Bank Open Data. https://data.worldbank.org/indicator/

