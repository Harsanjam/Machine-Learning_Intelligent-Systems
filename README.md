# Machine-Learning_Intelligent-Systems


# Intelligent Systems - Linear Regression Lab

This repository contains the implementation of linear regression using Gradient Descent for a lab assignment in the Intelligent Systems course. The primary goal is to predict the final marks of students based on their midterm marks by building a linear regression model from scratch.

## Lab Overview:
- **Dataset**: The dataset contains midterm and final marks of 100 students from the previous semester. The objective is to predict the final marks using the midterm marks.
  
- **Key Tasks**:
  - **Data Exploration and Standardization**: Performed exploratory data analysis (EDA) and feature standardization to normalize the dataset.
  - **Linear Regression Model**: Implemented a linear regression model with the standard equation \( y = mx + b \).
  - **Error (Cost Function)**: Defined and calculated the error using the sum of squared differences between predicted and actual final marks.
  - **Gradient Descent**: Computed the partial derivatives of the cost function with respect to slope (m) and intercept (b), and updated them iteratively using a learning rate (α) to minimize the error.
  
## Implementation Details:
1. **Standardization**: Implemented feature scaling to standardize the data for improved performance.
2. **Error Function**: Calculated the error using:
   ```
   E = (1/N) * Σ (y_i - (mx_i + b))^2
   ```
   
3. **Gradient Descent Algorithm**: 
   - Updated m and b iteratively using:

   ```
   m_new = m_old - α * ∂E/∂m
   b_new = b_old - α * ∂E/∂b
   ```
   
4. **Visualization**: 
   - Plotted the initial data points and regression line.
   - Visualized the updated regression line after 100 iterations and the error progression.
   - Repeated the process for 2000 iterations with visualizations of the final regression line and the error at each iteration.

## Results:
- Conducted the linear regression both with and without feature standardization, observing the impact of standardization on the model's convergence and error reduction.
- Visualized the error reduction over 2000 iterations for both standardized and non-standardized features.

## Technologies:
- Python
- Matplotlib
- NumPy
- Pandas

