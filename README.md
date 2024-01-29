# Group10_GroupWork
### FINAL NOTES!
## Sample Population Overview
# The dataset primarily consists of demographic information such as age, gender, work type, BMI, hypertension, heart disease, smoking status, average glucose level, and stroke occurrence.
# The data has been cleaned and missing values imputed. Outliers were not addressed in analysis as it was not deemed necessary as they were few and it was health data.
# In the data Gender and Residence Type were evenly distributed with Residence being more even. Work Type contained various sectors with most working in the private sector. In the smoking status majority never smoked and non_smokers make up most of the data. With strokes being the data most referenced it is heavily skewed with a high percentage never having had a stroke.

## Data Analysis
# Correlation Analysis
# Significant correlations were observed between some variables (age and glucose, bmi and glucose) and a correlation heatmap between (Hypertension, Heart Disease and Stroke)- where the correlation was fairly similar between each variable.

# Visualizations
# Various visualizations, including histograms and countplots, were created to explore the distribution of variables and the relationship between health conditions and other factors.

# Insights
# Age
# Age is positively correlated with stroke, hypertension and heart disease, which is expected.
# Glucose
# Average glucose level shows some correlation with age, stroke, hypertension, and heart disease, which is mostly positive.
# BMI
# BMI shows some correlation with age, stroke, hypertension, and heart disease, with people at a certain BMI range having a 50/50 chance of developing a health condition
# Marriage and Resudence Type
# These two variables have no observeable correlation with the aforementioned health conditions.
# Strokes 
# The dataset contains a relatively small number of stroke cases.
# Further investigation into factors contributing to strokes, such as age, hypertension, and heart disease, may be insightf

## Recommendations
# Given the imbalanced distribution of stroke cases, conduct a more in-depth analysis to identify factors contributing to strokes. Consider applying techniques to handle class imbalance in machine learning models.
