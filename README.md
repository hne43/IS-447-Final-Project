# Socioeconomic Factors and Access to Nutrition in Illinois
Contributors: Grace Requeno and Lillian Hsu
## Abstract !! need to add a summary of our findings here!!
The goal of this project is to investigate the relationship between socioeconomic factors and obesity rates across counties in Illinois. By examining variables such as poverty rate, median household income, geographic location, and demographic composition, the analysis seeks to uncover patterns that link economic and social conditions to disparities in food access and nutritional health. Understanding these relationships can provide insights into how structural inequities influence health outcomes and inform targeted interventions to promote healthier communities across the state.

## Data
### Economic Research Service (ERS), U.S. Department of Agriculture (USDA). Food Access Research Atlas, https://www.ers.usda.gov/data-products/food-access-research-atlas/

This dataset includes information about food access data, with specific features such as location (by state and county), population, housing, income, and overall demographics (including race and age). These features relate to different food access metrics in the dataset, mainly low access metrics, along with the different demographics. This dataset is very similar to the previous dataset, just with a few more features. A very similar dataset can be found under the ‘Access and Proximity to Foodstore’ category sheet in the previous dataset, but this one in specific includes more information as it has more rows.

- Accuracy: To assess the accuracy of this dataset, I analyzed the documentation of the dataset. I noticed that information for the dataset was taken from a 2019 list of official supermarkets, accompanied by several census data that included the given information. For these reason, I assessed that the dataset could be accurate and trustworthy, but there is definitely more exploration that could be done for accuracy by checking external sources.

- Completeness: The dataset was mostly complete. For the socioeconomic section of the dataset, there were no null values detected for the state of Illinois and the columns I chose to focus on. For the health section of the dataset, there were some null values for columns that were not completely important or related that we chose to focus on. I found that the dataset was overall good for use, and a form of imputation could be implemented if needed.

- Timeliness: The dataset mostly covered data from 2019.

- Consistency: The consistency of the dataset was good. Checking between the different datasets/sections of the overall dataset, Illinois rows were consistent, as well as each row key. This told me that I could trust the different datasets to be integrated smoothly with each other.

- **Fit for use**: Overall, I would say the dataset was fit for use. I think more exploration of accuracy and consistency could be good. For example, I could explore separate datasets to test these metrics, but I would say that it was good overall.

### U.S. Department of Agriculture, Economic Research Service. Food Environment Atlas. https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads

This dataset is known as the Food Environment Atlas, and includes several different sheets/categories, covering: ‘Access and Proximity to Foodstore’, ‘Store Availability’, ‘Restaurant Availability’, ‘Food Assistance’, ‘State Food Insecurity’, ‘Food Taxes’, ‘Local Foods’, ‘Health and Physical Activity’, and ‘Socioeconomic Characteristics’. This dataset provides a wide overview of these characteristics across the U.S., including specific states and counties. Additionally, the dataset was last updated in July of 2025, so it is quite up to date. This dataset also seems to heavily focus on impoverished communities and demographics. As for the criteria of low income for this dataset, their definition comes from the Department of the Treasury’s New Markets Tax Credit program, in which the median household income would be less than or equal to 80% of the state-wide median household income. Another large focus of the dataset, aside from low-income households, would be low-access households. These are based on resident's distance to their closest good food retailer(s). Overall, this dataset proves to be a useful tool, offering several different categories of measurement and data relating to nutrition and food accessibility. This dataset would help greatly in our goal of mapping relationships between different socioeconomic factors and nutrition/food accessibility.

### Centers for Disease Control and Prevention. (2025, September 16). Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System. Data.CDC.gov. https://data.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7/about_data

This dataset is sourced from the Behavioral Risk Factor Surveillance System from the U.S. Department of Health and Human Services and includes information, ranging from the years 2011 to 2023, about adults’ diets throughout the United States. The dataset includes many other personal and socioeconomic features such as physical activity, weight status, age, income, race, location, and more. All of these factors would greatly aid in the analysis of how socioeconomic and self-care factors affect personal health behaviors. This dataset would be valuable in our research on finding how differences in health behaviors can potentially stem from community, upbringing, and demographics.

- Accuracy: To check the accuracy of the dataset, an external source was used. https://www.americashealthrankings.org/explore/measures/Obesity/IL shows that the obesity rate of adults in Illinois was 36%. And, in the dataset, the obesity rate of adults in Illinois was 33.89%. It was not the same as the external source, however, it can be considered accurate for our explorations.
  
- Completeness: Of the data that we need, which is the data of Illinois state, there are 215 rows of incomplete data. However, there are 1932 rows of data of illinois state, meaning that the incompleteness of the data we needed is only 10%. So, the completeness of this dataset is good for use.
  
- Timeliness: The dataset includes data from 2011 to 2023, which covers the years we want to investigate.
Consistency: The consistency was checked by checking if there are any logic errors in the dataset, by checking whether there is Data_Value lower than Low_Confidence_LImit or higher than High_Confidence_Limit. After checking, there are no logic errors in the dataset. So the consistency of this dataset is good.

- **Fit for use**: Overall, this dataset is fit for use, but does require a little bit of cleaning, such as getting rid of the data of the states that we’re not interested in and also deal with the missing values.

## Findings
As part of the analysis, we explored several socioeconomic factors, specifically race/ethnicity and income, to determine whether they showed any meaningful relationships with obesity rates and fruit consumption across Illinois. By comparing obesity prevalence and nutritional behavior indicators with demographic and economic characteristics, we aimed to identify potential patterns in how different communities experience access to healthy foods. This comparison helped us investigate whether disparities in income or racial/ethnic composition might be associated with differences in dietary habits or obesity outcomes. This data exploration also helped us determine which socioexoniomic factor we should focus on.
Below are two barplots showing the relationships between obesity rates and income and race/ethnicity.

From the first plot, it can be concluded that income and obesity rate do not have a strong relationship with each other.
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/713d1505-52e0-4992-ac66-a44a36c3abbd" />
However, in the second plot, it can be seen that race/ethnicity has a stronger relationship with obesity rate than income does. Specifically, Asians have a much lower obesity rate in the state of Illinois.
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/f1a9e7c6-0649-40c7-8ce9-01f87356fc44" />


## Future Work
## Reproducing
### Python Setup
````
import pandas as pd
import seaborn as sns
import matplotlib.pypplot as plt
````
## References
- U.S. Department of Agriculture, Economic Research Service. Food Environment Atlas. https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads
- Economic Research Service (ERS), U.S. Department of Agriculture (USDA). Food Access Research Atlas, https://www.ers.usda.gov/data-products/food-access-research-atlas/
- Centers for Disease Control and Prevention. (2025, September 16). Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System. Data.CDC.gov. https://data.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7/about_data
