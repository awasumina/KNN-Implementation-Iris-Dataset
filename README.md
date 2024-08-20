# K-Nearest Neighbors (KNN) Implementation with Iris Dataset

This repository contains a Python implementation of the K-Nearest Neighbors (KNN) algorithm applied to the Iris dataset. The KNN algorithm is a simple, supervised machine learning algorithm that can be used for both classification and regression tasks.

## Dataset

The Iris dataset is a classic dataset in the field of machine learning and statistics. It contains 150 samples of iris flowers with four features each: sepal length, sepal width, petal length, and petal width. The dataset is divided into three classes, each representing a type of iris flower: Setosa, Versicolor, and Virginica.

## Implementation

The code is divided into several key functions:

- **loadDataset**: Loads the dataset from a CSV file and splits it into training and testing sets based on a specified ratio.
- **euclideanDistance**: Calculates the Euclidean distance between two data points.
- **getNeighbors**: Finds the k nearest neighbors to a given test instance from the training set.
- **getResponse**: Determines the majority class among the neighbors for classification.
- **getAccuracy**: Calculates the accuracy of the model by comparing the predicted values to the actual values in the test set.

### Example Output

Running the main function yields the following sample output having:

Train set: 101
Test set: 49
Accuracy: 93.88%
     

## Conclusion

The K-Nearest Neighbors (KNN) algorithm, as applied to the Iris dataset, demonstrates its effectiveness in classification tasks, achieving an accuracy of 93.88%. While simple, KNN is powerful and can be further optimized by experimenting with different `k` values, distance metrics, and data preprocessing techniques. This implementation serves as a solid foundation for exploring KNN in other datasets and applications.
