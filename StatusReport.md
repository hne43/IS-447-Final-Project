**Data quality assessment**
Centers for Disease Control and Prevention. (2025, September 16). Nutrition, Physical Activity, and Obesity - Behavioral Risk Factor Surveillance System. Data.CDC.gov. https://data.cdc.gov/Nutrition-Physical-Activity-and-Obesity/Nutrition-Physical-Activity-and-Obesity-Behavioral/hn4x-zwk7/about_data 

Accuracy: To check the accuracy of the dataset, an external source was used. https://www.americashealthrankings.org/explore/measures/Obesity/IL shows that the obesity rate of adults in Illinois was 36%. And, in the dataset, the obesity rate of adults in Illinois was 33.89%. It was not the same as the external source, however, it can be considered accurate for our explorations. 

Completeness: Of the data that we need, which is the data of Illinois state, there are 215 rows of incomplete data. However, there are 1932 rows of data of illinois state, meaning that the incompleteness of the data we needed is only 10%. So, the completeness of this dataset is good for use. 

Timeliness: The dataset includes data from 2011 to 2023, which covers the years we want to investigate. 

Consistency: The consistency was checked by checking if there are any logic errors in the dataset, by checking whether there is Data_Value lower than Low_Confidence_LImit or higher than High_Confidence_Limit. After checking, there are no logic errors in the dataset. So the consistency of this dataset is good. 

Fit for use: Overall, this dataset is fit for use, but does require a little bit of cleaning, such as getting rid of the data of the states that we’re not interested in and also deal with the missing values. 

**Data Cleaning**

The Food Environment Atlas Data (2025) includes nine different datasets within the overall file. This includes datasets on: Access, Stores, Restaurants, Assistance, Insecurity, Taxes, Local, Health, and Socioeconomic data. 

**The Health Dataset**

The Health dataset focuses on data specific to health metrics like obesity rate, as well as metrics relating to physical activity access among a community. It is important to analyze these metrics with respect to the different counties also included. In specific, we will be analyzing these metrics in Illinois and comparing the data among the different counties. This will allow us to get a better scope on our research question which is specific to the different counties in Illinois and how different socioeconomic factors affect nutritional and physical health throughout the state.

When starting the data cleaning, it was very important to take the research question into consideration. The first task in data cleaning was to minimize the dataset to only focus on the State of Illinois. The original dataset was at 3144 rows (including all the states), and after minimizing the scope to Illinois, the dataset shrank to 102 rows. This makes the dataset a lot easier to interpret. The next step was to narrow down which columns I thought might be most important. I decided to narrow this down to “FIPS” (the Primary Key for future integration steps), “State”, “County”, "PCT_OBESE_ADULTS22", "PCT_HSPA21", "RECFAC20", "RECFACPTH20", "PCH_RECFACPTH_16_20"
The overall gist of the columns chosen covers obesity and diabetes rates in adults, as well as physical activity trends among them. It was also important to include the columns that cover access to fitness resources as that could count as a socioeconomic factor. Some areas may have overall better access to self-care resources such as fitness resources.

Lastly, I decided to finish cleaning the dataset by looking for null values. The data source stated that null values were denoted either by “N/A” and “-9999”, and when searching through the dataset to see how prevalent they were, I found that there were 59 total rows to include null values, only for access to fitness resources, “RECFAC20”, “RECFACPTH20”, and “PCH_RECFACPTH_16_20”. I debated whether to keep the rows with null values or not, and decided keeping them would be better as the access to fitness resources is more of a background attribute.

**The Socioeconomic Dataset**

**Contributions**

Lillian: 

I worked on the dataset that's about behavioral risk factor. The main thing I was working with this dataset was to explore the relationships between each factors, which would be helpful to our project. From this process, I found that Race/Ethnicity is related to how much people are consuming fruits and vegetables. And, I also looked at the relationship between obesity rates and people's income, trying to see if income is a big factor when it comes to obesity. Using this dataset's exploration analysis, we were able to know what socioeconomic factors we wanted to focus on in order to complete this project in a more more efficient way. After EDA, I then worked documenting the data quality of this dataset, using the four criteria taught in class.

