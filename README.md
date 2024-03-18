# Linear Regression Model Coefficients and Performance Analysis

This IPython Notebook contains Python code to find coefficients for a linear regression model using different methods and analyze their performance. The methods include Normal Equation, Batch Gradient Descent, and Stochastic Gradient Descent. The analysis includes plotting MSE vs. iteration for both training and testing sets, evaluating MSE on the testing set, and determining the best learning rate for Gradient Descent methods.

## Steps to Run the Notebook

1. Ensure you have Jupyter Notebook installed along with the necessary libraries such as NumPy, Matplotlib, and Scikit-learn.
2. Clone or download the repository containing the notebook file.
3. Open Jupyter Notebook and navigate to the directory containing the notebook file.
4. Open the notebook file (`linear_regression.ipynb`) and execute the code cells sequentially.

## Notebook Contents

- **Data Loading and Preprocessing**: Load the dataset from "data2.txt" and split it into training and testing sets.
- **Normal Equation Method**: Implement the Normal Equation method to find coefficients.
- **Batch Gradient Descent**: Implement Batch Gradient Descent method and plot MSE vs. iteration.
- **Stochastic Gradient Descent**: Implement Stochastic Gradient Descent method and plot MSE vs. iteration.
- **Evaluation on Testing Set**: Evaluate MSE on the testing set for both Gradient Descent methods.
- **Determining Best Learning Rate**: Plot MSE vs. learning rate to determine the best learning rate.

## Files in the Repository

- `linear_regression.ipynb`: IPython Notebook containing the program implementation.
- `data2.txt`: Dataset file containing the data for linear regression.
- `README.md`: This file providing an overview of the notebook.

## How to Use

1. Clone or download the repository to your local machine.
2. Run Jupyter Notebook and open the `linear_regression.ipynb` file.
3. Execute the code cells in sequence to perform the analysis and visualize the results.
4. Refer to the comments and markdown cells within the notebook for detailed explanations and instructions.

## Notes

- Ensure that you have Jupyter Notebook installed along with the required libraries mentioned above.
- Modify the notebook or parameters as needed for experimentation or further analysis.
- Read the markdown cells and comments within the notebook for detailed explanations of the code and algorithms used.
