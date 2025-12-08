# Socioeconomic Factors and Access to Nutrition in Illinois
Contributors: Grace Requeno and Lillian Hsu
## Summary
Concerns about health equity, food security, and several community health disparities have been highlighted over the past several years and growth in public health topics. This has strengthened the public need to understand how several different factors may affect different communities’ access to self-care and healthy assets. The goal of this project is to investigate the relationship between socioeconomic factors and how it affects obesity rates, food access, and overall nutritional health across counties in Illinois. Our original aim was to focus on obesity rates, there was some data limitations that pointed us in a direction to focus more on food access in addition to nutritional health and obesity. By examining variables such as poverty rate, median household income, geographic location, and demographic composition, the analysis seeks to uncover patterns that link economic and social conditions to disparities in food access and nutritional health. Understanding these relationships can provide insights into how structural inequities influence health outcomes and inform targeted interventions to promote healthier communities across the state. 

Nutrition and health outcomes are not solely determined by personal choices, they are also shaped by broader structural conditions. Communities with limited access to healthy foods, fewer resources, and socioeconomic disadvantages often face higher risks of obesity and poor dietary habits and long-term health challenges. Understanding these patterns in Illinois is important for identifying which populations are most affected and for informing policies that promote more equitable access to nutrition across the state. This project aims to provide insight into these disparities and support data-driven approaches to improving public health. 

Additionally, understanding how food access and nutritional health may vary across different counties in Illinois can also aid in state resource allocation and even specific policy decisions relating to nutritional health. For instance, if it is shown that certain counties experience poorer food access and nutritional health, policymakers can focus on improving their economic development and health education, as well as make progress toward improving the health of that county overall.

Ultimately, this research would offer a solid foundation in understanding how several socioeconomic factors, such as poverty rate, median household income, geographic location, and demographic composition, play a role in shaping nutritional environments. Through highlighting the differences in food access across many counties in Illinois, a project like this could help shape policymaking and public health initiatives to improve the quality of life for many residents of Illinois. Overall, work and data analysis such as what is presented in this project would aid greatly in ongoing issues about health equity across Illinois.


### Research Questions
- How do different socioeconomic factors in Illinois, such as location, poverty rate, median income, and overall demographics, relate to the population's food access and nutritional health?

Our analysis found that while income did not show a strong or consistent relationship with obesity rates across Illinois counties, race and ethnicity did, with Asian populations exhibiting significantly lower obesity prevalence. Economic conditions, however, showed a much stronger connection to food access and nutritional environments. Counties with a higher income tended to have more access to healthy food resources, whereas counties with higher poverty rates consistently faced reduced food access and fewer healthy food resources. Moreover, changes in food access over time revealed that disadvantaged communities not only have poorer access but also experience slower improvements, suggesting inequities as wealthier wealthier counties continue to progress more quickly. Overall, the findings highlight that poverty and broader socioeconomic disadvantages are key determinants of disparities in food access and nutritional health, emphasizing the need for policies and public health to support disadvantaged communities. 


## Data Profile + Quality
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

The scatter plot showing the relationship between median household income and food access per capita seems to show an upward trend. This is shown by the solid red line in the middle that is also surrounded by several data points. This tells us that counties with higher incomes do tend to have better food access resources. So, counties and environments that have residents who are more advantaged economically are also more likely to be more advanced with their healthy living habits, such as better healthy food access. 
<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/e3eed20d-0901-4f2a-8eb5-d3903c3c41b5" />

The scatter plot showing the relationship between poverty rate and food access per capita seems to show a negative relationship, further relating to and confirming the previous scatter plot’s suggestions. The pattern shown in this scatter plot indicates that disadvantaged communities have less access to healthy food access and environments. This also suggests that these counties likely lack funding for better food access distribution, causing worse health outcomes among their residents.
<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/9b538d42-2812-4637-a2ae-abc3ac6599ad" />


The scatter plot showing the relationship between poverty rate and change in per-capita food access shows that more economically disadvantaged communities seemed to experience less meaningful improvements in food access over time. This is especially important to consider because although it may be acknowledged that lower-income communities have worse access to healthy resources, it seems as though not much is being done about it by policymakers. This points to some economic disparities and hardships that need to be addressed. Higher-income communities seem to be advancing quicker while lower-income communities are struggling to keep up with these trends.

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/b0ba92de-8538-4386-ba33-f7ede290ae9e" />


Overall, across these three scatter plots, it is evident that economic conditions, especially relating to income and poverty rates, play quite a major role in food access and health equity across several counties in Illinois. Higher-income counties already have better access to healthy food resources, but also advance and improve quicker with their resources. These findings point us to consider how policymakers and public health officials can make initiatives on improving the quality of living and health of those in less fortunate situations.

## Future Work

