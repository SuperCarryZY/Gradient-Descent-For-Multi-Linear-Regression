# Gradient-Descent-For-Multi-Linear-Regression
This is a self-defined function to find the final w and B using gradient Descent. <br>
Cost function:Least squares method.
# Build in Function 
* np.dot: This is a function for vector multiplication
* x.shape: It return feature number and rows.
* np.zeros((3,): retrun a array with 3 features. array([0., 0., 0.])
# Defined Function
* def Cost_function:It is the sum of error/2m of the linear regression.
* def predict_single_loop: Predict Y for each row.
* def predict_vector_single_loop:Predict Y by inputing vector.
* def gradient:This function is actually taking the derivative of w and b.
* def gradient_descent:Final function for adjust final w and b until convergence.
# Cost function:
![image](https://user-images.githubusercontent.com/121896846/224187649-0089aee2-cd46-48be-85a2-f6c1e333cf65.png)


# Gradient Descent:
![image](https://user-images.githubusercontent.com/121896846/224187741-1aca181e-c574-4dcb-9dec-7e7363af9ecc.png)

# Derivation：
![image](https://user-images.githubusercontent.com/121896846/224187864-1f5e4fe3-ac0d-438f-9efe-2fd4d3c43ff7.png)

