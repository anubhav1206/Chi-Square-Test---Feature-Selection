# Chi-Square-Test---Feature-Selection
Categorical Feature Selection using Chi Square Test

Features in a machine learning model are columns that describes the characteristics of targets to be measured e.g age, sex, weight, level of education, years of work experience, home address are all features used in describing an individual.

Feature Selection is a process which involves reducing the input variables needed in a model by using only relevant data and getting rid of those variables that add little or no information. From the example above, weight and home address should probably not be used in a model that tries to determine an individual's salary. This process simplifies the model, reduces training time, avoid overfitting, and also helps data scientsits avoid the curse of dimensionality

There are generally 2 types of features in a machine learning model.

Numerical Features which are quantitative variables that carries a sense of magnitude related to the context of the variable which are measurable in numbers e.g Age, Height, Salary

Categorical Features which are qualitative variabless which maybe assigned based on particular qualities e.g Sex, Location, Department, Marital Status

These different feature types have different selection techniques. Pearson's Correlation rank and Chi-Square Test for Categorical features. The rest of this exercise is going to be spent applying the Chi-Square feature selection technique on categorical variables of a dataset
