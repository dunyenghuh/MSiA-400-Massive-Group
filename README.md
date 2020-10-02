# MSiA-400-Massive-Group

Weekly update by Oct 2th

We contacted our point of contact, Aaron and scheduled our initial meeting for next week. Since we didn’t have access to our data this week, we brainstormed some ideas based on the project description provided, came up with some modeling methods, and studied statistical concepts about sampling to prepare for the project.

The main focus of this project was to answer the question: “Do students show different inclinations to the STEM field based on their past experiences?”. To examine the relationship between people’s interest in the STEM field and all the past experience variables, we plan to use classifications (classify interested in STEM field as 1, and not interested in STEM field as 0). Speaking of model choosing, we would use the Logistic Regression model as our baseline, and try ensemble models like Random Forest and XGboost. 

We also noticed that our sample size is relatively small (60 samples in the treatment group and 120 samples in the control group), and such small sample size may limit the performance of the machine learning models above. Therefore, besides classification, we plan to employ statistical hypothesis testing such as t-test to explore how those features contribute to people’s interest towards science and examine any multicollinearity between those variables. Since there are around 600 variables and many of them contain “null” values or overlapped with other variables, we plan to first filter out insignificant variables by statistics test (like correlation test) before putting it into models. 
