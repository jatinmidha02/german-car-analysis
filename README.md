# German Car Market Analysis — AutoScout24

## Project summary
This project analyzes German used/new-car listing data using Python. It covers data cleaning,
exploratory data analysis, statistical summaries, visualization, feature engineering, correlation
analysis, and a baseline machine-learning model for listing-price prediction.

## Dataset
A public AutoScout24 Germany dataset is available on Kaggle and is described as containing 46,405
vehicles from Germany, collected for 2011–2021. Its core fields include mileage, make, model, fuel,
gearbox, offer type, price, horsepower and registration year.

Source:
https://www.kaggle.com/datasets/ander289386/cars-germany

The repository's included CSV is a **synthetic practice sample** created to let the project run
without redistributing the public dataset. It follows the same core schema. If you use the project
for a real portfolio/resume project, download the public dataset yourself and replace the included
CSV, then rerun the notebook.

## Tools
- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Workflow
1. Load and inspect the dataset
2. Identify duplicates and missing values
3. Validate numeric ranges
4. Impute missing values
5. Create vehicle-age and mileage-per-year features
6. Analyze price distributions
7. Compare prices by brand, fuel type and transmission
8. Study mileage/age/horsepower relationships
9. Calculate correlations
10. Build a Random Forest baseline price-prediction model
11. Evaluate using MAE, RMSE and R²
12. Translate findings into marketplace/business insights

## Suggested resume bullets
- Analyzed German vehicle listings from AutoScout24 using Python, Pandas and NumPy to identify
  relationships between mileage, vehicle age, horsepower, fuel type, transmission and listing price.
- Cleaned and validated automotive data by handling missing values, duplicates and inconsistent
  numerical ranges; engineered vehicle-age and mileage-per-year features.
- Built Matplotlib visualizations and statistical summaries to compare pricing patterns across
  brands, fuel types and transmission types.
- Developed a Random Forest regression baseline to estimate listing prices and evaluated performance
  using MAE, RMSE and R².

## Interview explanation
"I worked on an automotive market analytics project using an AutoScout24 Germany dataset. I first
profiled the data for missing values, duplicates and invalid ranges. Then I cleaned the dataset and
engineered vehicle age and mileage-per-year. I used Pandas groupby and descriptive statistics to
compare pricing by brand, fuel type and transmission, and Matplotlib for distributions and
relationship plots. Finally, I built a Random Forest regression baseline with one-hot encoded
categorical features and evaluated it using MAE, RMSE and R². The main purpose was to understand
which vehicle attributes were associated with listing price and demonstrate an end-to-end analytics
workflow."

## Important
Do not quote model metrics or specific numerical findings from the included sample as if they came
from the real AutoScout24 dataset. After downloading the real dataset, rerun the notebook and use
the actual output.
