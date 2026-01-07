## Theory

In many scientific and engineering problems, the analytical form of a function may not be available, and the function values are known only at discrete points obtained through experiments or numerical simulations. In such cases, numerical differentiation is used to approximate the derivative of the function.

Let the function values be known at equally spaced points:

<img width="146" height="32" alt="image" src="https://github.com/user-attachments/assets/bb3e1907-32f2-472d-a5fc-48ab324b6583" />

with a constant spacing:

<img width="152" height="35" alt="image" src="https://github.com/user-attachments/assets/4f50c301-13ad-422c-b834-b5f975a2bd38" />

Numerical differentiation approximates the derivative using finite difference methods, which are derived from Taylor series expansions.

### Forward Difference Method

The forward difference approximation of the first derivative at Xi is given by:

<img width="280" height="92" alt="image" src="https://github.com/user-attachments/assets/80d999e9-b9d0-4747-8441-dfc0c74977de" />

This method uses the function value at the current point and the next point. It is simple to implement but generally provides lower accuracy.

### Backward Difference Method
The backward difference approximation of the first derivative at Xi is given by:

<img width="285" height="93" alt="image" src="https://github.com/user-attachments/assets/2bac4f83-32dc-49ca-8d4e-246811a80555" />

This method uses the function value at the current point and the previous point and is useful when forward data points are unavailable.

### Central Difference Method
The central difference approximation of the first derivative at Xi is given by:

<img width="317" height="90" alt="image" src="https://github.com/user-attachments/assets/ec39bcea-ba20-485e-ae1f-f89f6fcedb5c" />

This method uses data points on both sides of the point of interest and provides better accuracy compared to forward and backward difference methods.

### Importance of Numerical Differentiation

Numerical differentiation is widely used in:

- Estimation of velocity and acceleration from discrete position data

- Analysis of experimental data

- Scientific and engineering simulations
###This method uses the function value at the current point and the previous point and is useful when forward data points are unavailable.

