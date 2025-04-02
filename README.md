## Project_Investment_Opportunity_Analysis_EDA_Vietnamese
### Building an Investment Opportunity Analysis Model (Investment Opportunity Analysis - EDA)

Other projects : [Projects Introduction](https://github.com/ViaThanh/1-Projects-Introduction), [Sales Data Cleaning&Analysis SQL](https://github.com/ViaThanh/2-Sales-Data-Cleaning-and-Analysis-with-SQL), [Users Behaviours Analysis](https://github.com/ViaThanh/3-Netflix-Users-Behaviours-Analysis)
#### Objective:
- Analyze data to select the appropriate country, sector, and type of investment
- Strategy: invest where others are also investing

#### Data:
Source: This project uses the Investment Analysis dataset, sourced from Kaggle. The original dataset was provided by [ASHISH] and is available on Kaggle. [https://www.kaggle.com/datasets/ashydv/investment-analysis/data].

- The data consists of 03 files: rounds2.csv, mapping.csv, and companies.txt
- companies.txt contains information about companies: homepage, category_list, country, etc.
- mapping.csv: maps business sectors
- round2.csv: contains information about investment rounds

#### Requirements:
- Download and load the data into the program
- Perform data statistics such as max, min, mean, etc.
- Carry out data preprocessing: cleaning, filling in missing data, merging datasets, and correcting data discrepancies, etc.
- Analyze the type of investment: compare typical investment amounts in venture, seed, angel, private equity rounds, etc.
- Analyze by country: identify the countries that have received the most investments in the past.
- Analyze by sector: analyze the investment distribution across eight main sectors (mapping.csv file).

*Note: The 'main sectors' are stored in mapping.csv. However, companies.txt and round2.csv contain many sub-sectors, so the mapping file was merged to integrate sub-sectors into main sectors.*

**Tools:**
Jupyter Notebook for data processing
Power BI for creating visual reports

#### About the project:

**Conclusion:**
In this project, we conducted a study using Exploratory Data Analysis (EDA) to analyze the investment opportunity model across different sectors. Through meticulous analysis and the application of EDA techniques, we gained a comprehensive and in-depth understanding of the market structure and characteristics, thus identifying:
+ Type of Investment: The most suitable investment type identified through the analysis is Venture. This investment type has shown significant potential for returns and is the preferred choice in most funding rounds.
+ Country Analysis: The United States emerges as the leading country for investment activities, with the highest number of funding rounds and total investment amounts. This indicates that the U.S. market is highly active and is an ideal place for venture capital investments.
+ Sector Analysis: The sectors with the most significant investment activities include 'Others,' 'Cleantech/Semiconductors,' and 'Social, Finance, Analytics, and Advertising.' These sectors are attracting considerable attention from investors, making them potential investment targets.
<p align="center">
  <img src="https://github.com/ViaThanh/4-Data-Preprocessing-and-Investment-Opportunity-Analysis/blob/main/Number%20of%20Investment.png" width="400">
  <img src="https://github.com/ViaThanh/4-Data-Preprocessing-and-Investment-Opportunity-Analysis/blob/main/Total%20Invested%20Amount.png" width="400">
</p>

**Based on the findings from the analysis, the following action recommendations are made:**
+ Focus on Venture Investments: Given the high performance and popularity of venture capital investments, this investment type should be prioritized to maximize returns.
+ Target the U.S. Market: With the U.S. showing the strongest investment activity, investment efforts should be concentrated in this market, especially in sectors that have demonstrated strong growth.
+ Invest in High-Growth Sectors: Investments should be expanded into sectors like 'Cleantech/Semiconductors' and 'Social, Finance, Analytics, and Advertising.' These sectors have shown great potential and could provide high returns in the future.

#### Visualization:
This project includes a report created with Power BI to provide interactive and insightful visualizations. It features various charts and graphs to display trends and patterns in the data, helping users easily understand and explore relationships between variables in the dataset.
<img src="https://github.com/ViaThanh/Project_Investment_Opportunity_Analysis_Vietnamese/blob/52ab957a1a861f6af67a521d6b4368a0918094bd/IOA_EDA.png" width="400">


The idea for data processing and analysis is inspired by investment opportunity analysis based on available datasets from Kaggle. [Link1](https://www.kaggle.com/code/absheer/investment-data-cleaning-and-understanding), [Link2](https://www.kaggle.com/code/anuranchowdhury/spark-fund-investment-analysis-eda), [Link3](https://www.kaggle.com/code/kerneler/starter-investment-analysis-69cfb24d-6), [Link4](https://www.kaggle.com/code/ashydv/investment-opportunity-analysis-eda)

