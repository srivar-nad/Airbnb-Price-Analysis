# Airbnb-Price-Analysis-
Multi-Regression Model to Identify Airbnb Price Factors in Top US Tourist States

# 🏡 Airbnb Price Analysis – Multi-Regression on U.S. Tourist States

This project analyzes how different factors affect Airbnb pricing across the **top 10 most-visited U.S. states** using **multiple linear regression**.

We applied a hedonic pricing model to identify which attributes (e.g., number of bedrooms, bathrooms, review scores, amenities) significantly impact Airbnb prices.



## 📊 Project Summary

- **Title**: Airbnb Insights: Multi-Regression Analysis of Price Factors in Top 10 Most Visited US States
- **Tools Used**: R, R Studio
- **Data Source**: [Inside Airbnb](http://insideairbnb.com/)
- **Timeframe**: 2021–2023 (Post-COVID)
- **Methodology**: Linear Regression, Target Transformation, Residual & Multicollinearity Analysis
  


## 🔍 Key Analysis Steps

- Cleaned dataset with 80+ variables and reduced to the most influential 16
- Applied linear regression and then transformed the model (log and sqrt) to fix heteroscedasticity
- Checked for:
  - ✅ Linearity
  - ✅ Independence
  - ✅ Normality
  - ✅ No multicollinearity (via VIF)
- Identified **positively and negatively influential** variables on pricing



## 💡 Insights

### 📈 Positively Influencing Factors
- Accommodates: +$4 per extra guest
- Bedrooms: +$12 per extra bedroom
- Elevator: +$12 per night
- Amenities like TV, dryer, gym: +$25 collectively

### 📉 Negatively Influencing Factors
- Minimum nights
- Host response rate
- On-premise parking (!)
- Shared room type



## License
- This project is open-source and can be modified or redistributed under the appropriate licensing agreement.

---
