# 📌 Quality of Life Prediction using Machine Learning

A machine learning project that analyzes various factors affecting the quality of life across different countries. The project explores economic, environmental, and social variables to predict quality of life scores.
## 📦 Dataset  

- **Source**: [Quality of Life for Each Country – Kaggle](https://www.kaggle.com/datasets/ahmedmohamed2003/quality-of-life-for-each-country/data)  
- **Description**: This dataset provides various socioeconomic, environmental, and quality-of-life indicators for different countries worldwide.  

### **Features**  
#### 🌍 Country Information  
- `country` → Name of the country.  

#### 💰 Economic Indicators  
- `Purchasing Power Value` → Numeric score for purchasing power.  
- `Purchasing Power Category` → Qualitative category for purchasing power.  

#### 🛡️ Safety & Health  
- `Safety Value` → Numeric safety index score.  
- `Safety Category` → Qualitative safety category.  
- `Health Care Value` → Numeric score for healthcare quality.  
- `Health Care Category` → Qualitative healthcare category.  

#### 🌤️ Environment & Cost of Living  
- `Climate Value` → Numeric score for climate quality.  
- `Climate Category` → Qualitative climate category.  
- `Cost of Living Value` → Numeric score for cost of living.  
- `Cost of Living Category` → Qualitative cost of living category.  

#### 🏡 Housing & Infrastructure  
- `Property Price to Income Value` → Numeric ratio of property price to income.  
- `Property Price to Income Category` → Qualitative property price-to-income category.  
- `Traffic Commute Time Value` → Numeric score for commute times.  
- `Traffic Commute Time Category` → Qualitative traffic commute category.  

#### 🌿 Pollution & Quality of Life  
- `Pollution Value` → Numeric pollution index score.  
- `Pollution Category` → Qualitative pollution category.  
- `Quality of Life Value` → Numeric score for overall quality of life.  
- `Quality of Life Category` → Qualitative quality of life category.  

### **📊 Data Source**  
Collected from **Numbeo**, a global database providing cost of living, housing indicators, healthcare, traffic, crime, and pollution statistics.  


## 📂 Project Structure
notebooks/ → Jupyter Notebooks with data analysis, visualization, and modeling
src/ → Python scripts for data processing and modeling
data/ → (Optional) Datasets used in the project
images/ → Visualizations (e.g., SHAP plots, boxplots before and after outlier removal)

## 🔍 Key Insights
Climate Value and Income-to-Property Ratio are the strongest predictors of quality of life.

A favorable climate improves health, supports outdoor activities, and enhances well-being.
Affordable housing (higher income-to-property ratio) reduces financial stress and improves living conditions.
Purchasing Power Value positively impacts Quality of Life.

Higher purchasing power allows better access to healthcare, education, and leisure.
Pollution negatively affects quality of life, reinforcing the importance of environmental policies.

## 📊 Machine Learning Approach
Preprocessing: Handled missing values, applied log transformation, and normalized features.
Feature Engineering: Created meaningful variables like Income_to_Property_Ratio and Safety_to_Pollution_Ratio.
Modeling: Used regression models (e.g., Random Forest, XGBoost) to predict Quality of Life.
Feature Importance: SHAP analysis reveals Climate Value and Income-to-Property Ratio as top influencers.

## 📜 License
MIT License – Feel free to use and modify this project.
