# Bengaluru Home Price Prediction

This project demonstrates the complete workflow of data preprocessing, feature engineering, and model training to predict home prices in Bengaluru. The model is built using **Linear Regression**, and the entire process is carried out within a **Jupyter Notebook** environment. The goal is to predict house prices based on a set of input features, with a strong emphasis on data cleaning and model accuracy.

### Project Overview

This is a code-along project inspired by the **Codebasics** YouTube channel. The focus is on learning how to clean and preprocess data, build a machine learning model, and save the trained model for later use. The steps include:

- **Data Cleaning**: Handling missing data, removing outliers, and correcting inconsistencies in the dataset.
- **Feature Engineering**: Creating new features or transforming existing ones to improve the predictive power of the model.
- **Model Training**: We use **Linear Regression** as the core machine learning model to predict housing prices.
- **Model Export**: The trained model is saved using the Python `pickle` library for future use.

Thanks to Codebasics for providing guidance on the approach!

### Dataset

The dataset used for this project is sourced from Kaggle and contains information about housing prices in Bengaluru. It includes various features like the number of bedrooms, size, location, and price per square foot.

- **Dataset Source**: [Bengaluru House Price Data on Kaggle](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data)

### Key Features of the Project

1. **Data Preprocessing**: 
   - Handled missing values.
   - Removed duplicates and outliers.
   - Converted categorical data into numerical format using one-hot encoding.

2. **Feature Engineering**: 
   - Engineered new features to capture more information, such as price per square foot.
   - Reduced the dimensionality of categorical features using techniques like label encoding.

3. **Model Training**:
   - Linear Regression is used to build a predictive model based on the cleaned dataset.
   - Performed cross-validation to validate the model's performance.

4. **Model Export**:
   - The trained model is saved into a `.pkl` file using the `pickle` library so that it can be easily loaded and used for predictions in the future.

### Tools and Libraries

The following Python libraries are used in the project:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib** & **Seaborn**: For data visualization and exploring relationships between features.
- **Scikit-learn**: For building the machine learning model.
- **Pickle**: For saving the trained model.

### How to Run

1. Clone the repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and follow the step-by-step instructions to preprocess the data and train the model.
4. After training, use the saved model for predictions.

### Future Enhancements
- Implement other machine learning models (e.g., Random Forest, Gradient Boosting) to compare performance.
- Incorporate more advanced feature engineering techniques to improve model accuracy.
- Experiment with hyperparameter tuning for better model optimization.

### Credits
Special thanks to [Codebasics](https://www.youtube.com/channel/UCh9nVJoWXmFb7sLApWGcLPQ) for the tutorial and guidance.

