# sales_prediction_EDA-ML
“Predicting global video game sales using machine learning (Random Forest, XGBoost, Lasso Regression) with EDA and visualization.”
# Global Video Game Sales Predictor 

**Tools:** Python (pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost), Jupyter Notebook  

## Objective
Predict global video game sales based on features such as genre, platform, publisher, release year, and ratings. The goal was to identify the most important factors that influence commercial success in the video game industry.  

## Data
- Dataset: Historical video game sales data with features like title, platform, genre, publisher, year, regional sales, and reviews.  Source: https://www.kaggle.com/datasets/thedevastator/global-video-game-sales-and-reviews
- Preprocessing: Missing value handling, duplicates removal, one-hot encoding for categorical variables, scaling of numerical features.  

## Approach
1. **EDA:** Visualized sales trends by genre, publisher, platform, and year.  
2. **Feature Engineering:** Created “Years Since Release” and binned review scores.  
3. **Modeling:** Trained and compared Random Forest, XGBoost, and Lasso Regression.  
4. **Evaluation:** Used MAE, RMSE, and R² to assess model accuracy.  
5. **Hyperparameter Tuning:** GridSearchCV for optimization.  

## Results
- Best model: **Lasso Regression** (balanced accuracy + interpretability).  
- Key features: Year of release, genre, platform, and ratings strongly influenced global sales.  
  
## How to Run
- Clone this repo  
- Install requirements: `pip install -r requirements.txt`  
- Open the notebook: `notebooks/EDA_minor_project.ipynb` in Jupyter  
- Or view directly on GitHub (renders automatically)
