# Medical-Expenses-Prediction
This project aims at building Machine Learning models which can predict a patient's medical expenses based on specific features
Factors affecting the medical expenses of the patients :

• Age

• Gender

• Body Mass Index

• Region

• Smoking Behavior


## Business Implications of the Project:

• Health is the center of everyone’s life.

• Every part of our life relies on good health.

• Health is the extent of an individual’s continuing physical, emotional, mental, and social
ability to cope with the environment.

## Data Source:

• The dataset has been sourced from kaggle.com and on GitHub.

It includes the following features:

• Age: Patient's age

• Sex: Patient's sex

• BMI: Patient's Body Mass Index

• Children: How many children the patient has

• Smoker: Whether the patient is a smoker or not

• Region: Which region the patient is from (Northeast, Southeast, Southwest, Northwest)

• Expenses: Individual medical costs billed by health insurance

## Target Variable:

The Expenses column is the target column, and the rest others are independent columns. Independent columns are those which will predict the outcome.

## Independent Variables:

The first column is Age. Age is an important factor for predicting medical expenses because young people are generally more healthy than old ones and the medical expenses for Young People will be quite less as compared to old people.

The Next column is sex, which has two Categories in this column: Male and Female. The sex of the person can also play a vital role in predicting the medical expenses of a subject.

After that, you have the ‘bmi’ column, then BMI is Body Mass Index. For most adults, an ideal BMI is in the 18.5 to 24.9 range. For children and young people aged 2 to 18, the BMI calculation considers age and gender as well as height and weight. If your BMI is less than 18.5, you are considered underweight. People with very low or very high ‘bmi’ are more likely to require medical assistance, resulting in higher costs.
     
The fourth column is the ‘children’ column, which contains information on how many children your patients have. Persons who have children are under more pressure because of their children’s education, and other needs than people who do not have children.

The fifth is the ‘smoker’ column. The Smoking factor is also considered to be one of the Most Important factors as the people who smoke are always at risk when their age reaches 50 to 60.

Next is the ‘region’ column. Some Regions are Hygienic, Clean, Neat, and Prosperous, But some Regions are not, and this information affects health which is related to medical expenses.

## Conclusion
 
We have built three models among which the Random Forest Regressor model shows the best result through which we can say 83.75% variability of expenses can well be explained by predictor variables and which yields comparatively low RMSE value so our predicted expense through this model will not vary too much from the actual expense.
