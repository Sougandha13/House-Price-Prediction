# House Price Prediction

## Overview
The **House Price Prediction** project aims to build a machine learning model to predict housing prices based on various features. Using the **California Housing** dataset from Scikit-learn, this project applies data preprocessing, visualization, and advanced regression techniques to develop an accurate price prediction model. The project is particularly useful for real estate professionals, investors, and analysts to make data-driven decisions.

## Features
- **Data Collection & Processing:**
  - Uses the **California Housing** dataset from Scikit-learn.
  - Features include house age, number of rooms, population, median income, and more.
  - Data is processed using **Pandas** to ensure suitability for analysis.
  
- **Data Visualization:**
  - Leverages **Matplotlib** and **Seaborn** to generate insightful visualizations.
  - Includes histograms, scatter plots, and correlation matrices to explore feature relationships.
  
- **Train-Test Split:**
  - Splits the dataset into training and testing sets for model evaluation.
  - Ensures a robust assessment of predictive performance.
  
- **Regression Model using XGBoost:**
  - Utilizes the **XGBoost** algorithm, a powerful gradient boosting framework.
  - Provides high predictive accuracy by handling complex feature relationships.
  
- **Model Evaluation:**
  - Assesses performance using **R-squared error** and **mean absolute error (MAE).**
  - Generates a scatter plot comparing predicted vs. actual house prices.

## Technologies Used
- **Python**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**
- **XGBoost**

## Getting Started
### Prerequisites
Ensure you have Python installed along with the required libraries:
```sh
pip install numpy pandas scikit-learn matplotlib seaborn xgboost
```

### Running the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/YOUR_USERNAME/House_Price_Prediction.git
   cd House_Price_Prediction
   ```
2. If using Google Colab:
   - Open [Google Colab](https://colab.research.google.com/)
   - Upload and open the `House_Price_Prediction.ipynb` file.
   - Run the notebook cells sequentially.

## Results
- The project successfully builds an XGBoost regression model for house price prediction.
- The model evaluation metrics indicate its effectiveness in estimating prices.
- Data visualizations help in understanding feature correlations and trends.

## Conclusion
The **House Price Prediction** project demonstrates a practical approach to predicting real estate prices using machine learning. By leveraging data preprocessing, visualization, and the powerful **XGBoost** regression model, this project serves as a valuable tool for analyzing and estimating house prices accurately.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Scikit-learn for providing the **California Housing** dataset.
- The open-source community for contributing to the development of data science tools.

