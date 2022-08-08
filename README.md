# A tool to classify emails as either spam or non-spam based 57 features of the email using SVM and tree-based methods

1. we train the data in the dataset
2. we set the seed to 10
3. we grow a tree on the trained data set

 ![](https://github.com/la6if9/Classification-with-trees/blob/main/Spam%20Tree.png)

4. Bagging/random forest

![](https://github.com/la6if9/Classification-with-trees/blob/main/Rplot1.png)

![](https://github.com/la6if9/Classification-with-trees/blob/main/Rplot2.png)

5. Boosting: for tuning the nIter hyperparameter
6. Support Vector Machines
7. we use the function tune("svm", . . .) to tune the cost parameter for an svm with a radial kernel (too many hyperparameters)
8. Plotting

9. ![](https://github.com/la6if9/Classification-with-trees/blob/main/Rplot%20SVM.png)
