# Status Report - Socioeconomic Factors and Access to Nutrition in Illinois

**Data quality assessment**
Centers for Disease Control and Prevention. (2025, September 16). Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System. Data.CDC.gov. https://data.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7/about_data 

Accuracy: To check the accuracy of the dataset, an external source was used. https://www.americashealthrankings.org/explore/measures/Obesity/IL shows that the obesity rate of adults in Illinois was 36%. And, in the dataset, the obesity rate of adults in Illinois was 33.89%. It was not the same as the external source, however, it can be considered accurate for our explorations. 

Completeness: Of the data that we need, which is the data of Illinois state, there are 215 rows of incomplete data. However, there are 1932 rows of data of illinois state, meaning that the incompleteness of the data we needed is only 10%. So, the completeness of this dataset is good for use. 

Timeliness: The dataset includes data from 2011 to 2023, which covers the years we want to investigate. 

Consistency: The consistency was checked by checking if there are any logic errors in the dataset, by checking whether there is Data_Value lower than Low_Confidence_LImit or higher than High_Confidence_Limit. After checking, there are no logic errors in the dataset. So the consistency of this dataset is good. 

Fit for use: Overall, this dataset is fit for use, but does require a little bit of cleaning, such as getting rid of the data of the states that we’re not interested in and also deal with the missing values. 

Economic Research Service (ERS), U.S. Department of Agriculture (USDA). Food Access Research Atlas, https://www.ers.usda.gov/data-products/food-access-research-atlas/

Accuracy: To assess the accuracy of this dataset, I analyzed the documentation of the dataset. I noticed that information for the dataset was taken from a 2019 list of official supermarkets, accompanied by several census data that included the given information. For these reason, I assessed that the dataset could be accurate and trustworthy, but there is definitely more exploration that could be done for accuracy by checking external sources.

Completeness: The dataset was mostly complete. For the socioeconomic section of the dataset, there were no null values detected for the state of Illinois and the columns I chose to focus on. For the health section of the dataset, there were some null values for columns that were not completely important or related that we chose to focus on. I found that the dataset was overall good for use, and a form of imputation could be implemented if needed.


Timeliness: The dataset mostly covered data from 2019.

Consistency: The consistency of the dataset was good. Checking between the different datasets/sections of the overall dataset, Illinois rows were consistent, as well as each row key. This told me that I could trust the different datasets to be integrated smoothly with each other.

Fit for use: Overall, I would say the dataset was fit for use. I think more exploration of accuracy and consistency could be good. For example, I could explore separate datasets to test these metrics, but I would say that it was good overall.

**Data Cleaning**

The Food Environment Atlas Data (2025) includes nine different datasets within the overall file. This includes datasets on: Access, Stores, Restaurants, Assistance, Insecurity, Taxes, Local, Health, and Socioeconomic data. 

**The Health Dataset**

The Health dataset focuses on data specific to health metrics like obesity rate, as well as metrics relating to physical activity access among a community. It is important to analyze these metrics with respect to the different counties also included. In specific, we will be analyzing these metrics in Illinois and comparing the data among the different counties. This will allow us to get a better scope on our research question which is specific to the different counties in Illinois and how different socioeconomic factors affect nutritional and physical health throughout the state.

When starting the data cleaning, it was very important to take the research question into consideration. The first task in data cleaning was to minimize the dataset to only focus on the State of Illinois. The original dataset was at 3144 rows (including all the states), and after minimizing the scope to Illinois, the dataset shrank to 102 rows. This makes the dataset a lot easier to interpret. The next step was to narrow down which columns I thought might be most important. I decided to narrow this down to “FIPS” (the Primary Key for future integration steps), “State”, “County”, "PCT_OBESE_ADULTS22", "PCT_HSPA21", "RECFAC20", "RECFACPTH20", "PCH_RECFACPTH_16_20"
The overall gist of the columns chosen covers obesity and diabetes rates in adults, as well as physical activity trends among them. It was also important to include the columns that cover access to fitness resources as that could count as a socioeconomic factor. Some areas may have overall better access to self-care resources such as fitness resources.

Lastly, I decided to finish cleaning the dataset by looking for null values. The data source stated that null values were denoted either by “N/A” and “-9999”, and when searching through the dataset to see how prevalent they were, I found that there were 59 total rows to include null values, only for access to fitness resources, “RECFAC20”, “RECFACPTH20”, and “PCH_RECFACPTH_16_20”. I debated whether to keep the rows with null values or not, and decided keeping them would be better as the access to fitness resources is more of a background attribute.

**The Socioeconomic Dataset**
The Socioeconomic dataset focuses on data specific to socioeconomic metrics such as race, age, and income levels across different counties throughout the United States. Like mentioned earlier, we will only be focusing on counties in Illinois to get a more focused scope on our research question.

The first task in data cleaning for this dataset was minimizing to only focus on data in Illinois. Similarly to the Health dataset, this caused the number of rows to shrink down to 102 rows. Again, this makes the dataset a lot easier to interpret. I then also narrowed down the columns I wanted to focus on to: 

"FIPS", "State", "County", "PCT_NHWHITE20", "PCT_NHBLACK20", "PCT_HISP20", "PCT_NHASIAN20", "PCT_65OLDER20", "PCT_18YOUNGER20", "POPLOSS15", "METRO23", "MEDHHINC21", "POVRATE21", "DEEPPOVRATE21", "CHILDPOVRATE21", "DEEPCHILDPOVRATE21"

I narrowed it down to these columns because they were more focused on specific demographics, age groups, and poverty rates which are all socioeconomic factors that we figured might be useful for our study. Lastly, I noticed that there were no null values in the dataset, so it was cleaned and ready to be put to use.


**Contributions**  
Lillian:   
I worked on the dataset that's about behavioral risk factor. The main thing I was working with this dataset was to explore the relationships between each factors, which would be helpful to our project. From this process, I found that Race/Ethnicity is related to how much people are consuming fruits and vegetables. And, I also looked at the relationship between obesity rates and people's income, trying to see if income is a big factor when it comes to obesity. Using this dataset's exploration analysis, we were able to know what socioeconomic factors we wanted to focus on in order to complete this project in a more more efficient way. After EDA, I then worked documenting the data quality of this dataset, using the four criteria taught in class.

Grace:

I worked on the dataset about food access data and several different factors related to the topic such as several different socioeconomic factors (The Socioeconomic Dataset) and health related factors (The Health Dataset). My main goal with the two datasets within this overall dataset was to find what features may help us find underlying patterns regarding a population’s nutritional status and food access and their relationship with several different socioeconomic factors. It was helpful to look at all of the different variables within the different datasets and consider how they may work together overall.
