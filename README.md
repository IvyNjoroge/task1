# TASK1
UNIVERSITY ADMISSION – Task 1<br>

In the competitive landscape of higher education, universities receive a multitude of applications from prospective students seeking admission. To make informed decisions and predict their chances of admission, it is essential for students to understand the factors that influence the admission process. In this context, a regression model can be developed to assist students in estimating their likelihood of being admitted to a university based on various factors.<br>
The regression model aims to leverage a dataset consisting of important features that affect the chances of admission. These features include: GRE Score, TOEFL Score, University rating, Statement of Purpose, Recommendation Letter, Cumulative Grade Point Average and Research.<br>
My aim was to create a regression model to help students predict the chances of admission to a university. I separated the data in train and test partitions, then compared results of 5 different regression models: Linear Regression, Random Forest, SVR, Gradient Boosting and Ada Boost.<br>
The different parameters in the dataset are -<br>
•	Serial No : To uniquely identify students<br>
•	GRE Score : Score of GRE test which is an important test for admissions in the graduate school or business school application process globally.<br>
•	TOEFL Score : Test of English as a Foreign Language exam score<br>
•	University Rating : Rating of the University out of 5<br>
•	SOP : Related to Statement of Purpose(SOP) for applying to a particular course or university.<br>
•	LOR : Some score related to a letter of recommendation<br>
•	CGPA : CGPA is a past performance measure of aspirant<br>
•	Research : Binary values of either 1 or 0<br>
•	Chance of Admit : Probability of the student to get admission the university<br>

DATA PREVIEW:<br>

 ![image](https://github.com/IvyNjoroge/task1/assets/111203571/6d494c5b-1d75-4bb4-ae7f-7026619e5875)

The data contained 400 rows and 9 columns.<br>

CORRELATION:<br>

![image](https://github.com/IvyNjoroge/task1/assets/111203571/85e32a92-40c0-4289-9ace-af52d146ae22)<br>

CGPA has the highest correlation to Chance of Admit meaning it's the most important feature for getting selected while research is the least. <br>
 
Comparison between CGPA and Chance of Admission:<br>

 ![image](https://github.com/IvyNjoroge/task1/assets/111203571/b9170646-0b7b-450a-938e-3232213b97c4)<br>

Comparison between GRE Score and Chance of Admission:<br>

 ![image](https://github.com/IvyNjoroge/task1/assets/111203571/7a5e7674-9d4d-4f6d-b8ff-d64f0f471d3c)<br>

Comparison between TOEFL Score and Chance of Admission:<br>

 ![image](https://github.com/IvyNjoroge/task1/assets/111203571/9221027f-2067-4dba-b16b-b0d917510714)<br>

Comparison of R2 Scores of all 5 regression models:<br>

 ![image](https://github.com/IvyNjoroge/task1/assets/111203571/a756b38f-bca6-4fed-bdc7-307e1b0395f8)<br>

CONCLUSION<br>
Based on the provided metrics, you can make the following observations:<br>
•	Linear Regression has the highest R2 score (0.821) among the models, indicating a relatively good fit to the data.<br>
•	Random Forest Regressor and Gradient Boosting Regressor also have high R2 scores (0.809 and 0.796, respectively), suggesting good performance.<br>
•	Ada Boost Regressor has a slightly lower R2 score (0.787) but still performs reasonably well.<br>
•	SVR has a lower R2 score (0.635) compared to the other models, indicating a weaker fit to the data.<br>
In terms of MAE and MSE, Linear Regression has the lowest values, followed closely by Random Forest Regressor and Gradient Boosting Regressor. SVR has the highest MAE and MSE values among the models, indicating higher prediction errors.<br>
Based on these metrics, I would consider Linear Regression as the best model.<br>

RECOMMENDATIONS
1.	Focus on CGPA: Since CGPA has the highest correlation with the "Chance of Admit," it is crucial for students to prioritize their academic performance. Strive to achieve a high CGPA by putting effort into coursework, assignments, and exams. Seek additional academic support if needed.<br>
2.	Prepare for GRE and TOEFL: The GRE and TOEFL scores are important factors considered by universities during the admissions process. Dedicate time to prepare for these exams by using study materials, taking practice tests, and seeking guidance if required. Aim for competitive scores to increase your chances of admission.<br>
3.	Enhance Statement of Purpose and Letters of Recommendation: The SOP and LOR play a role in the admissions process. Make sure to craft a compelling SOP that highlights your motivations, goals, and relevant experiences. Request LORs from individuals who can provide strong recommendations and showcase your abilities and potential.<br>
4.	Consider University Ratings: The dataset includes a feature for university ratings. Research and consider universities with higher ratings as they may offer better opportunities and resources. However, keep in mind that university ratings should not be the sole determining factor. Consider other aspects such as faculty, research opportunities, program fit, and location.<br>
5.	Research Experience: Although the correlation suggests that research has a relatively lower impact on admission chances, having research experience can still be beneficial. Engage in research projects or internships to gain practical knowledge and showcase your ability to contribute to the field. It can also set you apart from other applicants.<br>
6.	Analyze Regression Model Results: Evaluate the performance of the different regression models (Linear Regression, Random Forest, SVR, Gradient Boosting, and Ada Boost) based on the provided metrics (R2 score, MAE, MSE). Identify the model that yields the best results and can provide accurate predictions. Consider the strengths and weaknesses of each model before making a final selection.<br>
7.	Seek Guidance and Support: If you are unsure about the admissions process or need assistance in improving your profile, consider seeking guidance from mentors, professors, or professional counselors. They can provide valuable insights, personalized advice, and help you strategize your approach to maximize your chances of admission.<br>

Dataset: https://www.kaggle.com/datasets/akshaydattatraykhare/data-for-admission-in-the-university
