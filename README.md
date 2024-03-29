**SPAM CLASSIFICATION**
    Data Loading and Preprocessing:
        The code first loads a dataset from a CSV file ('spam.csv') containing text messages and their labels (spam or ham).
        It preprocesses the text data by converting labels to numeric format (0 for ham and 1 for spam) and dropping unnecessary columns.

    Model Training:
        It splits the dataset into training and testing sets using the train_test_split function from scikit-learn.
        Two classifiers are trained:
            Gaussian Naive Bayes classifier (GaussianNB) and Decision Tree classifier (DecisionTreeClassifier).

    Model Evaluation:
        After training, the classifiers are used to make predictions on the testing data.
        The accuracy score and classification report are calculated for both classifiers using the accuracy_score and classification_report functions from scikit-learn.

    Writing Results to a File:
        The results of both classifiers (accuracy score and classification report) are written to a text file named "results_comparison.txt".
        Each classifier's results are labeled with a heading for clarity.

    Printing a Message:
        Finally, a message is printed to indicate that the comparison file has been created.
