# lead_score_case_study
Problem Statement:
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. 
The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

X Education has appointed our team to help them select the most promising leads, i.e., the most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each lead such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

Data Provided:
The dataset provided consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not. The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t converted.

Solution:
We have undertaken the following steps to build a regression model that predicts whether a lead will get converted or not:
1. Data Loading and Cleaning
2. Data Segmentation
3. Dummy variable creation
4. Train-Test split
5. Scaling using Min Max scaler
6. Feature selection
7. Model Building
8. Evaluating the model and determining the optimal threshold
9. Evaluating the model on Test Data
