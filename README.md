# GlobalTerroristDBPredictions



GTD or Global Terrorist Attack database is a database of around 1,90,000 terrorist attacks worldwide since 1970. 
This is available freely on  https://www.start.umd.edu/research-projects/global-terrorism-database-gtd as well as on Kaggle https://www.kaggle.com/tags/terrorism

This data is in .csv format and is around 1,58,997 KB in size. It consists information of when the attack took place, where the attack took place, 
who was the target group, what is the identified terrorist group name, weapons used etc. 
Out of the total 135 columns, only the most informative columns will be used to predict the gname or terrorist group name. As the data is huge so it’s quite important
to use Feature Selection techniques to pick the most relevant features. 

I have used a section of data only so it fits in my RAM.

The Class that I am predicting is the gname. Following Feature Selection will be Data 
Preprocessing Techniques to cleanse the data to get it to a form to apply Machine Learning techniques on it. 
Summary of results, I achieved 90% + accuracy in predicting the gname with various models: KNN, Random Forest, Decision Trees, SVM and Naive Bayes.
