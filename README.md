# Airbnb NYC Pricing & Demand Analysis

## Project Overview
This project aims to uncover key factors influencing Airbnb pricing and demand across New York City, with the goal of predicting profitability and identifying high-potential, investment-worthy listings.

We analyze the spatial distribution of listings, examining how location density correlates with price and availability. External datasets on weather conditions and crime rates are integrated to assess how environmental and safety factors impact Airbnb performance.  

---

## Datasets
- **Airbnb NYC 2019 Listings**: Prices, availability, and neighborhood details  
- **NYC 311 Complaint Reports**: Local complaints for safety and environmental insights  
- **NYC Weather Data**: Temperature, precipitation, and seasonal trends  

---

## Methodology
- **Exploratory Data Analysis (EDA)**: Studied pricing patterns, demand trends, and neighborhood distributions  
- **Feature Engineering**: Combined Airbnb, weather, and crime datasets  
- **Predictive Modeling**: Tested three models for price prediction:
  - **Lasso Regression**: Good for feature selection, achieved 86.63% test accuracy, RMSE = 15,322.36  
  - **Random Forest**: Best-performing model with 99.8% test accuracy, RMSE = 220.79  
  - **Neural Network**: Captured complex patterns but performed worse than Random Forest  

---

## Key Insights
- **Manhattan & Brooklyn**: Average prices are fairly uniform across neighborhoods ($600–$700), with Chelsea, West Village, and Midtown showing higher pricing potential.  
- **Queens & Bronx**: Wider price range; Little Neck and Jamaica Hills average $800–$900, while Breezy Point averages ~$300.  
- **Staten Island**: Significant variation — Woodrow averages ~$80, while New Dorp and Chelsea average ~$1,000. Offers both the lowest-priced and high-investment listings.  
- **Neighborhood Density**: Distribution of listings explains some price discrepancies; areas with sparse listings (like parts of Staten Island) show extreme averages.  
- **Model Performance**: Random Forest captured non-linear relationships effectively, making it ideal for predicting listing profitability and identifying high-ROI neighborhoods.  

---
## Data

Download the zip file to have the 3 files used:

[AirBnB Pricing Project.zip](https://github.com/user-attachments/files/22687205/AirBnB.Pricing.Project.zip)



## Technologies Used 
- Python, Pandas, NumPy
- scikit-learn (Lasso, Random Forest)
- TensorFlow/Keras (Neural Network)
- Matplotlib, Seaborn, Folium (visualizations)
## Conclusion

The Random Forest model emerged as the most accurate solution, suggesting tree-based ensemble methods are particularly suited for capturing complex relationships in NYC Airbnb data. Insights from this analysis can guide investors and property managers toward high-potential listings while accounting for neighborhood dynamics and external factors.

