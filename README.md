This is the Breast Cancer Wisconsin Diagnostic dataset that is bundled with scikit-learn

https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html#sklearn.datasets.load_breast_cancer

The dataset contains 569 samples, each with 30 features and a label indicating whether a tumor was malignant (0) or benign (1). There are only two labels, so this dataset is commonly used to perform binary classification. 

Using this dataset, reimplement the steps of this chapter’s classification case study in Sections 15.2–15.3.
* Use the GaussianNB (short for Gaussian Naive Bayes) estimator. 
* When you execute multiple classifiers (as in Section 15.3.3) to determine which one is best for the Breast Cancer Wisconsin Diagnostic dataset, include a LogisticRegression classifier in the estimators dictionary.
  

**Implement the following steps/tasks. Clearly document each step with markup descriptions. (HINT: look at the steps in the book from 15.2.2-15.3.3)**
* Load the data
* Display the data description
* Check the sample and target sizes
* Split the data for training and testing
* Create the model (GaussianNB)
* Train the model
* Predict
* Determine accuracy with score
* Determine accuracy with confusion matrix.  
* Visualize the confusion matrix using a heat map
* Determine accuracy with classification report
* Perform k-fold cross validation
* Run multiple models using a dictionary of esitmators and a for loop to find the best one, include GaussianNB, KNeighborsClassifier, LogisticRegression, and SVC.
* Which classifer performs the best?






