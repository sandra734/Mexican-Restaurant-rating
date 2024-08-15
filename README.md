# Mexican-Restaurant-rating Analysis
## Project Overview
This project centers on the evaluation of a dataset detailing restaurant ratings in Mexico, with the objective of identifying what drives customer satisfaction and pinpointing areas that need improvement. The dataset includes information on restaurant details, customer demographics, preferences, and reviews. Through the analysis of this data, the project seeks to discover trends and insights that will support business owners and investors in making data-driven decisions. The end goal is to enhance customer experiences, boost restaurant success, and provide strategic guidance. The outcomes of this analysis will include visual reports, practical recommendations, and a thorough understanding of consumer preferences and behaviors in the restaurant industry.
## Data Sources 
The data used for this analysis is a data set is Restaurant_ratings [View](https://drive.google.com/file/d/1c1HKM8UTqwWOgexRLOtEJuxjBiA2N6xf/view?usp=drive_link)
## Tools
Excel for data cleaning and exploration.
Powerbi for data Modeling, Analysis and visualization.
## Data cleaning and exploration 
- Load the data 
- Checked for duplicate 
- Handled missing values 
- Deleted unnecessary columns
- Standardized the data
  
## Exploratory data analysis
The exploration phase aimed to answer key questions such as...
- What can you learn from the highest-rated restaurants? Do consumer preferences affect
ratings?
- What are the consumer demographics? Does this indicate a bias in the data sample?
- Are there any demand & supply gaps that you can exploit in the market?
- If you were to invest in a restaurant, which characteristics would you be looking for?
## Data Analysis
### Data modeling 
We added the relationship between the different tables.
![Capture](https://github.com/user-attachments/assets/e84b1bbb-f8f7-4569-8ffb-f95690c0daa5)
### Dax codes used 
``` Dax code
  No_Of_Cities = DISTINCTCOUNT(consumers[City])
  No_OF_consumers = DISTINCTCOUNT(ratings[Consumer_ID])
  No_Of_Orders = COUNT(ratings[Restaurant_ID])
  No_Of_Restaurants = DISTINCTCOUNT(ratings[Restaurant_ID])
```
## Results/Findings
Based on the analysis,
- The highest-rated restaurants include Emilianos, Log Yin, Michiko, and Restaurant Las Mañanitas. Notably, consumer preferences do not significantly influence these ratings, as the most preferred dining establishments tend to focus on Mexican cuisine. In contrast, the top-rated restaurants primarily offer a variety of cuisines that do not include Mexican dishes.
- The dataset exhibits bias, as findings indicate that 66.96% of the sampled restaurants and 63.20% of the sampled consumers  are located in San Luis Potosí.
- ![Consumer](https://github.com/user-attachments/assets/b34d0646-dcf2-41a1-8d07-a2b103427456) ![Restaurant](https://github.com/user-attachments/assets/a3daf583-4300-4824-8c83-ed2cdae08f68)
- The supply gap exists in the market for Mexican cuisine, as the demand for Mexican restaurants significantly exceeds the current supply. Despite Mexican cuisine being the most preferred among consumers, there are not enough establishments to accommodate this preference, highlighting a critical need for more Mexican dining options.
- Characteristics of a sound restaurant investment
   - The restaurant should specialize in Mexican cuisine, as it is the most preferred culinary choice among consumers.
   - To ensure accessibility and attract a wider customer base, the restaurant should be situated close to public transportation hubs.
   - The restaurant should feature a dedicated drinking area or bar, providing patrons with the option to enjoy alcoholic beverages alongside their meals.
   - The restaurant will be designed to be budget-friendly(medium budget), catering to consumers seeking affordable dining options without compromising on quality and service.
## Recommendations 
- Although Mexican cuisine is the most preferred among consumers, the highest-rated restaurants do not primarily serve Mexican dishes. This presents an opportunity for Mexican restaurants to enhance their overall service and dining experience. We recommend that they focus on key factors such as improving service quality, creating a welcoming ambiance, innovating menu options, ensuring consistency in food and service, and actively seeking customer feedback. By addressing these areas, Mexican restaurants can elevate their offerings, improve their ratings, and better align with consumer preferences in a competitive market.
## Limitations 
## References 
- Build a toggle button like a pro [View here](https://youtu.be/5QMpc5fUV2I)

