# Machine_Learning
## Documenting Machine Learning Concepts
> Feature scaling is defined by ScienceDirect as the process of transforming the values of independent variables so that they have common characteristics, such as being within a certain range of values, having an average value of 0, and the same standard deviation.

~~~python
print("Welcome to Machine Learning Documentation by Godswill Umoh"
~~~

## Where do you apply feature scaling?
### Answer: Feature scaling is always applied in the columns but never across columns.
___table
Column1 | Column2 | Column3

#### Feature scaling will be applied in each column
___

## How do you apply feature scaling
### The common method of feature scaling are 
- #### Normalization and
- #### standardization.
_for <ins>Normalization</ins>, you subtract the minimum value from all other values divided by the range where as the <ins>standardization</ins> case subtract the mean value from all other values divided by standard deviation._

- X' = X - Xmin /Xmax - Xmin
- #### All of the values in the column will be between 0 & 1 [0, 1]

- X' = X -mean / SD
- #### All of the values in the column will be between -+3 & 1  [-3, +3]

#### Formula for Normalization and standarddization:(https://ibb.co/QFNbVNn)
![scaling](https://github.com/user-attachments/assets/181c4d58-52a5-4656-9e59-e106434920ae)
