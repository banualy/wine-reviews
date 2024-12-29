# Wine Reviews Data Analysis and Regression Model

This project performs an exploratory data analysis (EDA) and builds a regression model to predict wine review points based on features like price, region, and description sentiment. The analysis leverages Python libraries and Kaggle's Wine Reviews dataset.
You can find Kaggle notebook here: https://www.kaggle.com/code/banualy/wine-review-final

## Features
- **Data Cleaning**: Removes irrelevant or redundant columns, handles missing values.
- **Feature Engineering**:
  - Maps average price and squared points to respective regions.
  - Extracts sentiment polarity from wine descriptions using `TextBlob`.
- **Visualization**: Correlation heatmaps and pairplots to uncover relationships between features.
- **Regression Modeling**: Uses linear regression to predict wine review points.
- **Performance Metrics**: Evaluates model using RMSE and R-squared scores.

## Prerequisites
- Python 3.7+
- Required Python libraries: pandas, numpy, matplotlib, seaborn, textblob, scikit-learn, tensorflow

### Steps in the Script
1. **Data Cleaning**:
   - Drops unused columns like `designation`, `country`, and others.
   - Handles missing values by dropping rows with null values.

2. **Feature Engineering**:
   - Calculates average squared points per region.
   - Uses `TextBlob` to compute sentiment polarity of descriptions.

3. **Visualization**:
   - Plots correlations using heatmaps and pairplots.

4. **Regression Model**:
   - Scales features using `StandardScaler`.
   - Splits data into training and testing sets.
   - Fits a linear regression model to predict wine points.

### Output
- The script prints:
  - Dataset summary statistics.
  - Correlation matrix.
  - Regression model performance (RMSE and R-squared scores).

## Example Results
- **Root Mean Squared Error (RMSE)**: 1.5 (approx.)
- **R² Score**: 0.77 (approx.)

## Contributing
Contributions are welcome! Feel free to submit pull requests or report issues.


