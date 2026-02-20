# Coffee Quality Prediction Analysis

## Overview
This self-directed project used open-source coffee quality data to apply core machine learning techniques. The analysis focused on relationships between sensory measures, using geospatial analysis to explore regional trends, regression to predict one score from others, clustering to identify sensory profiles, and time series analysis to examine seasonal patterns and production stability.

## Tools
- **Python** (Jupyter | Anaconda) – Scripting Environment
- **pandas | numpy | os** – Data Manipulation
- **matplotlib | seaborn | pylab** – Plotting | Visualisation
- **scikit-learn | statsmodels** – Machine Learning | Statistical Modelling
- **folium** – Geospatial Visualisation
<!--- **Tableau** – Dashboard Design-->

## Process
- **Preparation** - Exploratory Data Analysis | Data Wrangling | Aggregation | Subsetting
- **Analysis** - Linear Regression | Clustering (K-Means) | Model Evaluation | Time Series Analysis | Stationarity Testing | Lag Analysis | Geospatial Analysis

## Data
This analysis uses a modified version of data originally sourced from the **Coffee Quality Institute**, made available on **Kaggle**.

- [**Coffee Quality Dataset**](https://www.kaggle.com/datasets/adampq/coffee-quality-with-locations-of-origin/data) – Bean origin, variety, altitude, processing method, physical attributes, flavour metrics, and total quality score, with geospatial coordinates for most entries.
    
The Dataset was accessed on 02 November 2024.

<!-- ## Deliverables
- **Tableau Dashboard**

## Key Insights
### 1. Which countries produce the best coffee?


### 2. Can certain measures be used to predict the scores of others?


### 3. Is there a higher demand for coffee with better quality scores? -->


## Takeaways
### Successes
The project successfully explored relationships between sensory quality measures and revealed patterns in global coffee scoring through geospatial, predictive, and clustering techniques. It demonstrated that certain metrics can be used to predict others with reasonable accuracy and provided a practical opportunity to apply regression, clustering, and time series methods to open-source data.

### Challenges
The dataset lacked the granularity required to assess consumer demand relative to quality scores. This limited the ability to explore market dynamics and highlighted the importance of defining analytical objectives and data requirements clearly at the start of a project.

### Way Forward
Future iterations should focus on sourcing a dataset that includes pricing, volumes sold, or export trends to better assess demand. Additionally, experimenting with alternative modelling techniques may improve predictions for less correlated attributes. A revised Tableau dashboard is planned to enhance visual storytelling and consolidate key insights from the notebooks into an interactive format.
