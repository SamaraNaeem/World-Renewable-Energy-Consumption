# World Renewable Energy Consumption (2012–2022) and Forecasting

This project analyses global renewable energy consumption trends from 2012 to 2022 and applies statistical and machine learning techniques to forecast future energy demand. The study explores consumption patterns across energy sources and continents, identifies growth trends, and highlights the global shift toward sustainable energy.

## Project Overview
Renewable energy plays a critical role in addressing climate change and ensuring long-term energy sustainability. This project examines historical renewable energy consumption data, visualises global and regional trends, and forecasts future consumption using mathematical modelling.

The analysis focuses on major renewable energy sources and investigates how consumption patterns differ across continents.

## Objectives
- Analyse global renewable energy consumption trends (2012–2022)
- Compare consumption patterns across renewable energy types
- Study regional differences in renewable energy usage
- Forecast future renewable energy consumption
- Identify clustering patterns in solar and wind energy usage

## Renewable Energy Types Analysed
- Hydroelectric energy
- Wind energy
- Solar energy
- Biofuel energy

## Exploratory Data Analysis
- **Pie Chart:** Shows the distribution of renewable energy sources, with hydroelectric power dominating global consumption (64.1%) :contentReference[oaicite:0]{index=0}
- **Box Plot:** Compares renewable energy consumption across Asia, Europe, and North America, highlighting Asia’s higher and more variable usage

## Time-Series Analysis & Forecasting
- Line plots show a consistent upward trend in renewable energy consumption from 2012 to 2022
- An exponential model is used to fit historical data and forecast future consumption
- The model predicts global renewable energy consumption to reach approximately **220,000 TWh by 2032**

## Statistical Analysis
Statistical moments such as mean, median, standard deviation, skewness, and kurtosis were computed for each energy source. High skewness and kurtosis in solar and wind consumption indicate strong growth potential and increasing variability.

## Clustering Analysis
- **K-Means clustering** was applied to scaled solar and wind consumption data
- Elbow and silhouette methods were used to determine the optimal number of clusters
- Three distinct clusters were identified, representing different renewable energy consumption patterns

### Cluster Interpretation
- **Cluster 0:** Low solar and wind consumption
- **Cluster 1:** High wind and moderate solar consumption
- **Cluster 2:** High solar consumption relative to wind

## Key Findings
- Hydroelectric power is the dominant renewable energy source globally
- Asia leads global renewable energy consumption
- Solar and wind energy show strong growth potential
- Renewable energy consumption exhibits a clear upward global trend
- Distinct regional and consumption patterns exist across energy sources

## Tools & Technologies
- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Statistical analysis
- Time-series forecasting
- K-Means clustering

## Project Structure
- notebooks/ – Data analysis, visualization, and modelling
- figures/ – Plots and charts
- README.md – Project overview

## Conclusion
This project demonstrates a strong global shift toward renewable energy adoption. Forecasting results suggest continued growth in renewable energy consumption, emphasizing the importance of sustained investment in clean and sustainable energy solutions.

## Author
Samara Naeem
