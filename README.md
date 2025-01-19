## Student Preformance Predictor

Built and End-to-End Machine Learning model which predicts the performance of a student based on certain factors like:

- gender : sex of student -> (Male/Female)

- Race/ethnicity: The student's racial or ethnic background (Asian, African-American, Hispanic, etc.)

- Parental level of education: The highest level of education attained by the student's parent(s) or guardian(s)

- Lunch: Whether the student receives free or reduced-price lunch (yes/no)

- Test preparation course: Whether the student completed a test preparation course (yes/no)

- Math score: The student's score on a standardized mathematics test

- Reading score: The student's score on a standardized reading test

- Writing score: The student's score on a standardized writing test

This project handles Data Ingestion, Data transformation and Model Training in order to delivery the output.

Created custom exceptions which lets me know if any error is found in the program. Through logger files i can get access of all the errors found. 

During the process of developing this project. I used many machine learning models and performed hyperparameter tuning, through which the best performing model Ridge Regression with a R2_score of 88.05.

Used a simple html code to create a front end page to display my final outcome.

image.png

