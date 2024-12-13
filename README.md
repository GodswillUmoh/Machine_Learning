# Machine_Learning
## Documenting Machine Learning Concepts
Feature scaling is defined by ScienceDirect as the process of transforming the values of independent variables so that they have common characteristics, such as being within a certain range of values, having an average value of 0, and the same standard deviation.

## Where do you apply feature scaling?
### Answer: Feature scaling is always applied in the columns but never across columns.
___table
Column1 | Column2 | Column3

#### Feature scaling will be applied in each column
___

## How do you apply feature scaling
### The common method of feature scaling are 
- Normalization and
- standardization.
for Normalization, you subtract the minimum value from all other values divided by the range where as the standardization case subtract the mean value from all other values divided by standard deviation.

- X' = X - Xmin /Xmax - Xmin
- #### This gives a value range of [0, 1]

- X' = X -mean / SD
- #### This gives a value range of [-3, +3]
