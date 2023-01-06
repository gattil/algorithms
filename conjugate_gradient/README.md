# Compute Optimum using Conjugate Gradient from scipy.optimize.minimize

The "CG" method from the minimize function in the scipy.optimize module is an optimization algorithm that uses the conjugate gradient method to find the minimum of a function defined on a finite-dimensional space. 
It is a type of gradient descent method that iteratively improves the solution to an optimization problem by taking steps in the direction of the negative gradient of the objective function.

The conjugate gradient method works by constructing a sequence of search directions that are conjugate to each other. This means that at each iteration, the search direction is chosen to be orthogonal to all of the previous search directions. 
This property allows the conjugate gradient method to make faster progress towards the minimum of the objective function, because it avoids the "zig-zag" behavior that can occur with other gradient descent methods.

The conjugate gradient method is particularly well-suited to optimization problems where the objective function is a quadratic function, because it is able to find the minimum of such functions in just a few iterations. 
However, it can also be used to optimize more general nonlinear functions, although it may require more iterations to find the minimum in these cases.

To use the "CG" method, you will need to pass it as the method argument to the minimize function, along with the objective function and the initial guess for the optimal solution. 
The minimize function will then return an object containing the optimal solution and other information about the optimization process.
