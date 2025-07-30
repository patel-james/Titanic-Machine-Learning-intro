# Titanic-Machine-Learning-intro
Building predicitive models to test whether a passenger survived teh Titanic bases on features such as age, sex, ticket class, and more.


## 📁 Files
- `titanic.csv`: The dataset containing passenger information.
- `model.ipynb`: Jupyter Notebook used for data analysis, model training, and prediction.
- `image.png`: Correlation heatmap or other visualizations (if included).
- `README.md`: This file.

## Steps Performed

1. **Data Cleaning**
   - Removed missing values
   - Converted categorical variables to numeric (e.g., Sex, Embarked)
   - Combined certain features into one such as Sibiling/Spouse and Parent/Children count into one feature "Family_Size"
   - Grouped and binned 'fare price' and 'age' for better understanding for ranges

2. **Feature Selection**
   - Selected important features like `Pclass`, `Sex`, `Age`, `Fare`

3. **Model Training**
   - Used a algorithm: KNN and certain param_grid model to sort out the best model for selection
   - Trained the model on a portion of the dataset and left 25% for testing

4. **Model Evaluation**
   - Checked model accuracy using test data
   - Visualized results using confusion matrix and accuracy score


## How to Run

1. Open `model.ipynb` in Jupyter Notebook
2. Run all cells to clean the data, train the model, and make predictions


