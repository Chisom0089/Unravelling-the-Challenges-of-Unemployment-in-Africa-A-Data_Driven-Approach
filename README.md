# Unravelling-the-Challenges-of-Unemployment-in-Africa-A-Data_Driven-Approach

![Unemployment 1](https://github.com/Chisom0089/Unravelling-the-Challenges-of-Unemployment-in-Africa-A-Data_Driven-Approach/assets/138637505/182ca3dd-cc76-41c3-beb1-e348b93cd5cb)

![Unemployment 2](https://github.com/Chisom0089/Unravelling-the-Challenges-of-Unemployment-in-Africa-A-Data_Driven-Approach/assets/138637505/a9cbd208-63aa-4661-8fec-bd75d04d6d7b)

![Unemployment 3](https://github.com/Chisom0089/Unravelling-the-Challenges-of-Unemployment-in-Africa-A-Data_Driven-Approach/assets/138637505/310fac07-f81e-44d1-b15e-e7bc1220089f)


# Introduction
Unemployment remains one of the most daunting challenges facing African nations today. It is a multifaceted problem with deep roots in socio-economic, educational, and policy-related factors. The African population has drastically increased over the years causing the number of unemployed persons especially the youths to increase. 

# Problem Statement
The primary goal of this case study is to analyze data, identify patterns, and propose informed, data-driven recommendations that governments and stakeholders can implement to effectively address and reduce unemployment rates, particularly focusing on the African context. It leverages the use of diverse datasets to uncover valuable insights and strategies that contribute to the achievement of the Sustainable Development Goal.

# Data Overview
I was challenged with six diverse datasets, each offering a unique perspective on factors influencing unemployment, they include:
1. Unemployment Rate (Men vs. Women): This dataset provides a comparative view of unemployment rates between genders.
2. National Strategy for Youth Employment: This dataset outlines various national strategies adopted across different African countries to combat youth unemployment.
3. Share of Education in Government Expenditure: Education is a critical factor in employment. This dataset sheds light on how much governments are investing in education.
4. Population with Access to Electricity: Access to electricity is a fundamental driver of economic development and can influence employment opportunities. This dataset provides insights into the availability of electricity across different regions and its potential impact on employment.
5. Total Firms (Historical Data): The health of a country's private sector is directly linked to employment rates. This dataset includes historical data on the number of firms.
6. Country Codes: This dataset is essential for mapping data points to specific African countries, enabling a more precise and geographically contextual analysis.

# Data Cleaning and transformation
I loaded the six datasets into Power Query Editor in Power BI for transformation and cleaning. I started by clearing all sorts of formatting in the tables and renamed column and table names to short and readable names, ensured consistency in the names of countries provided, Removed outliers (dates with negative values), unnecessary columns and empty rows, replaced null values with '0', checked for duplicates value, removed unnecessary statements in some tables. I created new column for the National strategy using the conditional column feature. After cleaning the tabes individually, I merged the first 5 datasets to get a consolidated datasets for further analysis and visualization in Power BI.

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
3. The Unemployment rate increased drastically from 2019 to 2021, with female rate increasing from 6.89% in 2019 to 8.05% in 2021 while male rate increased from 5.30% in 2019 to 6.10% in 2021.
4. Countries with access to Education tends to have a lower rate of unemployment.
5. Most countries with electricity access  have lower rate of unemployment.
6. Sub-Saharan African regions with higher Total Business Density rate have reduced rate of unemployment.
7. Higher number of Total limited liability companies can be helpful in addressing unemployment challenge in Africa as most countries with reduced unemployment rate have higher number of total limited liability companies.

# Recommendations
1. With the higher rate of unemployment in the female world, targeted programs such as vocational trainings, mentorships and initiatives should be implemented to address the unemployment issues in females.
2. Government should invest in Education and skill development programs in order to equip both individuals with the necessary skills needed for the Job market.
3. Strategies should be adopted based on countries specific economic, cultural, social factors to address the unemployment challenges especially in countries with higher population and unemployment rate.
4. Continuous efforts should be put in place to ensure access to electricity is improved.
5. Limited liability companies should be encouraged by creating a conducive business environment and providing financial incentives.
6. Other factors such as technological advancement, globalizations trends, as well as changes in consumer behaviour should be looked into to ascertain their impacts on the rate of unemployment in Africa.
7. Implement initiative which can contribute to the overall economic development such as infrastructural development, Education and healthcare system.

Thank you for reading through. Feel free to interact with my [Dashboard](https://app.powerbi.com/groups/me/reports/b0337025-6869-445c-b905-1abe296a1958/ReportSection?experience=power-bi
) and say me a hello! on [Linkedin](https://www.linkedin.com/in/chisomibemere) 



