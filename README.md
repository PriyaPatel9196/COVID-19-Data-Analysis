# COVID-19 Data Analysis
This repository contains the analysis performed on COVID-19 data, focusing on the conditions contributing to COVID-19 deaths across different demographics and locations in the United States. The purpose of this analysis was to uncover insights into the factors contributing to COVID-19 mortality and provide data-driven recommendations for public health strategies and policy decisions.
## Project Overview
This project utilizes real-world data on COVID-19 deaths and contributing conditions from the Centers for Disease Control and Prevention (CDC). The goal of this analysis was to understand the impact of various conditions on COVID-19 deaths, analyze geographical variations, and develop predictive models to support public health officials and policymakers in targeting interventions effectively.
## Repository Structure
This project files are divided between the following folders:
1. Project Management: Contains the project brief which outlines the objective and expectations of the analysis.
2. Data: Separated into two subfolders Original Data and Prepared Data. These cintains the original data frames and the data frames after they have been cleaned and prepared for analysis respectively. (Data files not uploaded to GitHub due to size).
3. Scripts: The Jupyter notebooks containing the coding for the analysis.
4. Analysis: The Visualizations folder contains the visualizations used for developing and explaining insights.
5. Sent to Client: Includes the Tableau Public storyboard as a PDF file.
## Key Questions
● What are the most common conditions contributing to COVID-19 deaths is different age group?

● Which group have highest death and which conditions contributing to COVID-19 deaths?

● Which states have highest specific conditions contributing to COVID-19 deaths?

● What are the regional patterns and which region have highest COVID-19 deaths?

● Which month or season has highest COVID-19 deaths?

● How have COVID-19 death rates and contributing conditions changed over time?

● What factor are most predictive of COVID-19 death rates?
## Tools
● Python: Primary programming language used for data analysis.

● Panads: For data manipulation and analysis.

● NumPy: For numerical operations.

● Matplotlib & Seaborn: For generating data visualizations.

● Scikit-learn: For implementing machine learning models.

● Statsmodels: For time series analysis and ARIMA modeling.

● Geopandas: For geographical data manipulation and visualization.

● Plotly: For interactive visualizations.

● Tableau Public: For creating interactive visualizations and dashboards.
## Visualizations
This project includes various visualizations such as scatter plots, choropleth map, bar charts and time-series plots, which illustrate the impact of differnt conditions on COVID-19 mortality, geographical variations, and temporal trends.
Take a look at the <a href="https://public.tableau.com/app/profile/priya.patel2009/viz/AnalysisofCOVID-19Data_17217830518570/COVID-19DataAnalysis?publish=yes">
                    <button> Tableau Workbook</button>
                    </a> on Tableau Public.
## Analysis Sections
### Initial Data Exploration
● Exploration of the dataset: Understanding the structure and kry statistics.

● Cleaning and preprocessing: Handling missing values, outliers, and data type conversions.
### Geographical Analysis
● Choropleth map: Visualizing total COVID-19 deaths across states.

● Insights: Identifying high-impact regions and patterns.
### Linear Regression Analysis
● Model Building: Developing a regression model to predict COVID-19 deaths based on the number of mentions of conditions.

● Performance Evaluation: Assessing the model using Mean Squared Error (MSE) and R-squared score.

### Cluster Analysis
● K-means clustering: Identifying clusters of states with similar COVID-19 impact.

● Cluster Interpretation: Analyzing the characteristics and severity of each cluster.

### Time Series Analysis
● Trend and Seasonality: Decomposing time series data to identify trends and seasonal patterns.

● Stationarity Check: Performing the Dicky-Fuller test and differencing to achieve stationarity.

● Autocorrelation Analysis: Using ACF and PACF plots to analyze the autocorrelation structure of the time series data.
## Conclustion and Recommendations
The analysis provided actionable insights into the factors contibuting to COVID-19 mortality, highlighting the importance of demographic and condition-specific factors. The findings support targeted public health interventions and resource allocation strategies to better prepare for future health crises.
## Limitations and Potential Biases
● Provisional Nature of Data: Data is provisional and conclusions may need revision as finalized data becomes available.

● Reporting Delays: Delays in reporting can affect the completeness of recent data.

● Inconsistent Reporting Standards: Variability in state-level reporting standards may impact reliability.

● Multiple Conditions: Presence of multiple conditions per death complicates analysis.

● Double Counting Risk: Deaths involving multiple conditions are counted in each relevant category.

● Population Data: Analysis is based on 2020 population data, which may not reflect changes over time.
## Recommendations for Future Work
● Enhanced Clustering: Perform clustering analyses on additional conditions and demographics.

● Predictive Modeling: Develop models to identify high-risk populations and enhance public health strategies.
