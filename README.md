# Autumn Project 2021: Machine Learning and Statistics

**Due: last commit on or before 20<sup>th</sup> August 2021**


These are the instructions for the Autumn project in 2021.
This project will be worth 100% of your marks for this module, unless otherwise agreed in advance with the lecturer.
Your whole submission should be in the form of a single GitHub repository.
The commit history of the repository should reflect the effort you put into it.
Your last pushed commit before the deadline will form your submission.
You should immediately create this repository and submit its URL using the following form.


[Click here to submit your GitHub repository URL](https://forms.office.com/r/whWTJsDuz7)



You should make regular, appropriate commits to your repository and push these to GitHub.
If you set your repository to private, make sure to add `ianmcloughlin` as a collaborator.
Please also read the **[Using git for assessments](https://github.com/ianmcloughlin/using-git-for-assessments/raw/master/using-git-for-assessments.pdf)** document which applies to this project.
As always, you must also follow [the code of student conduct and the policy on plagiarism](https://www.gmit.ie/general/quality-assurance-framework).


## What to do

Create a Jupyter notebook in Python 3 that compares the use of the [scikit-learn `KNeighborsClassifier`](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html) with the use of keras [keras](https://keras.io/) for classifying the three species of iris identified in [Fisher's famous iris dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set).
The notebook should include the following.

1. A description of the iris dataset and an explanation of why it so heavily referenced in machine learning, particularly in respect to classification algorithms.
2. An explanation and code to train a k-nearest-neighbour classifier for the iris species based on the dataset using `scikit-learn`.
3. An explanation and code to train a classifier for the iris species based on the `keras` package.
4. A comparison of the accuracy of your two classifiers.


The notebook should be stored in your GitHub repository along with an appropriate README detailing how to run it.

## Enhancements

To enhance your submission, and potentially enhance your mark, you might consider implementing some or all of the following ideas.

1. Give an explanation and code to train an SVM classifier for the iris species based on [`scikit-learn`](https://scikit-learn.org/stable/modules/svm.html).
2. Give an analysis of which of the four numeric variables (sepal length, sepal width, petal length, petal width) is the most important in identifying the correct species of iris. 
3. Use [cross validation](https://scikit-learn.org/stable/modules/cross_validation.html) to analyse your classifiers.

## Marking scheme

The following marking scheme will be used to mark your submission out of 100%.
The examiners' overall impression of your submission may influence individual marks.
It is important that your submission provides direct evidence of each of the items listed in each category.
For instance, your commit history should demonstrate and provide evidence that you had a pragmatic attitude to completing the assessment.
Likewise, your submission should have references in it to demonstrate that you considered the literature and the work of others.
  

| Weight | Category | Description |
|---|---|---|
|25% | Research | Evidence of research performed on topic; submission based on referenced literature, particularly academic literature; evidence of understanding of the documentation for any software or libraries used. |
|25% | Development | Environment can be set up as described; code works without tweaking and as described; code is efficient, clean, and clear; evidence of consideration of standards and conventions appropriate to code of this kind. |
|25% | Consistency | Evidence of planning and project management; pragmatic attitude to work as evidenced by well-considered commit history; commits are of a reasonable size; consideration of how commit history will be perceived by others. |
|25% | Documentation | Clear documentation of how to create an environment in which any code will run, how to prepare the code for running, how to run the code including setting any options or flags, and what to expect upon running the code. Concise descriptions of code in comments and README. |