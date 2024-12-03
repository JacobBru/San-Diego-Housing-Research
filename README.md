# **Predicting Housing Prices in San Diego, CA**  

This repository contains my project aimed at predicting future housing prices in San Diego, CA, using historical data and data science techniques. By analyzing trends in price-per-square-foot data, this project offers valuable insights for potential homebuyers, real estate professionals, and investors navigating the dynamic housing market of San Diego.

---

## **Abstract**  
This project utilizes historical real estate data to develop a predictive model for housing prices in San Diego, CA. By applying data cleaning, exploratory data analysis, and a linear regression model, I’ve identified key trends in property values over time. The findings provide actionable insights, revealing a gradual increase in property values that could assist buyers and investors in making informed decisions.  

---

## **Dataset**  
The dataset used in this analysis was sourced from Kaggle:  
[USA Real Estate Dataset](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset?resource=download)  

This dataset includes property sale prices, square footage, sale dates, and other relevant details. While the data only covers trends up to 2021, it provides a solid foundation for analyzing historical patterns in San Diego's housing market. Future iterations of this project may incorporate real-time data using APIs or updated datasets.  

---

## **Project Approach**  
### **1. Data Preparation**  
- Filtered the dataset to focus on properties in San Diego, CA.  
- Addressed missing values and outliers using techniques like interquartile range (IQR) and visual inspection.  
- Added a new feature, **price per square foot**, for better comparisons across properties of varying sizes.  
- Scaled continuous variables to ensure consistency and improve model performance.  

### **2. Exploratory Data Analysis (EDA)**  
- Analyzed trends in average price per square foot over time, revealing key patterns.  
- Visualized relationships between property features (e.g., bedrooms, bathrooms) and prices using bar plots and line graphs.  
- Identified outliers that impacted model predictions and addressed them to enhance data reliability.  

### **3. Model Development**  
- Built a **Linear Regression Model** using Scikit-Learn to predict price-per-square-foot trends over time.  
- Initially, the model showed a slight downward trend, influenced by outliers. After refining the dataset, the corrected model indicated a gradual upward trend in property values.  
- Evaluated the model’s performance using metrics like R-squared and Mean Squared Error (MSE).  

### **4. Visualizations**  
Key insights were visualized through:  
- **Boxplots**: Highlighted data distribution and outliers.  
- **Line Graphs**: Showed trends in median and average prices over time.  
- **Bar Graphs**: Analyzed price per square foot by bedrooms and bathrooms.  

---

## **Findings**  
- Historical data indicates a gradual increase in the average price per square foot in San Diego.  
- Trends vary by property type and number of bedrooms/bathrooms, but larger homes in the suburbs may influence pricing dynamics.  
- External factors like COVID-19 and economic fluctuations play a role in short-term pricing trends.  

---

## **Tools & Technologies Used**  
- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn  
- **Dataset Source**: Kaggle  

---

## **Conclusion**  
This project highlights the value of data-driven methods in understanding real estate trends. While the analysis suggests an overall upward trend in property values, external factors like economic conditions and policy changes can influence market dynamics. Future iterations of this project could incorporate real-time data and more advanced models to improve prediction accuracy.

---

## **References**  
1. Kaggle Dataset: [USA Real Estate Dataset](https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset?resource=download)  
2. Pandas Documentation: [https://pandas.pydata.org](https://pandas.pydata.org)  
3. Scikit-Learn Documentation: [https://scikit-learn.org](https://scikit-learn.org)  
4. Harris, C. R., et al. (2020). "Array Programming with NumPy." *Nature*.  
