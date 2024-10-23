# Student-Placement-Classification-Problem-

**Problem Description:**
The goal is to predict whether students will be recruited during campus placements based on academic and personal factors. This task is critical for educational institutions, as placement success influences their reputation and admissions. The dataset includes various student characteristics, such as grades, work experience, specialization, and test scores, all of which can impact their employability. By developing predictive models, institutions can better understand which factors lead to successful placements, enabling more focused efforts to improve student outcomes.

1.	**DATASET SELECTION:**
•	Appropriate Dataset : The dataset selected for predicting student placements contains a clear categorical target variable: status (Placed/Not Placed). This binary target variable is appropriate for a classification task. The dataset has been taken from kaggle.
Here is the description of the dataset columns:
- **sl_no:** Serial number of the student (identifies each record uniquely).
- **gender:** Gender of the student (0 for male and 1 for female).
* **ssc_p:** Secondary Education percentage (10th Grade).
* **ssc_b:** Board of education for Secondary Education (Central or Others).
* **hsc_p:** Higher Secondary Education percentage (12th Grade).
* **hsc_b:** Board of education for Higher Secondary (Central or Others).
* **hsc_s:** Specialization in Higher Secondary (Commerce, Science, Arts).
* **degree_p:** Percentage obtained in Undergraduate Degree.
- **degree_t:** Type of Undergraduate Degree (Sci&Tech, Comm&Mgmt, Others).
* **workex:** Whether the student has prior work experience (Yes or No).
* **etest_p:** Employability test percentage score.
* **specialisation:** Specialization in MBA (Mkt&HR, Mkt&Fin).
* **mba_p:** Percentage obtained in MBA.
* **status:** Placement status (Placed or Not Placed).
* **salary:** Salary offered to the student (if placed).

This dataset contain various academic and personal factors that could influence the likelihood of a student getting placed, which can be used to build models to predict the placement status. The salary field is populated only for those students who have been placed


