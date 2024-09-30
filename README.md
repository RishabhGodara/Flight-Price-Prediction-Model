# Flight-Price-Prediction-Model
This project aims to develop a machine learning model for predicting flight prices based on various factors, including the airline, journey date, duration, and additional features. The key components of this project include:

    Data Preprocessing: Clean and prepare the dataset by handling missing values, encoding categorical variables using Label Encoding, and extracting useful features such as the day of the journey from the date.

    Exploratory Data Analysis (EDA): Perform EDA to understand the relationships between different features and their impact on flight prices. Visualizations such as heatmaps for correlation analysis are employed to identify significant predictors.

    Model Training: Implement multiple regression models, including Ridge Regression, Lasso Regression, and Decision Tree Regressor. Utilize techniques like GridSearchCV for hyperparameter tuning to optimize model performance.

    Performance Evaluation: Assess the models using metrics such as Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and R-Squared values to determine the best-performing model.

    Model Saving and Deployment: Save the trained models using joblib for future predictions on new flight data.

    User Interface: Create a simple interface (could be via a command line or GUI) that allows users to input flight details and receive price predictions.

Features:

    Predict flight prices based on various features.
    Visualization of important correlations and data distributions.
    Comparison of different regression models to select the best one.
    Easy-to-use interface for entering new flight details.

Technologies Used:

    Python
    Pandas, NumPy for data manipulation
    Scikit-learn for model training and evaluation
    Matplotlib, Seaborn for data visualization
    Joblib for model serialization