Based on our findings, there seems to be a lot of potential future work that can be done on this research topic. First, it was unfortunate that there was limited data on obesity rate per county in Illinois, so it would be nice to explore more datasets that might specifically cover the topic of obesity rate among the different counties of Illinois. It would also be good to integrate a dataset including obesity rate of each county with the other datasets we have explored. Doing this would allow for a more holistic review and approach of the data, and this would allow us to better answer our initial research question. It would be useful to see more direct translations between food access and measurable differences in nutritional health results in residents of different counties.

In addition, we could explore more specific aspects of food access. In this report, food access was researched as a general term pointing to how accessible overall grocery stores and healthy food are. It would be interesting to focus on different kinds of specific types of food access. This would include comparing food access such as restaurants, grocery stores, farmers market, and residents’ transportation/proximity to these different access points. This would allow us to delve deeper into food accessibility and how different types of access may be found across different counties also based on socioeconomic factors and status.

On the other hand, another direction of future work we can take would be to study different investment patterns made by policymakers, public health officials, and governments among Illinois and the different counties in Illinois. This would give us a better understanding of why there seems to be such disparities between the different counties in Illinois in regards to food access and health equity. Researching potential funding disparities could also be a good stepping stone toward public health initiatives to improve quality of life and health equity for more people across the state based on their socioeconomic status.

The last potential future work I can think of would be to utilize a more hands-on approach in this research. Directly getting involved with residents of different counties would be a good way to get honest opinions and feedback from the people who are actually affected by such disparities. This could be done through case studies, interviews, and even surveys that are distributed to the many residents. This could provide important information and context behind the results we found as well. The actual voices of the affected residents is important to help policymakers make more informed decisions, assuming that actual lived experiences of health inequity could be a good push for them to take initiative for change.

Overall, there are a lot of different directions that future work in this subject can take. Studying these several different initiatives and how they might potentially create better outcomes and change in these communities would be ideal to fight the socioeconomic barriers and disparities. This research is a good stepping stone and starting point toward these initiatives.

## Reproducing
### Data Acquisition
- U.S. Department of Agriculture, Economic Research Service. Food Environment Atlas. https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads
  
  When downloading this dataset, download as a csv file and save two of the different subdatasets, the HEALTH and SOCIOECONOMIC datasets. Save those two as csv files and name them '25_food_env_data_HEALTH' and '25_food_env_data_SOCIOECONOMIC' accordingly, with the csv tag at the end.
  
- Economic Research Service (ERS), U.S. Department of Agriculture (USDA). Food Access Research Atlas, https://www.ers.usda.gov/data-products/food-access-research-atlas/

  When downloading this dataset, download as a csv file for analysis.
  
- Centers for Disease Control and Prevention. (2025, September 16). Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System. Data.CDC.gov. https://data.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7/about_data
  
  When downloading this dataset, download as a csv file and rename it 'nutritional_physical' with the csv tag at the end.
  
### Data Cleaning
#### Python Setup
```
import pandas as pd
import seaborn as sns
import numpy as np
import matplotlib.pyplot as plt
```
#### Load Data - Nutritional + Physical Dataset
```
df1 = pd.read_csv('nutritional_physical.csv')
```
#### Data Filtering
```
df_illinois = df1[df1["LocationAbbr"] == "IL"]
df_illinois_income = df_illinois[df_illinois["StratificationCategory1"] == "Income"]
df_illinois_age = df_illinois[df_illinois["StratificationCategory1"] == "Age (years)"]
df_illinois_race = df_illinois[df_illinois["StratificationCategory1"] == "Race/Ethnicity"]
df_illinois_edu = df_illinois[df_illinois["StratificationCategory1"] == "Education"]
df_illinois_sex= df_illinois[df_illinois["StratificationCategory1"] == "Sex"]
df_illinois_income_obesity = df_illinois_income[df_illinois_income["Class"] == "Obesity / Weight Status"]
df_illinois_income_fruits = df_illinois_income[df_illinois_income["Class"] == "Fruits and Vegetables"]
df_illinois_race_obesity = df_illinois_race[df_illinois_race["Class"] == "Obesity / Weight Status"]
df_illinois_race_fruits = df_illinois_race[df_illinois_race["Class"] == "Fruits and Vegetables"]
```
#### Create Visualizations 
```
income_obesity_means = df_illinois_income_obesity.groupby("Income")["Data_Value"].mean()

# Create bar chart
plt.figure(figsize=(10, 6))
plt.bar(income_obesity_means.index, income_obesity_means.values)
plt.title("Average Obesity Rate by Income in Illinois")
plt.xlabel("Income")
plt.ylabel("Average Data Value")
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```
```
income_fruit_means = df_illinois_income_fruits.groupby("Income")["Data_Value"].mean()

# Create bar chart
plt.figure(figsize=(10, 6))
plt.bar(income_fruit_means.index, income_fruit_means.values)
plt.title("Average Fruit Consumption by Income in Illinois")
plt.xlabel("Income")
plt.ylabel("Average Data Value")
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```
```
race_obesity_means = df_illinois_race_obesity.groupby("Race/Ethnicity")["Data_Value"].mean()

# Create bar chart
plt.figure(figsize=(10, 6))
plt.bar(race_obesity_means.index, race_obesity_means.values)
plt.title("Average Obesity Rate by Race/Ethnicity in Illinois")
plt.xlabel("Race/Ethnicity")
plt.ylabel("Average Data Value")
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```
```
race_fruit_means = df_illinois_race_fruits.groupby("Race/Ethnicity")["Data_Value"].mean()

# Create bar chart
plt.figure(figsize=(10, 6))
plt.bar(race_fruit_means.index, race_fruit_means.values)
plt.title("Average Fruit Consumption by Race/Ethnicity in Illinois")
plt.xlabel("Race/Ethnicity")
plt.ylabel("Average Data Value")
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```
#### Analyzing the Health Dataset
```
# Analyze Data Table
fed_health_df = pd.read_csv('25_food_env_data_HEALTH.csv')
IL_fed_health_df = fed_health_df[fed_health_df['State'] == 'IL']
focus_health_columns = ["FIPS", "State", "County", "PCT_OBESE_ADULTS22", "PCT_HSPA21", "RECFAC20", "RECFACPTH20", "PCH_RECFACPTH_16_20"]
focused_IL_health_df = IL_fed_health_df[focus_health_columns]
focused_IL_health_df
```

