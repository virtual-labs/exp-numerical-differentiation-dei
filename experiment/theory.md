# Numerical Differentiation Using Evenly Spaced Points

## Introduction
Numerical differentiation is a technique used to estimate the rate of change of a function when the function values are available only at specific data points. In many scientific and engineering applications, we do not always have the exact mathematical formula or it may be too complex to differentiate. Instead, we rely on sampled values of the function at evenly spaced points. Numerical differentiation helps us calculate approximate derivatives from such data.

## Evenly Spaced Points
In practical scenarios, data is often collected at equal intervals. The gap between two consecutive points remains constant. This uniform spacing allows us to apply standard numerical methods easily and consistently.

## Methods of Numerical Differentiation
Several methods exist for estimating the derivative of a function using discrete data points. This experiment focuses on three commonly used techniques:

### 1. Forward Difference Method
The slope at a point is estimated by comparing the value at that point with the next point. This method is simple and widely used but can have a larger error compared to more advanced techniques. It is usually applied near the beginning of the dataset.

### 2. Backward Difference Method
The slope at a point is calculated using the value at that point and the previous point. This method is useful at the end of the dataset where forward difference cannot be applied.

### 3. Central Difference Method
This method uses information from both the previous and the next points around the point of interest. Because it considers both sides, it provides a more accurate and balanced estimation of the derivative. However, it cannot be used for the first and last data points.

## Why These Methods Are Important
Numerical differentiation plays a key role in real-world analysis including:
- Studying motion to determine velocity and acceleration from position data
- Monitoring engineering systems for changes in physical measurements
- Analysing scientific signals such as temperature, pressure, or electrical variations
- Supporting data-driven decision making where direct calculus is not possible

## Observation Through Simulator
In this experiment, users can enter a function and specify:
- Starting and ending points
- Total number of evenly spaced sample points
- Choice of differentiation method

The simulator displays:
- A table showing the estimated derivative values
- A graph comparing the original function and the calculated derivative

This visual output helps the user understand how different numerical methods affect accuracy and representation.

## Conclusion
Numerical differentiation with evenly spaced points is a practical and efficient approach when dealing with real-world data. Forward and backward difference methods are simple to use but can have higher error, while the central difference method offers better accuracy. Choosing the right technique depends on the position of data points and the level of precision required.

