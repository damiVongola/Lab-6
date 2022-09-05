# Lab-6
This is the final Lab for the class Introduction to Machine Learning DIT 45100 AIW01

Install the following python packages needed for this Lab. I would advice that as practice for industry, you install these packages in a virtual environment.

`pip install jupyterlab` `pip install matplotlib` `pip install seaborn` `pip install pandas` `pip install sklearn`

You will be provided with some sample code in sample_code.ipynb that will provide you information that should be enough for you to complete the labs. The following tasks below are our objectives for the lab

You will be implementing the following algorithms we discussed in class:

Classification with SVM's (100 marks)
- Plotting Decision boundaries and getting accuracy, f1-score, and AUC
  - Download the Iris dataset from sklearn
  - You will be grabbing 2 features from the dataset (You can use any of the feature selection methods you learnt in class)
    Hint: I used chi-square feature selection because it is easy, fast and gave the same results as recursive feature elimination in previous labs
  - Train an svm on the chosen features with the following parameters. 
    - Split your data into a training and test set
      - kernel="linear", C=1.0
        - Calculate the accuracy, f1-score and AUC on the training set
        - Calculate the accuracy, f1-score and AUC on the testing set
        - Plot the decision boundary with each point colored with its groundtruth class in 2D
        - Plot the decision boundary with each point colored with its groundtruth class in 3D
     - kernel="linear", C=100000
        - Calculate the accuracy, f1-score and AUC on the training set
        - Calculate the accuracy, f1-score and AUC on the testing set
        - Plot the decision boundary with each point colored with its groundtruth class in 2D
        - Plot the decision boundary with each point colored with its groundtruth class in 3D
     - kernel="linear", C=0.0001
        - Calculate the accuracy, f1-score and AUC on the training set
        - Calculate the accuracy, f1-score and AUC on the testing set
        - Plot the decision boundary with each point colored with its groundtruth class in 2D
        - Plot the decision boundary with each point colored with its groundtruth class in 3D
    - kernel="rbf", C=1.0, gamma="scale"
        - Calculate the accuracy, f1-score and AUC on the training set
        - Calculate the accuracy, f1-score and AUC on the testing set
        - Calculate the accuracy, f1-score and AUC for the model
        - Plot the decision boundary with each point colored with its groundtruth class in 2D
    - kernel="poly", degree=2, coef0=0
        - Calculate the accuracy, f1-score and AUC on the training set
        - Calculate the accuracy, f1-score and AUC on the testing set
        - Calculate the accuracy, f1-score and AUC for the model
        - Plot the decision boundary with each point colored with its groundtruth class in 2D
    - kernel="poly", degree=2, coef0=1
        - Calculate the accuracy, f1-score and AUC on the training set
        - Calculate the accuracy, f1-score and AUC on the testing set
        - Calculate the accuracy, f1-score and AUC for the model
        - Plot the decision boundary with each point colored with its groundtruth class in 2D
    - kernel="poly", degree=3, coef0=1
        - Calculate the accuracy, f1-score and AUC on the training set
        - Calculate the accuracy, f1-score and AUC on the testing set
        - Calculate the accuracy, f1-score and AUC for the model
        - Plot the decision boundary with each point colored with its groundtruth class in 2D
    
        
