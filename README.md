# Linear Regression Analysis on Literacy Rate vs. Poverty Rate

## Project Overview
This project analyzes the relationship between Literacy Rate (%) and Poverty Rate (%) in India using Linear Regression. The goal is to determine whether an increase in literacy rates impacts the poverty rate over time.

## Data Sources
The datasets were sourced from [data.gov.in](https://www.data.gov.in):
- **Poverty Rate Dataset**: [Percentage of People Below Poverty Line in India](https://www.data.gov.in/resource/percentage-people-below-poverty-line-india)
- **Literacy Rate Dataset**: [Literacy Rate from 1951 to 2011](https://www.data.gov.in/resource/literacy-rate-1951-2011)

## Steps Performed
1. **Data Import**: Imported the datasets in CSV format.
2. **Data Cleaning**: Handled missing values and removed duplicates.
3. **Data Merging**: Aligned Literacy Rate and Poverty Rate data for corresponding years.
4. **Data Splitting**: Split the dataset into training (80%) and testing (20%) subsets.
5. **Model Training**: Used a Linear Regression model to fit the data.
6. **Evaluation**: Assessed model performance using Mean Squared Error (MSE) and R-squared (R²) metrics.
7. **Visualization**:
   - Scatter plot of Literacy Rate vs. Poverty Rate with the regression line.
   - Future predictions for Poverty Rate based on projected Literacy Rates (2024-2033).

## Results
- **Regression Equation**: The trained model provides an equation of the form:
  \[ Poverty Rate = \beta_0 + \beta_1 \times Literacy Rate \]
- **Model Performance**:
  - Mean Squared Error (MSE): _Computed value_
  - R-squared (R²): _Computed value_

## Future Predictions
Using the trained model, we projected poverty rates for future literacy rates (2024-2033) and visualized these predictions.

## Visualization
- Scatter plot of actual data.
- Regression line to show the linear relationship.
- Plot of predicted values for future years.

## Requirements
To run this project, install the following Python libraries:
```bash
pip install pandas numpy scikit-learn matplotlib
```

## How to Run
1. Upload the CSV files.
2. Execute the Jupyter Notebook or Python script.
3. View the results and generated plots.

## Author
**Aaditya Chachra**