#### Analyzing the Socioeconomic Dataset

```
fed_socioeconomic_df = pd.read_csv('25_food_env_data_SOCIOECONOMIC.csv')
IL_fed_socioeconomic_df = fed_socioeconomic_df[fed_socioeconomic_df['State'] == 'IL']
focus_socioeconomic_columns = ["FIPS", "State", "County", "PCT_NHWHITE20", "PCT_NHBLACK20", "PCT_HISP20", "PCT_NHASIAN20", "PCT_65OLDER20", "PCT_18YOUNGER20", "POPLOSS15", "METRO23", "MEDHHINC21", "POVRATE21", "DEEPPOVRATE21", "CHILDPOVRATE21", "DEEPCHILDPOVRATE21"]
focused_IL_socioeconomic_df = IL_fed_socioeconomic_df[focus_socioeconomic_columns]
focused_IL_socioeconomic_df
```

#### Integrate the Datasets

```
# Integration
merged_df = focused_IL_health_df.merge(focused_IL_socioeconomic_df, on=['FIPS', 'State', 'County'], how="inner")

merged_df.head()

foodaccess_merged_df = focused_IL_health_df.merge(
    focused_IL_socioeconomic_df, on=["FIPS","State","County"], how="inner"
)
foodaccess_merged_df.info()
food_access_columns = ["RECFAC20", "RECFACPTH20", "PCH_RECFACPTH_16_20"]
for col in food_access_columns:
    foodaccess_merged_df[col] = pd.to_numeric(foodaccess_merged_df[col], errors='coerce')
foodaccess_merged_df[food_access_columns].isnull().sum()
```

```
# Study correlation
corr_food = merged_df.corr(numeric_only=True)[["RECFAC20", "RECFACPTH20", "PCH_RECFACPTH_16_20"]]
corr_food
```
#### Create the Visualizations

```
# Median Income vs. Food Access per Capita
plt.figure(figsize=(8,5))
sns.scatterplot(data=merged_df, x="MEDHHINC21", y="RECFACPTH20")
sns.regplot(data=merged_df, x="MEDHHINC21", y="RECFACPTH20", scatter=False, color='red')
plt.title("Median Income vs Food Access per Capita in Illinois Counties")
plt.xlabel("Median Household Income in 2021")
plt.ylabel("Facilities per 1,000 Residents")
plt.tight_layout()
```

```
# Poverty Rate vs. Food Access per Capita
plt.figure(figsize=(8,5))
sns.scatterplot(data=merged_df, x="POVRATE21", y="RECFACPTH20")
sns.regplot(data=merged_df, x="POVRATE21", y="RECFACPTH20", scatter=False, color='red')
plt.title("Poverty Rate vs Food Access per Capita")
plt.xlabel("Poverty Rate (%)")
plt.ylabel("Facilities per 1,000 Residents")
plt.tight_layout()
```

```
# Poverty Rate vs. Change in Food Access
plt.figure(figsize=(8,5))
sns.scatterplot(data=merged_df, x="POVRATE21", y="PCH_RECFACPTH_16_20")
sns.regplot(data=merged_df, x="POVRATE21", y="PCH_RECFACPTH_16_20", scatter=False, color='red')
plt.title("Poverty Rate vs Change in Food Access (2016–2020)")
plt.xlabel("Poverty Rate (%)")
plt.ylabel("Change in Facilities per 1,000 Residents (2016–2020)")
plt.tight_layout()
```

## References
- U.S. Department of Agriculture, Economic Research Service. Food Environment Atlas. https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads
- Economic Research Service (ERS), U.S. Department of Agriculture (USDA). Food Access Research Atlas, https://www.ers.usda.gov/data-products/food-access-research-atlas/
- Centers for Disease Control and Prevention. (2025, September 16). Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System. Data.CDC.gov. https://data.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7/about_data
