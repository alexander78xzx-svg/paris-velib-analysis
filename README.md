# Paris Vélib' Data Analysis (May-June 2024)

### Project Overview

This project is an end-to-end data analysis of the Paris Vélib' bike-sharing system. The goal was to take a large raw dataset and transform it into a clean and interactive dashboard to answer key business questions about usage patterns.

----------

### Live Interactive Dashboard

This entire analysis is summarized in a live Tableau Public dashboard. Click the image below to interact with it.

**[Clickable Screenshot of your Tableau Dashboard]** _(Insert a screenshot here, then make it a link by wrapping it: [![Dashboard screenshot](https://imgur.com/mGWeUMm)](https://public.tableau.com/app/profile/alexandru.bodnariuk/viz/velib_analysis_may-june_2024/Dashboard1?publish=yes)_

----------

### Key Questions & Insights

I focused on answering three main questions:

1.  **WHERE are the busiest stations?**
    
    -   **Insight:** The top 10 stations are, as expected, clustered around major transport hubs like Gare de Lyon and Saint-Lazare. 
        
2.  **WHEN are bikes being used?**
    
    -   **Insight:** A clear two-peak commuter pattern emerges on **weekdays** (8-9 AM and 5-7 PM). **Weekends**, however, show a completely different pattern: a long, sustained leisure peak from 2 PM to 7 PM.
        
3.  **WHAT is the usage difference between bikes?**
    
    -   **Insight:** Electric bikes are not just more popular; they are used for significantly **longer trips** (avg. 18 min) compared to mechanical bikes (avg. 11 min), suggesting they are used for new, longer routes, not just replacing short ones.
        

----------

### Tools & Technologies Used

-   **Data Cleaning & Preparation:** **Python** (Pandas, NumPy)
    
-   **Data Analysis:** **Jupyter Notebook**
    
-   **Data Visualization:** **Tableau Public**
    
-   **Version Control:** **Git & GitHub**
    

----------

### Project Structure

-   `analysis.ipynb`: The main Jupyter Notebook containing all Python code for data cleaning, transformation, and feature engineering.
  
    
-   `/datasets`: Folder containing the original raw CSV file.
### Data Source

The raw data  is not included in this repository due to its large size. It can be downloaded directly from the **Kaggle** at: 
https://www.kaggle.com/datasets/pierre4567/bike-sharing-rides-in-paris-vlib 

A small sample of 500 rows (velib_sample.csv) is included in this repo to allow the Python notebook to be run for testing.
