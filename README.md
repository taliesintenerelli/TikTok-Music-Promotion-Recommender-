# TikTok Music Promotion Recommender

This project aims to analyze and optimize TikTok video features to maximize engagement, specifically log video views. The project uses machine learning models and Bayesian optimization to find the optimal values for various video features.

## Features and Technologies Used:
- Python
- pandas for data manipulation
- scikit-learn for machine learning models and cross-validation
- RandomForestRegressor, LinearRegression, SVR, MLPRegressor for model training
- Bayesian Optimization for parameter tuning
- Matplotlib and Seaborn for data visualization
- TensorFlow for neural network modeling

## Steps Involved:
1. **Data Collection**: Collecting TikTok analytics data using Tokbackup.
2. **Preprocessing**: Cleaning and organizing data, feature engineering.
3. **Exploratory Data Analysis**: Understanding data distribution and relationships.
4. **Model Selection**: Testing various models and selecting the best one based on cross-validated R-squared.
5. **Feature Selection**: Using feature importance and domain knowledge to choose relevant features.
6. **Optimization**: Using Bayesian optimization to find the best feature values for maximizing engagement.

## Results:
The project identified the optimal set of video features that maximize log video views, providing insights into what characteristics make a TikTok video more engaging.

### Optimal feature values:
    - Video Duration: 86.02
    - Caption Length: 39.39
    - Total Hashtags: 21.85
    - Generic Hashtags: 2.02
    - Unique Hashtags: 9.03
    - Time Posted: 1303.16
    - Optimal predicted log video views: 13.36

## Installation and Setup

To install the necessary dependencies, you can use the provided `requirements.txt` file. Follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/TikTok-Music-Promotion-Recommender.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd TikTok-Music-Promotion-Recommender
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
