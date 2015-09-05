# SI - Pattern Recognition

**Table-of-contents**

* [Dependencies](#dependencies)
* [Ensemble classifiers](#ensemble-classifiers)
* [To perform the practise](#to-perform-the-practise)

More description is given in the subsections.

## Dependencies

The following practise has been tested with **Ubuntu 14.04**.

In order to carry out the practise, the following dependencies are needed:

* ipython notebook - `conda install ipython-notebook`
* scikit-learn - `conda install scikit-learn`
* mpld3 - `pip install mpld3`

We strongly recommend to use a Linux environment to perform this practise.

## Ensemble classifiers


The following module of the framework will be studied:
![Alt text](./readme-images/pr-framework-fc.png)

### AdaBoost

In order to ease the practise, you will go step by step to implement AdaBoost:

* Get the principle of information gain,
* Implement a simple decision stump classifier,
* Finally, implement AdaBoost with the decision stump as weak learner.

### Random Forest

In the way as with AdaBoost, you will go step by step:

* First, you will try the decision tree and test the parameter allowing to select a subset for training at each node of the tree,
* Then, understand the principle of bagging,
* Finally, apply this two random principle to implement the Random Forest classifier.

## To perform the practise

### Assignment procedure

In order to perform the practise, you will have to fork the current project. To do so,

- [Fork](https://help.github.com/articles/fork-a-repo/) the current project by click on the Fork icon ![Do not fine the icon](./readme-images/fork-icon.png),
- Select your GitHub profile if necessary,
- Clone the repository ![Do not fine the icon](./readme-images/git-clone.png),
- Solve the practise by executing the Ipython notebook,
- Commit & push your changes in your own repository,
- Make a [pull request](https://help.github.com/articles/using-pull-requests/).

### Execute the Ipython notebook

Enter the following command in a terminal `ipython notebook`.

This command should run the server locally via your default web browser and you will be able to play with the notebook.

If you are just curious to see what the ipython notebook look like, you can view it [there](http://nbviewer.ipython.org/github/ViBOT-Erasmus/B31XI-SI-Ensemble-Classifiers/blob/master/06-ensemble-classifiers.ipynb).

Enjoy!!!

