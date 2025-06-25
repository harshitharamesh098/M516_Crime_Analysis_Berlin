# Crime Trend Analysis in Berlin (2012–2019)

This project presents a comprehensive crime data analysis and predictive modelling study based on publicly available data from Berlin between the years 2012 and 2019. The goal is to explore patterns, visualise trends, and build predictive models to forecast violent crime occurrences using engineered features from the dataset.



## 📊 Dataset

- **Source**: [Kaggle: Crime in Berlin (2012–2019)](https://www.kaggle.com/datasets/danilzyryanov/crime-in-berlin-2012-2019)
- **Features**: District-wise counts for multiple crime types recorded annually.
- **Years Covered**: 2012 to 2019
- **Target Variable**: `violent_crime` (includes robbery, assault, injury, threat)

## 🔧 Implementation Details

- **Language**: Python 3.11+
- **Environment**: Jupyter Notebook
- **Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scikit-learn`, `joblib`

### 📌 Key Steps:
1. **Data Cleaning & Aggregation**  
   Missing values and noise were handled. Crimes were grouped by year and district.

2. **Feature Engineering**  
   Derived features such as `pct_violent`, `z_score` for standardisation, and categorical encodings.

3. **Modelling**  
   A Random Forest Regressor was trained to predict violent crime using features like total crime, district, and standardised scores.

4. **Evaluation**  
   - **RMSE**: 569.22  
   - **R² Score**: 0.964  
   Plots show strong alignment between actual and predicted values.

5. **Visualisations**  
   Heatmaps, boxplots, and bar charts were used to explore patterns and correlations.

## 🧠 Results

- **Most Affected District**: Mitte
- **Peak Crime Year**: 2016
- **Top Crime Types**: Theft, Damage, Injury
- **Strong Predictors**: `total_crime`, `z_total_crime`, `property_crime`

## 📈 Visual Samples

- Total Crime Trends Over Time
- Correlation Heatmap Between Crime Types
- Feature Importances for Violent Crime Prediction

## 📁 Deliverables

- ✅ `.ipynb`: Notebook with full pipeline
- ✅ `.docx`: Word report (3000 words)
- ✅ `.pkl`: Trained model
- ✅ Visual exports for documentation

## 📝 Citation

If using this work or dataset, please cite the Kaggle dataset and acknowledge this GitHub repository.

## 📧 Contact

For academic use or clarification, please contact the project administrator via GitHub issues
