# Iris-Flower-Species-Classification-using-Ensemble-Learning

## Aim:
The aim of this project is to classify different species of Iris flowers based on their characteristics using ensemble learning techniques.

## Description:
In this project, we use the Iris dataset, which contains measurements of four features (sepal length, sepal width, petal length, and petal width) for three different species of Iris flowers (Setosa, Versicolor, and Virginica). The dataset is preprocessed by removing the 'Id' column and encoding the 'Species' column using label encoding.

We then apply three different classification algorithms, namely Logistic Regression, Random Forest, and k-Nearest Neighbors (KNN), individually, to classify the Iris flower species. Cross-validation with 10 folds is used to evaluate the performance of each algorithm.

Next, we create an ensemble of these classifiers using a VotingClassifier. We explore both hard voting (where the majority vote determines the predicted class) and soft voting (where the class probabilities are averaged). We compute the accuracy scores using cross-validation to compare the performance of the ensemble with individual classifiers.

Additionally, we experiment with different weight combinations for the soft voting ensemble by adjusting the weights assigned to each individual classifier. We iterate through different combinations of weights and evaluate the accuracy scores to observe the impact of weight variations on ensemble performance.

In the second part of the project, we shift our focus to a different dataset generated using the make_classification function. This dataset consists of 1000 samples with 20 features, out of which 15 features are informative, and 5 features are redundant. We generate synthetic data to demonstrate the applicability of ensemble learning techniques beyond the Iris dataset.

We create an ensemble of Support Vector Machines (SVMs) with different polynomial kernel degrees ranging from 1 to 5. We use cross-validation to evaluate the performance of individual SVMs and the ensemble using both soft and hard voting.

## Conclusion:
Through this project, we successfully demonstrate the application of ensemble learning techniques in classifying Iris flower species based on their characteristics. We compare the performance of individual classifiers, such as Logistic Regression, Random Forest, and KNN, and observe the improvement achieved by combining them using ensemble methods like VotingClassifier.

We find that the ensemble achieves higher accuracy compared to individual classifiers, indicating the benefit of combining diverse models. We further explore the impact of weight variations on the ensemble's performance and observe how different weight combinations affect the accuracy.

In the second part of the project, we extend our analysis to a synthetic dataset and demonstrate that ensemble learning techniques can be applied beyond a specific dataset like Iris. By creating an ensemble of SVMs with different polynomial kernel degrees, we show how ensemble methods can adapt to different classification problems.

Overall, this project highlights the effectiveness of ensemble learning in improving classification accuracy and encourages further exploration of ensemble methods for various machine learning tasks.
