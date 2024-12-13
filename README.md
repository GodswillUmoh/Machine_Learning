# Machine_Learning

## Documenting Machine Learning Concepts
> Feature scaling is defined by ScienceDirect as the process of transforming the values of independent variables so that they have common characteristics, such as being within a certain range of values, having an average value of 0, and the same standard deviation.

~~~python
print("Welcome to Machine Learning Documentation by Godswill Umoh"
~~~

#gh-dark-mode-only

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
- #### All of the values in the column will be between -3 & +3  [-3, +3]

#### Formula for Normalization and standarddization:(https://ibb.co/QFNbVNn)
![scaling](https://github.com/user-attachments/assets/181c4d58-52a5-4656-9e59-e106434920ae)

## Dealing With Outliers
_Outliers or extreme values outside the range of the numbers got from the scaling will be outside the range:_
Express Analytics define outlier as a data point that is noticeably different from the rest. They represent errors in measurement, bad data collection, or simply show variables not considered when collecting the data.

_. It can be either much higher or much lower than the other data points, and its presence can have a significant impact on the results of machine learning algorithms. They can be caused by measurement or execution errors._

### One of the ways to handle outlier
Calculate  X' = X -mean / SD, Points with |standardization| > 3 are considered outliers.

### Should I remove Outlier?
In Deciding How to Handle Outliers, sometimes _ _Do Nothing_ _ because __Sometimes outliers carry valuable information and should be retained (e.g., fraud detection).__

Other times, you may __Remove Outliers:__ for these reasons:
+ Exclude data points identified as outliers, especially if they result from errors or noise.
+ Be cautious; removing too many points can bias the dataset.

## Practical Case for Feature Scaling
| Names |	Salary |	Age |
|-------|--------|------|
| Godswill Umoh | $ 80,000 | 45 yrs |
| Victoria Okpi | $ 70,000 | 44 yrs |
| Esther Johnson |$ 62,000 | 40 yrs |

+ In this table our task will be to find out which names are closer to each other using feature scaling, specifically, __Normalization__
+ Using the formula: _X' = X - Xmin /Xmax - Xmin_

| Names |	Salary |	Age |
|-------|--------|------|
| Godswill Umoh | 1 | 45 yrs |
| Victoria Okpi | 0.444 | 44 yrs |
| Esther Johnson | 0 | 40 yrs |



