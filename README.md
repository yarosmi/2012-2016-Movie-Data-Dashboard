# 2012-2016 Movie Data Dashboard
An Excel dashboard with movie data statistics from 2012-2016.

### Table of Content
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning and Preperation](#data-cleaning-and-preperation)
- [Questions for Data Analysis](#questions-for-data-analysis)
- [Dashboard](#dashboard)
- [Results and Findings](#results-and-findings)
- [Challanges in Analysis](#challanges-in-analysis)

### Project Overview
This data analysis project focuses on uncovering insights of the performance and trends of movies released between 2012 and 2016. Through a comprehensive analysis of various aspects of the movie dataset, the goal is to identify patterns, provide data-driven recommendations, and develop a deeper understanding of the industry's dynamics during this period.

### Data Source
Movie Data: The primary dataset used for this analysis is the [Movies Data Ready for Dashboard.xlsx](https://github.com/yarosmi/2012-2016-Movie-Data-Dashboard/blob/226ebc0650518879ad1c8d56cedfdb90dcd04bb4/Movies%20Data%20Ready%20for%20Dashboard.xlsx) file, containing detailed and cleaned information about each movie such as its' box office performance, genre, cast, directors and more.

### Tools
- Power Query: Used to clean data from the source file.
- Excel
  - Pivot Table: Used tables for data sub-cetegories, slicers and charts/graphs to build the dashbaord and analize data.

 ### Data Cleaning and Preperation
 - Data Loading
 - Data Inspection and Cleaning
 - Data Type Conversion:
   - Ensured consistent data types by converting the formula of the ROI column into % for easier interpretation of box office performance.
 - String Cleaning and Parsing:
   - Removing extra spaces, special characters, and inconsistencies in the dataset for automation legibility.
 - Validation of Cleaned Data:
   - Cross-checked data from Pivot tables for errors or inconsistencies in the cleaned dataset before analysis.
 - The interactive dashboard with post cleaned and prepared data can be downloded here: [Apple TV Movie Data Dashboard](https://github.com/yarosmi/2012-2016-Movie-Data-Dashboard/blob/d1667edb9088bd605ec685a49328fbb740514b03/Apple%20TV%20Movie%20Data%20Dashboard%20-%20Yaraslau%20S.xlsx)

### Questions for Data Analysis
1. What is the most profitable quarter for movies from all combined years and genres?
2. What were the top 5 movies by profit and budget in 2014?
3. Who were the top performing cast in the Action movie genre from from all combined years?
4. What is the most profitable movie from all combined years?

### Dashboard
Preview of how the dashboard will look when you open it: ![Dashboard Screenshot](https://github.com/user-attachments/assets/44eedda5-bc6e-452a-b37e-f6279c615b22)

### Results and Findings
- ![Best Profitable Movie Screenshot](https://github.com/user-attachments/assets/18eccef0-6278-4bff-92bd-53a7be5effcc) Horror dominates in profitability with The Devil Inside's box office revenue of $102,000,000 USD, making it a safe pick for studios targeting high ROI with low budgets.
- Biography, Sports and Musical genres have negative average ROIs, likely due to niche audiences and underperformance.
- Quarter 2 and 3 are the best times to release movies with the exception of seasonal movies.
- Action movies tend to be most popular following Comedy and Adventure genres.
- ROI diminishes with higher budgets, emphasizing the importance of cost control in movie production.
- In the timeline of the dataset, Jennifer Lawrence is the highest grossing movie lead in the top 5 cast while being the only actress, the follwing cast are actors.

### Challanges in Analysis
- Pivot table for showing "Box Office Revenue Based On Month" gave me a hard time shoing just the months flter, upon the creation of the table, Release Date field only showed "Year", "Quarters", "Release Date". There was no option to filter to only months, I had to ungroup the release date column and regroup by months after which the line graph worked as intended.![Grouping By Month Screenshot](https://github.com/user-attachments/assets/8aa3df72-5113-4773-b073-fb0746332e55)

