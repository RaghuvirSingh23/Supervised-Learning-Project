# Supervised-Learning-Project
## GOAL: Create a model to predict whether or not a customer will Churn.

### Following is the walkthrough/roadmap of the project

### *Churn Analysis*
1. Segmenting customers based on their tenure, creating "cohorts".
2. Creating a histogram displaying the distribution of 'tenure'.
3. Using Seaborn to create histograms separated by two additional features, Churn and Contract.
4. Displaying a scatter plot of Total Charges versus Monthly Charges and color hue by Churn.

#### Creating Cohorts based on Tenure.
: Treating each unique tenure length, 1 month, 2 months, 3 months...N months as its own cohort.
#### Broader Cohort Groups
: Based on the tenure column values, creating a new column called Tenure Cohort that creates 4 separate categories:
* '0-12 Months'
* '24-48 Months'
* '12-24 Months'
* 'Over 48 Months'

### *Predictive Modeling*
Exploring 4 different tree-based methods:
* A Single Decision Tree
* Random Forest
* AdaBoost
* Gradient Boosting.

#### *Tree Plot :* 
![Tree Plot](https://i.ibb.co/2gSdDs5/download-1.png)

### Conclusion:

*With base models, we got the best performance from an AdaBoostClassifier, but this is without doing any grid searching, and most models performed about the same on the data set.*