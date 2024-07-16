# Mental Health Fitness Prediction Project

This project aims to predict the fitness of mental health using machine learning models based on various input features. 
The prediction is done using linear regression and random forest regression models, trained on a large dataset encompassing various countries and spanning multiple years.


## Features

1. **Input Features**
   - **Drug Use**: Data on the prevalence and patterns of drug use.
   - **Depressive Symptoms**: Indicators of depressive symptoms within the population.
   - **Alcohol Consumption**: Levels of alcohol consumption.
   - **Year**: The year of the recorded data.
   - **Country**: The country from which the data is sourced.
   - **Anxiety Symptoms**: Indicators of anxiety symptoms within the population.
   - **Eating Habits**: Data on eating habits and disorders.

2. **Prediction Models**
   - **Linear Regression**: A simple linear approach to model the relationship between input features and mental health fitness.
   - **Random Forest Regression**: An ensemble learning method using multiple decision trees to improve prediction accuracy and handle non-linear relationships.

## Technical Stack

- **Programming Language**: Python
- **Libraries**:
  - **Pandas**: For data manipulation and analysis.
  - **NumPy**: For numerical computations.
  - **Scikit-Learn**: For machine learning algorithms and model evaluation.
  - **Matplotlib/Seaborn**: For data visualization.

## Project Workflow

1. **Data Collection and Preprocessing**
   - Collect a large dataset containing the input features across various countries and years.
   - Handle missing values, normalize/scale features, and encode categorical data (e.g., country names).

2. **Exploratory Data Analysis (EDA)**
   - Visualize the data to understand distributions, correlations, and patterns.
   - Generate summary statistics to gain insights into the dataset.

3. **Model Training**
   - Split the dataset into training and testing sets.
   - Train the linear regression model on the training data.
   - Train the random forest regression model on the training data.
   - Perform hyperparameter tuning for the random forest model to optimize performance.

4. **Model Evaluation**
   - Evaluate both models using metrics like Mean Squared Error (MSE), R-squared, and others.
   - Compare the performance of linear regression and random forest regression.

5. **Prediction and Analysis**
   - Use the trained models to predict the fitness of mental health on new, unseen data.
   - Analyze the results and interpret the impact of different input features on mental health fitness
