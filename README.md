# House Price Prediction Project 
  This project predicts house prices using various features such as area, number of bedrooms, bathrooms, location, and more. The model is built using a Random Forest Regressor and evaluated using regression metrics and visualizations.

##  Dataset
The dataset is included in a ZIP file (`HPP.zip`) and contains:
- `House Price Prediction Dataset.csv` – structured data with both numeric and categorical features.

## Features Used
- Area
- Bedrooms
- Bathrooms
- Floors
- Year Built
- Location
- Condition
- Garage

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib
- Jupyter Notebook

##  Visualizations
-  Correlation Heatmap
-  Bar graph comparing **Actual vs Predicted** prices
-  Confusion Matrix using binned price ranges (quantile bins)
-  
## Model

A **Random Forest Regressor** was used to predict prices.
### Model Evaluation Metrics:
| Metric | Value |
|--------|-------|
| R² Score | `0.85` (example) |
| MAE | `15432.21` |
| RMSE | `24381.57` |

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
