# Housing Price Prediction

This project predicts housing prices using machine learning techniques in Python. The workflow includes data preprocessing, feature engineering, and applying regression models to predict prices and classify price ranges.

## Project Structure

- `Housing Price Prediction.ipynb`: Main Jupyter notebook containing all code for data preprocessing, feature engineering, model training, and evaluation.
- `Housing Price.csv`: Dataset containing housing data.

## Workflow

1. **Data Loading**  
   Load the dataset using pandas.

2. **Data Cleaning**  
   - Handle missing values in the `area` column using mean imputation.
   - Remove duplicate rows.

3. **Categorical Encoding**  
   - Encode categorical variables using `LabelEncoder` and mapping.

4. **Feature Scaling**  
   - Scale all features using `MinMaxScaler`.

5. **Correlation Analysis**  
   - Visualize feature correlations using a heatmap.

6. **Modeling**
   - **Linear Regression**: Predict normalized house prices.
   - **Logistic Regression**: Classify houses into price ranges (Low, Mid, High).

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- seaborn

Install dependencies with:
```sh
pip install pandas numpy scikit-learn seaborn
```

## Usage

1. Open `Housing Price Prediction.ipynb` in Jupyter Notebook or VS Code.
2. Run the cells sequentially to preprocess data and train models.
3. Review the output for model performance metrics.

## Results

- Linear Regression: Reports Mean Square Error (MSE) and Root Mean Square Error (RMSE).
- Logistic Regression: Reports prediction accuracy for price range classification.