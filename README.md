<div style="text-align: center;">
    <img src="images/banner1.jpg" style="width:1080px;height:600px;">
</div>

---

## CO2 Emissions Prediction Using Python

This project aims to develop a model that predicts CO2 emissions based on engine size using Python. The dataset used is `FuelConsumption.csv`, which contains various features, including engine size and CO2 emissions. This project involves several key steps to build and evaluate the predictive model.

### Project Workflow

1. **Importing Libraries:**
   Essential libraries like numpy, pandas, and matplotlib are imported for data manipulation, analysis, and visualization.

2. **Loading and Displaying Data:**
   The dataset is loaded into a DataFrame, and the first few rows are displayed to understand the data structure.

3. **Descriptive Statistics:**
   Summary statistics are generated to gain insights into the dataset, including measures like mean, median, and standard deviation.

4. **Selecting Features:**
   Key features, `ENGINESIZE` and `CO2EMISSIONS`, are selected for analysis. This helps focus on the variables that most influence CO2 emissions.

5. **Scatter Plot:**
   A scatter plot is created to visualize the relationship between engine size and CO2 emissions, providing a visual representation of the data.

6. **Splitting Data:**
   The dataset is split into training (70%) and testing (30%) sets to evaluate the model's performance.

7. **Z-Score Normalization:**
   Z-score normalization is applied to standardize the data, ensuring the features are on a comparable scale.

8. **Normalized Scatter Plot:**
   Another scatter plot of the normalized data ensures that the normalization process is correctly implemented.

9. **Cost Function:**
   The cost function is defined to measure the prediction error, essential for the optimization process.

10. **Gradient Calculation:**
    Gradients are calculated to understand the direction and rate of change needed to minimize the cost function.

11. **Gradient Descent:**
    The gradient descent algorithm is implemented to iteratively update the model's parameters and minimize the cost function.

12. **Training the Model:**
    The model is trained using gradient descent, and the cost reduction over iterations is tracked.

13. **Plotting Results:**
    The cost function's behavior and the regression line fitted to the normalized data are visualized to evaluate the model.

14. **De-normalizing Parameters:**
    The model's parameters are de-normalized to apply predictions to the original data scale.

15. **Prediction Function:**
    A function is defined to make predictions using the trained model.

16. **Printing Predictions:**
    Predictions are printed alongside actual values to showcase the model's effectiveness.

17. **Random Sampling:**
    Random samples from the test data are selected, and predictions are made to demonstrate the model's accuracy.

### Getting Started

To get started with this project, clone the repository and follow the steps outlined in the Jupyter notebook.

```bash
git clone https://github.com/Hoomkh/CO2EmissionsPrediction.git
cd CO2EmissionsPrediction
```

### Prerequisites

Ensure you have the following libraries installed:
- numpy
- pandas
- matplotlib

Install the required libraries using pip:
```bash
pip install numpy pandas matplotlib
```

### Usage

Open the Jupyter notebook and run the cells to execute the workflow and build the predictive model.

### License

This project is licensed under the MIT License.

---
