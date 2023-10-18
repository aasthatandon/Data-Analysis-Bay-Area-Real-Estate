# Data-Analysis-Bay-Area-Real-Estate

Data Analysis of the Bay Area Real Estate Market

### Problem Statement : 

The Bay Area Real Estate market has witnessed significant fluctuations in housing prices over the years, with recent events such as the pandemic and economic changes impacting the trends. This project aims to conduct a comprehensive data analysis of the real estate market in the Bay Area to uncover patterns, trends, and insights that can help stakeholders make informed decisions.

### Research Questions:

1. Price Variation by Nearby Places : How proximity to park, restaurant, and groceries impact housing prices in specific areas.
2. COVID-19 and Price Fluctuations :  Compare bay area real estate prices before, during, and after the COVID-19 pandemic (2019-2022).
3. Property price vs. Inflation/Interest Rates and Correlation : Explore the impact of inflation and interest rates on property prices in selected regions.
4. Prediction Modeling : Develop a predictive model for forecasting future property prices using historical data and relevant factors.
5. Investor Perspective : Identify criteria investors consider when evaluating properties for investment.

### Analysis Perfomed :

• Web scraping Redfin website for data retrieval.<br>
• Cleaning and preprocessing raw data to ensure accuracy.<br>
• Conducting exploratory analysis and data visualization to identify trends.<br>
• Applying statistical and data analysis methods to address research questions.<br>
• Developing regression model to forecast future prices.<br>
• Generating insights and recommendations tailored to stakeholders, including investors, homebuyers, and sellers in the Bay Area real estate market.

### Files Overview :
#### Referring Step wise files based on the analysis performed <br>

#### Data Collection :
1. Under Code Folder, ```Webscraping_Redfin.ipynb``` : Contains the web scraping code used to extract data from Redfin. Once you run these file, you would get data in two steps.<br>
2. Under Data Folder/Step1_Data Collected/  Folder, ```redfin_2023-09-29-20-15-24_sanjose.csv``` : Intial set of data collected for San Jose from webscraping.Similar steps for all the locations.<br>
3. Under Data Folder/Step2_Data Collected/ Folder , ```redfin_san_jose_final.csv```: Final Dataset for San Jose. Concatenated data from Step1 in this already. Similar steps to be repeated for each bay area location.<br>

#### Data Exploration and Analysis :
1. Under Code Folder, ```Exploration_Analysis.ipynb``` : Contains the scripts used for initial data analysis and exploration.<br>
2. Under Data/Collated_Cleaned Files Folder, ```combined_california2_data``` : This CSV file comprises the raw, combined data of all houses in the Bay Area location.<br>
3. Under Data/Collated_Cleaned Files Folder, ```cleaned1_df.csv``` : This file contains the cleaned and prepared dataset for analysis.<br>

#### Predictive Model : 
1. Under Code Folder, ```Data_Modeling.ipynb``` : Encompasses the modeling code.<br>
2. Under Data/Collated_Cleaned Files Folder, ```q6_file``` : This CSV is utilized in the modeling code.

#### Presentation:
Under Presenatation Folder, ```BAN 612_Group1_Final Project.pdf``` : Project Presentation to discuss the insights and recommendations.


