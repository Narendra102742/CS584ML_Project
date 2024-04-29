# Churn Prediction for Spotify

This project aims to predict user churn for Spotify, a music streaming service, using machine learning techniques. The code includes data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and hyperparameter tuning.

## Dataset

The dataset used in this project is a JSON file containing user interaction data with Spotify. It includes information about user actions, demographics, and historical data.

## Dependencies

The following Python libraries are required to run the code:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib

## Code Structure

The code is structured as follows:

1. **Data Loading and Cleaning**: The code starts by loading the dataset from a JSON file and performing initial data cleaning operations, such as handling missing values and removing duplicates.

2. **Exploratory Data Analysis**: Various analyses are conducted to gain insights into user behavior, including daily listening time, number of listening sessions per week, average session duration, unique artists listened to, and playlist diversity.

3. **Feature Engineering**: The code creates several features that could be predictive of user churn, such as user engagement metrics, session statistics, user agent information, page event counts, location data, and more.

4. **Correlation Analysis**: Correlation analysis is performed to identify highly correlated features, which are then removed to avoid multicollinearity.

5. **Feature Transformation**: Certain features are transformed (e.g., log transformation, square root transformation) to improve model performance.

6. **Data Preprocessing**: The dataset is split into training and testing sets, and feature scaling is applied.

7. **Model Training and Evaluation**: The code implements several machine learning models, including Logistic Regression and Random Forest, for churn prediction. Grid search is used for hyperparameter tuning, and model performance is evaluated using metrics such as F1-score and accuracy.

8. **Feature Importance**: The code analyzes and visualizes the importance of features for each trained model, helping to identify the most influential factors for churn prediction.

## Usage

1. Clone the repository or download the code files.
2. Make sure you have the required Python libraries installed.
3. Place the dataset file (`spotify_dataset.json`) in the appropriate location (`C:\Users\naren\OneDrive\Documents\` in this case).
4. Run the code in your Python environment or IDE.
5. The code will preprocess the data, train and evaluate the models, and display the results, including evaluation metrics and feature importance plots.

Note: The code includes file paths and URLs specific to the dataset and resources used in this project. You may need to modify these paths according to your local environment.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
