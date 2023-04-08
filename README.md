# **Customer-Conversion-Prediction**
Project for Data Science program - GUVI

The aim of this project is to predict customer conversion for an insurance company using historical data. 

Features: age , job , marital status, call type, education qualification , call duration, day , month, previous call outcome and number of calls
Target:To predict whether the contacted customer will opt an insurance.

It is a Supervised Learning Binary classification problem.
Done data cleaning, outlier analysis, EDA, Balancing, Splitting, Scaling, Model and Evaluation of model.
As the data is not balanced, balancing is done by SMOTEENN. AUROC is used as an evaluation metric.

# **KEY FINDINGS**
  XG Boost model performs better than other models. Duration plays a major role as higher the duration,  greater the customer conversion rate.
  
1.   Blue collar job peoples are mostly targeted by the bank officials followed by management professionals. Management professionals were converted successfully as a customer followed by technicians and admins. So, they have to target more technicians and admins as they have more success on customer conversion than blue collar job professionals.
2. Bank professionals contacted married people the most followed by singles and divorced people. But, the coustomer conversion success percent is more for singles(14.8%) followed by divorced (11.9%) and married has low 10% success. So, I suggest to target more singles and divorced people also.
3. In the case of education_qual, Bank professionals contacted secondary qualified people the most followed by tertiary and primary  qualified people. But, the coustomer conversion success percent is more for tertiary qualified people(15%) followed by secondary qualified (10.5%). So, I suggest to target more tertiary qualified people also.
4. Bnak professionals contacted via cell phones and have found successs in that.  
5. Bank professionals contacted people mostly in may month as also found succcess in that followed by july. But August month have the 2nd most customer conversion success than july so, I suggest to cintact more people in August also.
6. Most of the previous outcomes are recorded as "unknown" followed by "Failure". As "First impression is the Best impression" they need to track the previous outcomes and try to improve the customer conversion rate.





