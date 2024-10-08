### Pima Indians Diabetes Prediction

This project analyzes the Pima Indians Diabetes dataset to predict the onset of diabetes in individuals within 5 years based on various medical parameters. The problem is framed as a binary classification task, where the model predicts whether a person will develop diabetes (1) or not (0).

#### Dataset Overview
The dataset consists of 768 records, each with 8 medical features and 1 output variable indicating diabetes status. Some of the medical features include:

1. **Number of times pregnant**
2. **Plasma glucose concentration** (after a 2-hour oral glucose tolerance test)
3. **Diastolic blood pressure** (mm Hg)
4. **Triceps skinfold thickness** (mm)
5. **2-hour serum insulin** (mu U/ml)
6. **Body mass index (BMI)** (weight in kg / (height in m)^2)
7. **Diabetes pedigree function** (family history)
8. **Age** (years)

The missing values in the dataset are coded as zero.

#### Key Tasks
1. **Visualizing the Data:**
   - Histograms for all features without considering the class variable.
   - Histograms of features 2, 3, 6, and 7, with separate plots for the two classes (diabetes or not).
   
2. **Statistical Analysis:**
   - Calculation of the mean and variance for feature 6 (BMI).

3. **Scatter Plot:**
   - Plotting a scatter plot between features 6 (BMI) and 8 (Age), with different colors representing the two classes.

4. **Classification:**
   - Building a decision tree classifier with a maximum depth of 4 to classify whether an individual has diabetes or not based on the provided features.

#### Conclusion
This project provides a comprehensive analysis of the Pima Indians Diabetes dataset, combining data visualization, statistical analysis, and machine learning techniques to predict diabetes onset.

