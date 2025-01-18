Titanic Survival Prediction Model
Overview

In this project, I built a machine learning model to predict whether passengers survived the Titanic disaster, using the original dataset from Kaggle. I tried out different algorithms to see which one would give the best results. The models I used include Gradient Boosting Classifier, Logistic Regression, Random Forest Classifier, and Decision Tree Classifier. The goal was to predict survival, and the final model rankings reflect how well each algorithm performed.
Model Rankings

Here’s how the models stacked up based on accuracy:

    Gradient Boosting Classifier: 84.30%
    Logistic Regression: 82.96%
    Random Forest Classifier: 81.17%
    Decision Tree Classifier: 74.00%

Dataset

I used the original Titanic dataset from Kaggle, which contains features like:

    Passenger’s age
    Gender
    Class (Pclass)
    Fare
    Embarked port
    Family size
    and more.

Technologies Used

    Programming Language: Python
    Libraries:
        pandas: For data manipulation and analysis
        scikit-learn: For building and evaluating machine learning models
        matplotlib & seaborn: For creating charts and visualizations

Process

Here’s the workflow I followed:

    Data Cleaning: I handled missing values using mean, median, and mode based on the type of data.
    Exploratory Data Analysis (EDA): I took a deep dive into the data to understand the distributions and patterns, using visualizations like histograms and pairplots.
    Feature Engineering: Some features were transformed or new ones were created to improve model performance.
    Modeling: I trained multiple models to predict whether a passenger survived or not.
    Evaluation: After training, I compared the models based on accuracy and ranked them accordingly.

Results

The Gradient Boosting Classifier came out on top with an accuracy of 84.3%, followed closely by Logistic Regression (82.96%). Random Forest Classifier and Decision Tree Classifier were a bit behind in performance.
How to Run

    Clone the repository.
    Install the required dependencies:

pip install -r requirements.txt

Run the notebook or Python script:

    python titanic_model.py

Conclusion

This project was a great exercise in predicting Titanic survival using machine learning. While Gradient Boosting Classifier performed the best, all models showed valuable insights. There’s room for improvement, though—tuning the models and selecting the right features could make a big difference.
