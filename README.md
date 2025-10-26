# Middle East Flight Delay Analysis

## Project Overview

This project delves into a real-world dataset of over 240 flights from the Middle East to investigate the key factors contributing to flight delays. Through comprehensive data cleaning, processing, and statistical analysis in Python, the study aims to identify significant patterns, such as the "Weekend Effect," and provide insights that could inform airline operational strategies and improve passenger experience.

## Key Features

*   **Data Cleaning & Preprocessing:** Robust handling of raw flight data using Python (Pandas) to ensure data quality and readiness for analysis.
*   **Exploratory Data Analysis (EDA):** In-depth investigation into flight attributes, delay durations, and potential influencing factors.
*   **Feature Engineering:** Creation of a new `IsWeekend` feature to enable specific analysis of weekend impact on delays.
*   **Statistical Analysis:** Identification of significant patterns, including the "Weekend Effect," and assessment of correlations between various flight parameters and delay times.
*   **Compelling Visualizations:** Utilization of Matplotlib and Seaborn to create a series of informative charts (box plots, heatmaps, bar charts) that effectively communicate complex findings.
*   **Actionable Insights:** Derivation of data-driven conclusions relevant for airline operations, scheduling, and customer communication.

## Technologies Used

*   **Python:**
    *   Pandas (Data manipulation and analysis)
    *   Seaborn & Matplotlib (Data visualization)
    *   Jupyter Notebook (Interactive development environment)
*   **Statistical Analysis:** Application of statistical methods to validate findings and identify significant relationships.

## Data Source

The dataset for this analysis comprises over 240 flight records originating from the Middle East, including information on departure times, arrival times, delay durations, flight distances, airlines, and dates.

**Note:** Due to data privacy and proprietary restrictions, the raw dataset for this project cannot be publicly shared. The analysis and findings presented are based on an internal dataset.

## Analysis & Insights

This analysis uncovered several critical patterns and trends concerning flight delays:

### 1. The "Weekend Effect"

*   A **significant pattern of increased flight delay times was identified on weekends**. This "Weekend Effect" suggests specific operational challenges or demand surges during these periods.
*   Further multivariate analysis, enabled by the engineered `IsWeekend` feature, revealed that **specific airlines were disproportionately affected by the weekend surge in delays**. This points to varying operational resilience among carriers.

### 2. Factors Not Correlated with Delays

*   **Flight Distance:** Analysis demonstrated a **lack of significant correlation between flight distance and delay duration**. This suggests that short-haul and long-haul flights are equally susceptible to delays based on other factors.



## Key Visualisations

The following visualisations were instrumental in understanding and communicating the project's findings:

*   **Bar Plots:** Used to illustrate average delay by day of the week. 
*   **Heatmaps:** Employed to explore potential correlations between numerical variables.
*   **Scatter Plots:** Utilised to show the relationship between flight distance and flight delay.

Here are some examples of the visualizations generated during the analysis:

![Delay Distribution Box Plot]
![Weekend Effect Bar Chart]
![Distance vs Delay Scatter Plot] 

![1760536310673](https://github.com/user-attachments/assets/e1fac241-116e-4efe-95e6-4206ca173bfb)
![1760536310732](https://github.com/user-attachments/assets/28baaf0a-d74d-4639-860a-b6d40ff15197)
<img width="866" height="547" alt="image" src="https://github.com/user-attachments/assets/3b03d417-81a3-42b7-8485-ce4f87decb2b" />
