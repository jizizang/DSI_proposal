# Predicting Case Status of H-1B Visa Applications

1. What are you trying to do? Articulate your objectives using absolutely no jargon (i.e. as if you were explaining to a salesperson, executive, or recruiter).

“An H-1B visa allows an individual to enter the United States to temporarily work at an employer in a specialty occupation. In 2015, there were 348,669 applicants for the H-1B filed, of which 275,317 were approved.”[1] In this project, historical case disclosure data will be used to predict the final outcome of the H-1B application using machine learning algorithms. We will try to investigate what are the major factors that affect the decision. It will be very helpful to know these information for employers to reduce potential valuable employee turnover.

2. How has this problem been solved before? If you feel like you are addressing a novel issue, what similar problems have been solved, and how are you borrowing from those?

There are few work on study of the H1-B data.[2-4] One of them provided a ROC graph with 50% of the area under the curve, which is equivalent to random guess. It seems only older data (till 2016) with limited number of features (seven) have been studied. In this project, we will use the latest data including 2017 and start from all the 51 features.

3. What is new about your approach, why do you think it will be successful?

We will use advanced supervised machine learning for this classification project. As long as the information we get from the data is sufficient and the rejection is not random, I believe it will be successful since these machine learning techniques have been proved successful for many applications in different fields.
    
4. Who cares? If you're successful, what will the impact be?

Employer invests money and time on hiring high-skilled foreign people and all these efforts will be wasted if the H1-B application is rejected. Knowing the factors that influence the application results will help employer to make right decisions to avoid the rejection.

5. How will you present your work? 

I plan to present my work with slides presentation.

6. What are your data sources? What is the size of your dataset, and what is your storage format?
       
       The data can be downloaded herer: https://www.foreignlaborcert.doleta.gov/performancedata.cfm#dis. They are in .xlsx format. For 2014, 2015, 2016 and 2017 records, the data size is ~600Mb. I have downloaded them and will convert them to csv files.

7. What are potential problems with your capstone, and what have you done to mitigate these problems?

The data seem to be unbalanced. The rejection rate is much lower than approval rate. It’s probably hard to precisely predict the rejection. We may try re-sample the data such as undersampling,  oversampling or SMOTE(SYNTHETIC MINORITY OVER SAMPLING).

8. What is the next thing you need to work on?

Data were downloaded and will be converted to csv files. Better understanding of the meaning of each feature and more domain knowledge will be very helpful for this project. I will first work on small chunk of data or just one year of data and then the whole data. 



[1]. https://en.wikipedia.org/wiki/H-1B_visa

[2]. https://www.datacamp.com/community/tutorials/predicting-H-1B-visa-status-python

[3]. https://cseweb.ucsd.edu/classes/wi17/cse258-a/reports/a054.pdf

[4]. http://cs229.stanford.edu/proj2017/final-reports/5208701.pdf
