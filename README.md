#📌 Quality of Life Prediction using Machine Learning
A machine learning project that analyzes various factors affecting the quality of life across different countries. The project explores economic, environmental, and social variables to predict quality of life scores.

📂 Project Structure
notebooks/ → Jupyter Notebooks with data analysis, visualization, and modeling
src/ → Python scripts for data processing and modeling
data/ → (Optional) Datasets used in the project
images/ → Visualizations (e.g., SHAP plots, boxplots before and after outlier removal)
models/ → Saved machine learning models (if applicable)
🔍 Key Insights
Climate Value and Income-to-Property Ratio are the strongest predictors of quality of life.

A favorable climate improves health, supports outdoor activities, and enhances well-being.
Affordable housing (higher income-to-property ratio) reduces financial stress and improves living conditions.
Purchasing Power Value positively impacts Quality of Life.

Higher purchasing power allows better access to healthcare, education, and leisure.
Pollution negatively affects quality of life, reinforcing the importance of environmental policies.

📊 Machine Learning Approach
Preprocessing: Handled missing values, applied log transformation, and normalized features.
Feature Engineering: Created meaningful variables like Income_to_Property_Ratio and Safety_to_Pollution_Ratio.
Modeling: Used regression models (e.g., Random Forest, XGBoost) to predict Quality of Life.
Feature Importance: SHAP analysis reveals Climate Value and Income-to-Property Ratio as top influencers.

📜 License
MIT License – Feel free to use and modify this project.
