# Titanic-Survival-Prediction-Project

## Overview
This project aims to predict the survival of passengers aboard the Titanic using Machine Learning techniques. We implement logistic regression in Python and utilize data visualization libraries to explore and analyze the dataset. The project follows a structured workflow, from data preprocessing to model evaluation, with the goal of achieving an optimal accuracy score.

## Technologies Used
- **Python**: Programming language for implementation
- **Pandas & NumPy**: Data manipulation and numerical operations
- **Seaborn & Matplotlib**: Data visualization
- **Scikit-learn (sklearn)**: Machine learning library for model building
- **Logistic Regression**: Classification model used for prediction
- **Train-Test Split**: Splitting the dataset for training and testing
- **Accuracy Score**: Evaluating model performance

## Dataset
The dataset used in this project is the famous *Titanic* dataset, which contains information about passengers, including:
- Passenger class (Pclass)
- Name, Sex, and Age
- Number of siblings/spouses aboard (SibSp)
- Number of parents/children aboard (Parch)
- Ticket number, Fare, and Cabin (if available)
- Embarkation port (Embarked)
- Survival status (Target variable: 0 = No, 1 = Yes)

## Project Workflow
1. **Data Loading & Exploration**: Understanding the dataset structure using Pandas.
2. **Data Cleaning & Preprocessing**: Handling missing values, feature engineering, and encoding categorical data.
3. **Exploratory Data Analysis (EDA)**: Visualizing distributions, correlations, and survival trends using Seaborn and Matplotlib.
4. **Model Building**:
   - Splitting the dataset into training and testing sets using `train_test_split`
   - Applying Logistic Regression using `sklearn`
   - Training the model on the training dataset
5. **Model Evaluation**:
   - Predicting survival on the test set
   - Calculating accuracy score
   - Analyzing model performance

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   cd titanic-survival-prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python titanic_prediction.py
   ```

## Results & Insights
- The logistic regression model provides an accuracy score based on the test dataset.
- Important features affecting survival include gender, class, and age.
- Data visualization helps understand survival trends and dataset characteristics.

## Contributions
Contributions are welcome! Feel free to submit issues or pull requests.

## License
This project is licensed under the MIT License.

Ariz Iqbal 
