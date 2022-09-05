# Lab-6
This is the final Lab for the class Introduction to Machine Learning DIT 45100 AIW01

Install the following python packages needed for this Lab. I would advice that as practice for industry, you install these packages in a virtual environment.

`pip install jupyterlab` `pip install matplotlib` `pip install seaborn` `pip install pandas` `pip install sklearn`

You will be provided with some sample code in sample_code.ipynb that will provide you information that should be enough for you to complete the labs. The following tasks below are our objectives for the lab

You will be implementing the following algorithms we discussed in class:

Classification with SVM's (100 marks)
  - Download the Iris dataset from sklearn
    - Prepare data
      - Split your data into a training and test set
      - Feature scale your data
      - You will be grabbing 2 features from the dataset (You can use any of the feature selection methods you learnt in class)
         - Hint: I used chi-square feature selection because it is easy, fast and gave the same results as recursive feature elimination in previous labs
         - Show which features were selected 
    - Train svm's on the chosen features with the following parameters. 
       - kernel="linear", C=1.0
          - Calculate the accuracy and hinge loss on the training set
          - Calculate the accuracy and hinge loss on the testing set
          - Plot the decision boundary with each point colored with its groundtruth class in 2D
            - encircle your support vectors 
          - Plot the decision boundary with each point colored with its groundtruth class in 3D
       - kernel="linear", C=100000
          - Calculate the accuracy and hinge loss on the training set
          - Calculate the accuracy and hinge loss on the testing set
          - Plot the decision boundary with each point colored with its groundtruth class in 2D
            - encircle your support vectors
          - Plot the decision boundary with each point colored with its groundtruth class in 3D
       - kernel="linear", C=0.0001
          - Calculate the accuracy and hinge loss on the training set
          - Calculate the accuracy and hinge loss on the testing set
          - Plot the decision boundary with each point colored with its groundtruth class in 2D
            - encircle your support vectors
          - Plot the decision boundary with each point colored with its groundtruth class in 3D
      - kernel="poly", degree=2, coef0=0
          - Calculate the accuracy and hinge loss on the training set
          - Calculate the accuracy and hinge loss on the testing set
          - Plot the decision boundary with each point colored with its groundtruth class in 2D
            - encircle your support vectors
      - kernel="poly", degree=2, coef0=1
          - Calculate the accuracy and hinge loss on the training set
          - Calculate the accuracy and hinge loss on the testing set
          - Plot the decision boundary with each point colored with its groundtruth class in 2D
            - encircle your support vectors
      - kernel="poly", degree=3, coef0=1
          - Calculate the accuracy and hinge loss on the training set
          - Calculate the accuracy and hinge loss on the testing set
          - Plot the decision boundary with each point colored with its groundtruth class in 2D
            - encircle your support vectors
      - kernel="rbf", C=1.0, gamma="scale"
          - Calculate the accuracy and hinge loss on the training set
          - Calculate the accuracy and hinge loss on the testing set
          - Plot the decision boundary with each point colored with its groundtruth class in 2D
            - encircle your support vectors
    
        
