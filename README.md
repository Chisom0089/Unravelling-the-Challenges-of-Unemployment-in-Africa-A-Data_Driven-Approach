# Unravelling-the-Challenges-of-Unemployment-in-Africa-A-Data_Driven-Approach
# Introduction
Unemployment remains one of the most daunting challenges facing African nations today. It is a multifaceted problem with deep roots in socio-economic, educational, and policy-related factors. The African population has drastically increased over the years causing the number of unemployed persons especially the youths to increase. 

# Problem Statement
The primary goal of this case study is to analyze data, identify patterns, and propose informed, data-driven recommendations that governments and stakeholders can implement to effectively address and reduce unemployment rates, particularly focusing on the African context. It involves the use of various datasets to uncover insights and strategies that contribute to the achievement of the Sustainable Development Goals.

# Data Sourcing
The Dataset used in this analysis can be seen https://drive.google.com/drive/folders/1xnM2OMZITtjWJSrytSHBQKWGLt5PdwDl?sender_ctype=email&sender_campaign=aOo5Yr&sender_customer=E88Op7v. It comprises of six different tables containing the Unemployment rate for men vs women, national strategy for youth employment, Share of Education in Government Expenditure, Share of the population with access to electricity, Total number of Limited Liabiltiy Companies from 2006-2020 and the country code.

# Data Cleaning
Tools used for Data Cleaning
- Power BI (Power query Editor)

I loaded the six tables into Power Query Editor for transformation and cleaning. I started by clearing all sorts of formatting in tables. I renamed columns and tables name to short and redable names, Removed outliers, checked for duplicates and null values, Removed unnecessary data statements in some tables. I created new column for the National strategy using the conditional column feature. 

After cleaning the individual columns seperately, I merged the first 5 datasets to get a consolidated datasets for further analysis and visualization in Power BI.

# Attributes of the Data
1. Entity: This field represents the country or region
2. Code: A three letter code representng the country where the unemployment data was collected.
3. Year: The year when the unemployment rate data was collected
4. % female Unemployment: This represents the percentage of female labour force that is unemployed, as estimated by the international Labour Organisation (ILO)
5. % Male Unemployment: This represents the percentage of the male labour force that is unemployed based on ILO
6. Population: This column contains the population figures for the respective entity for the given year
7. Continent: This field indicates the continent where the entity is located
8. Existence of a developed and operationalized national strategy for youth employment, as a distinct strategy or as part of a national
employment strategy: This indicates the status of a national strategy for youth employment in the respective country
9. Government Expenditure on Education: This represents the % of total government expenditure that is allocated to education. This field measures the priority given to edication in the national budget of the respective entities.
10. Total Number of LLC: This field indicates the number of new limited liability companies that were registered in the specified economy in the given year. 
11. Adult population: The number of Adults in the speicified Economy.
12. New Business Density rate: The number of registered firms per 1000 working age people.
13. Sub-region: A more specific geographical region categorization (Southern Asia, Northern Europe)
14. Alpha - 2: This is a two letter country-code, which is part of the ISO 3166 standard
15. Alpha-3: This is a three letter country code, also part of the ISO 3166 standard.


# Findings/Insights
1. The average population is 24.09M with female unemployment rate, 7.39% against male rate of 5.82%.
2. Top 5 populous country as at 2021 includes: Nigeria, Ethiopia, Egypt, South Africa and Kenya.
3. The Unemployment rate increased drastically from 2019 to 2021, with female rate increasing from 6.89% in 2019 to 8.05% in 2021 while male rate increased from 5.30% in to 6.10% in 2021.
4. Countries with access to Education tends to have a lower rate of unemployment.
5. Most countries with electricity access  have lower rate of unemployment.
6. Sub-Saharan African regions with higher Total Business Density rate have reduced rate of unemployment.
7. Higher number of Total limited liability companies can be helpful in addressing unemployment challenge in Africa.

# Recommendations
1. With the higher rate of unemployment in the female world, targeted programs such as vocational trainings, mentorships and initiatives should be implemented to address the unemployment issues in females.
2. Government should invest in Education and skill development programs in order to equip both individuals with the necessary skills needed for the Job market.
3. Strategies should be adopted based on countries specific economic, cultural, social factors to address the unemployment challenges especially in countries with higher population and unemployment rate.
4. Continuous efforts should be put in place to ensure access to electricity is improved.
5. Limited liability companies should be encouraged by creating a conducive business environment and providing financial incentives.
6. Other factors such as technological advancement, globalizations trends, as well as changes in consumer behaviour should be looked into to ascertain their impacts on the rate of unemployment in Africa.
7. Implement initiative which can contribute to the overall economic development such as infrastructural development, Education, healthcare system.
