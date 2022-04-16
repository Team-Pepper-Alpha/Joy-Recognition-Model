# Joy Recognition Model

This is where we create the machine leraning model for recognizing happy emotion behind people's mask.

1. Split it in to three sections: Preprocessing, Trainning, and Testing. 
    - The dataset contains different action unit extracted from OpenFace
2. We train these data into 2 different machine learning algorithms.
    - **SVM** (Support Vector Machine)
    - **MLP Classifier** (Multi-Layer Perceptron Classifier)
3. We then use 5-fold cross validation to see the different between the accuracy between these 2 machine learning algorithm. We also use confusion matrix to see the amount of true positive that each algorithm can predict from our dataset.

## References

- https://numpy.org
- https://pandas.pydata.org
- https://scikit-learn.org/stable/modules/neural_networks_supervised.html
- https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html
- https://seaborn.pydata.org/introduction.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.KFold.html
- https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_predict.html
- https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html
- https://matplotlib.org/3.5.0/api/_as_gen/matplotlib.pyplot.html