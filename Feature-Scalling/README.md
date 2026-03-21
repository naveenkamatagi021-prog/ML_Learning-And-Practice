# Feature Scaling and Function Transformation in Machine Learning

This folder contains hands-on practice on important feature scaling techniques used in Machine Learning, including **Standardization**, **Normalization**, and **Function Transformation** using Python and Scikit-learn.

## Topics Covered
- Feature Scaling using Standardization
- Feature Scaling using Normalization
- Function Transformation
- Before vs After distribution comparison using histograms

## Project Overview

Feature scaling is an important step in data preprocessing because many machine learning algorithms perform better when numerical features are on a similar scale.

In this practice, I worked on scaling and transforming numerical data from a dataset using different preprocessing techniques and compared the data distribution before and after transformation.

## Techniques Used

### 1. Standardization
Standardization transforms the data so that it has:
- Mean = 0
- Standard Deviation = 1

In this practice, I applied **StandardScaler** on the `Principal` column and created a new scaled feature:
- `Principal_ss`

This helps make the feature suitable for models that are sensitive to feature magnitude.

### 2. Normalization
Normalization rescales the values into a fixed range, usually:
- 0 to 1

In this practice, I applied **MinMaxScaler** on the `past_due_days` column and created:
- `past_due_days_ms`

This method is useful when we want all values to lie within the same range.

### 3. Function Transformation
Function transformation is used to transform data into a more useful form for analysis or modeling.

In this practice, I used **FunctionTransformer** on the `age` column and created:
- `age_ft`

This helps understand how feature transformation can be applied to numerical data during preprocessing.

## Visual Analysis
To better understand the effect of preprocessing, I compared the data **before and after transformation** using histograms with KDE plots.

The visual comparisons were done for:
- `Principal` vs `Principal_ss`
- `past_due_days` vs `past_due_days_ms`
- `age` vs `age_ft`

## Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Libraries/Classes Used
- `StandardScaler`
- `MinMaxScaler`
- `FunctionTransformer`

## Learning Outcome
Through this practice, I learned:
- how to apply standardization to numerical features
- how to normalize data using Min-Max scaling
- how to use function transformation on columns
- how to compare feature distributions before and after preprocessing
- why feature scaling is important in machine learning

## Conclusion
Feature scaling and transformation are essential preprocessing steps in Machine Learning. They improve data consistency, help algorithms perform better, and make numerical features easier to work with during model training.

## Author
**Naveen Kamatagi**
