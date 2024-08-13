# Mini-Project_1_YouTube_Analytics

# **YouTube Statistics Analysis**
- [View detailed notebook](./YouTube_Statistics_Analysis.ipynb)

## Contents

1. **Introduction**
    - Research question.
2. **Data Collection**
    - API setup and data retrieval code.
3. **Data Preprocessing**
    - Cleaning and feature extraction code.
4. **Exploratory Data Analysis (EDA)**
    - Visualizations and initial insights.
5. **Hypothesis Testing**
    - Statistical analysis and results.
6. **Conclusion**
    - Summary of findings and implications.

## **1. Introduction**

- **Primary Question:** Has there been any change in the trend of data science and AI-related videos on YouTube?

*Note: This question can be further explored, but for the purposes of this project, I have focused on this specific aspect.*

## **2. Data Collection**

- **API Key Setup**
    - Required packages and initial API call setup.

- **Data Retrieval**
    - First API call to retrieve YouTube search results for relevant queries.
    - Preprocessing and cleaning of data for further analysis.

## **3. Data Processing**

- **Read CSVs (Clean)**
    - Importing the data and checking the integrity.

- **Initial Exploration of Data**
    - Assessing data types, null values, and initial insights.

- **Data Cleaning**
    - Handling null values, duplicate entries, and unnecessary columns.
    - Extracting dates and creating additional features for analysis.

## **4. Exploratory Data Analysis (EDA)**

- **Numerical Analysis**
    - Summary statistics and overall observations.
    - Detailed analysis of view counts, like counts, and comment counts.

- **Distribution of Numerical Features**
    - Histograms and KDE plots to visualize the distribution of key numerical features.

- **Categorical Analysis**
    - Total view counts per category and yearly trends.
    - Relationship analysis between numerical features like views, likes, and comments.

- **Trend Investigation**
    - Yearly and monthly trends in view counts.
    - Visualization of time series data to identify patterns and anomalies.

## **5. Hypothesis Testing**

- **Null Hypothesis (H0):** The mean view count, like count, and comment count are the same across all years.
- **Alternative Hypothesis (H1):** At least one year's mean view count, like count, or comment count is different from the others.

- **Statistical Tests**
    - Testing for skewness, kurtosis, and performing ANOVA to test for significant differences between years.

## **6. Conclusion**

- **Summary of Findings**
    - The trend in data science and AI-related videos on YouTube has shown statistically significant changes over recent years.
    - There has been an overall decrease in trend, potentially due to various factors including algorithm changes and shifts in viewer interest.

- **Further Investigation**
    - Further analysis could be conducted to understand the reasons behind the decreasing trend.
    - Additional data from 2024 could provide more complete insight.

---

*This project involves analyzing YouTube statistics related to data science and AI to identify trends and patterns over the years. The analysis includes data collection through YouTube API, data preprocessing, exploratory data analysis, hypothesis testing, and drawing conclusions based on statistical tests.*


