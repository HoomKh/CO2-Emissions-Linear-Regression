# CO2 Emissions Prediction

This project focuses on predicting CO2 emissions of vehicles based on their engine sizes using a linear regression model. The dataset used in this project is `FuelConsumption.csv`, which includes various attributes of cars such as model year, make, model, vehicle class, engine size, cylinders, transmission, fuel type, and different fuel consumption metrics.

#### Key Features:

1. **Data Preprocessing**:
   - The dataset is cleaned and preprocessed to select relevant features (`ENGINESIZE`, `CO2EMISSIONS`).
   - Data visualization techniques, such as scatter plots, are used to understand the relationship between engine size and CO2 emissions.

2. **Data Splitting**:
   - The data is split into training and testing sets (70-30 split) to validate the model's performance.

3. **Normalization**:
   - Feature and target variables are normalized using z-score normalization to ensure effective training.

4. **Model Training**:
   - A linear regression model is trained using gradient descent optimization.
   - The cost function and gradient calculations are implemented to iteratively update the model parameters.

5. **Denormalization**:
   - The model parameters (weights and biases) are denormalized to interpret them in the original scale of the dataset.
   - This step ensures the predictions are meaningful and can be compared directly to the actual CO2 emissions.

6. **Model Evaluation**:
   - The trained model is evaluated on the test set, and predictions are made.
   - The performance of the model is visualized through plots of predicted versus actual values.

This project provides a hands-on approach to understanding linear regression, data normalization, and model evaluation. It is an excellent resource for those interested in machine learning, data science, and environmental impact analysis. The complete code and dataset are available in the repository for further exploration and experimentation.
