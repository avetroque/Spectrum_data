- I have added a total interaction from student_log (excludes number of courses) - meaning total “web click” event
- ⁠I have added year of studies from year intake (first year or second year study)
- ⁠The accuracy i tried still hover around 50% accuracy (highest 55%)
- ⁠I have tried to change it into a binary classification - combined the distinction and good into 1, pass and fail into 0; And i managed to obtain highest 86% accuracy… should we continue binary classification moving forward?


Hi Dr, final_csv2 is the data before all this changes, and final_csv3 is everything beyond this message

EDA and prediction 

1. How do other journal paper do EDA-related to student prediction
2. EDA-univariate, bivariate, multivariate. How far should we do the EDA?

Qazi GPF
userid(final.csv)
id-idnumber(students.csv) id is userid, idnumber is matrik lama
matrik_lama - matrik_baru (matrik.csv) matrik_baru is spr code in grade
spr_code -  grade (grade.csv) 


Data consistency for qazi
	-how other pple explain extracting data from moodle-mostly via simple log 
	-TU eindhoven 17 courses, 4k students
	-Cordoba 7 courses, 438 student
	-UM 2407 courses, 16k students, 21 faculty



final_df2(no jupyter nb, only csv from nicholas)


final_df3 (got jupyter nb. use this)
	-added a total interaction from student_log (excludes number of courses) - meaning 	total “web click” event
	-added year of studies from year intake (first year or second year study)
	-accuracy still hover around 50% accuracy (highest 55%)
	-tried to change it into a binary classification - combined the distinction and 	good into 1, pass and fail into 0; And i managed to obtain highest 86% accuracy… 	should we continue binary classification moving forward?


1. Week 2-write up EDA, PREDICTION. CONCLUSION, SUMMARY
2. Week 3-study prediction
3. Week 4-write, add analysis of prediction
4. Week 5-review, reproof , submission
 
Univaratie analysis done. Next is Bivariate analysis.
Correlation for Student_summary 



Important:After reading and looking at IEEE datasets and papers on moodle, No need to include prediction. That will be another paper. Sufficient with statistical validation only and really clean the dataset 

-----------------------------------
Results
Table of prediction of different models and experiments
	by pass and fail
	by grades
Table of hyperparameters setting
Statistical analysis for dataset 


Use ChatGPT to verify whether private info still exists in the dataset or not. 
Whether an information or result is redudant-to be reviewed, discussed and decided by all members
----------------------------------------------------
For each course,calculate the total engagement for each userid. Then look at the correlation with the marks 

Add data cleaning and preprocessing 
shapiro-wilk test. 
