# Predict College acceptence 
For my two models I used a simple Linar regression model and Knn classifier. The data set that was used was Graduate school admissions for Indian students. The data set had 8 features: GRE Score, TOEFL Score, University Rating, SOP, LOR, CGPA, Research, Chance of Admitance. Using the GRE scores and Undergraduate GPA score, the algorythems would predict weather a student would be accepted to the college. These two features tend to have a big effect on the acceptance rate, and both were able to use these features. The difference between the models is that for Knn, I converted the acceptance rate into numaric True (accepted) False (not accepted) values. A person with an acceptance rate of .75 or higher was considered accepted, anything other were considard not accepted. For the Simple Regression model I used acceptance rates as floats.
