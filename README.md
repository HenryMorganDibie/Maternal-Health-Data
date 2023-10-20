## Maternal-Health-Data
Exploring maternal health data through data analysis and machine learning, predicting blood pressure levels for improved healthcare outcomes.

##  Exploring Maternal Health Data and Predicting Blood Pressure Levels 🩺

In the world of healthcare, data-driven insights are a vital compass for enhancing patient well-being. Join me as I delve into the fascinating journey of delving into maternal health data and harnessing the power of machine learning to forecast blood pressure levels.

 Data Exploration:

Age Group Distribution: I uncovered a diverse set of age groups, with the majority falling in the "<30" age group, followed by "30-39," "40-49," and "50+." This diversity highlights the wide range of ages in our dataset.

Blood Pressure Categories: I categorized the data into "Normal," "Prehypertension," and "Hypertension" based on systolic and diastolic blood pressure values. Categorization is key to understanding and managing health risks.

Blood Pressure and Age Group: I found that average systolic blood pressure tends to increase with age, with individuals in the "40-49" age group having the highest average systolic blood pressure. Age is a significant factor in blood pressure management.

Blood Pressure and Risk Level: The majority of individuals fall into the "Prehypertension" blood pressure category, suggesting the importance of preventive measures. #HealthDataAnalysis

Blood Sugar (BS) and Body Temperature: The data includes various combinations of blood sugar and body temperature values across different age groups. This diverse health metric data offers a comprehensive view of individual health status.

Heart Rate Changes: I also explored heart rate values and changes between consecutive rows, offering insights into cardiovascular health.

Logarithmic and Square Root Transformations: I applied these techniques to 'SystolicBP' and 'DiastolicBP' columns to handle non-linear relationships in the data. #DataPreprocessing

 Machine Learning:

With my data insights in place, I moved on to the machine learning phase.

Data Preprocessing: I preprocessed the data, including imputing missing values, one-hot encoding categorical variables like 'BloodPressureCategory,' and applying feature transformations. #DataPreprocessing

Linear Regression Model: I chose a Linear Regression model to predict systolic blood pressure. The model was trained and evaluated for its predictive performance.

Hyperparameter Tuning: A critical step involved hyperparameter tuning to optimize model performance.

Cross-Validation: To ensure my model's robustness, I employed cross-validation techniques to evaluate its consistency. #MachineLearning

📈 Results:

The Root Mean Squared Error (RMSE) of my predictive model on test data is approximately 1.16. This value provides a measure of the prediction error, with a lower RMSE indicating better predictive accuracy. #DataAnalysis
📚 Key Takeaway:
Combining data exploration with machine learning empowers me to extract valuable insights from healthcare data. My goal is to better understand health trends and ultimately improve healthcare outcomes. 
