# Healthcare-predictive-models

Built multiple predictive models using healthcare data

# How to run flask app

1. Download the "dist" folder

2. Click on the "dist" folder.

3. Click on "server".

4. A cmd window opens, where the last line is "Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)"

5. Copy the link and paste it on a browser.

# Description

This study has one primary goal: to ease the scheduling and calendaring of appointments and
surgeries. A hospital is one of the building blocks of an established society, and one of the few
services that will never be obsolete. Hence, there will always be demand of hospitals and
appointments. Thus, with exponential increase in patients, effective scheduling and
streamlining the way a hospital’s appointment and future appointments are made would lead
to an increase in its efficiency, and other factors like time and resources could be calibrated
and managed in a better way. Smoother functioning of the hospital will also lead to an
increase in revenue.

**A patient’s length of stay in the hospital after having their surgery is a very dynamic
phenomena which depends on a lot of factors. But gauging inpatient length of stay and
assigning it into tangible terms, like group of weeks (los) may help the hospital in establishing
a general framework for the patient’s length of stay, regardless of external factors.** 

This may also help the hospital administration look at the patient’s length of stay in terms of bed usage.
Since ultimately, it is the beds whose information (their availability) is required for optimal
working of the staff’s scheduling system, it is imperative to look at the data in terms of bed
usage. A binary-class target variable has been created for the same, which is explained in
detail in the later passages.

After having performed feature selection using chi-squared and information gain, performing principal components analysis for dimensionality reduction and using over/under sampling techniques to deal with the class imbalance, various classification machine learning models have been applied for the inpatient length of
stay prediction. **The ideal model was found to be the calibrated random forest, yielding
accuracy and f1 scores of 79.80% and 79.71% respectively for multiclass variable prediction
and 92.97% and 92.95% respectively for binary-class variable prediction.**

Another objective proposed was to determine how long (in days) a
patient may have to wait for their surgery, after having been admitted into the hospital.
**Various machine learning models have been fitted onto the updated data, and the ideal results were yielded by a calibrated random forest model with an accuracy and f1 score of 72.14% and 71.67% respectively.**

The final model proposed was to predict the likelihood of rehospitalization of a patient after
having undergone surgery, up to one year. The target variable is a binary classification with
“yes” or “no” classes. Three tree-based models have been fitted on to the data, and then
further calibrated to increase the performance and probability estimation of the model.
**Again, a calibrated random forest gave the best performance with 75.40% accuracy score and 75.28% f1 score.**
