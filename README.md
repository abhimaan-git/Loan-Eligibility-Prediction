loan Eligibility Prediction is a Machine Learning model based on Kaggle dataset, it consists of Credit History, co applicant income , applicant income etc. 
since Applicant an dco applicant income do not have uniformity in graphs so applying Logarithmic Transfromation to the graphs for uniformity in graphical representation.
Then we fill the Null spaces in data with proper values :- For Categorical Variable we will fill mode ( most recurring value) , & for Numerical Variable we provide mean (Average of all values)

Now we have complete dataset applying SK learn's Train test split and provide the X_train, X_test, y_train, y_test  in 80:20 ratio
than applying label encoder for preprocessing of categorical variables to binary form 0,1

coming to training part we apply DTC Decision Tree Clasifier Algorithm, it provided 70% accuracy and another Naive Bayes algorithm provided 83% accuracy which is greater than DTC .
