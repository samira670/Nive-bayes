# Naive Bayes Classifier on the Iris Dataset

This project demonstrates the use of Naive Bayes classifiers to predict the species of flowers in the **Iris dataset**. It includes three types of Naive Bayes classifiers: **BernoulliNB**, **MultinomialNB**, and **GaussianNB**, and evaluates their performance based on several metrics, including accuracy, precision, recall, and F1 score.

## Dataset
The dataset used in this project is the **Iris Dataset**, which is a famous dataset for classification tasks. It contains 150 samples of flowers belonging to three species (`setosa`, `versicolor`, and `virginica`). Each sample has 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

The dataset is available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/machine-learning-databases/iris/iris.data).

## Project Structure

- **load_iris_data**: This function downloads the Iris dataset, processes it into feature and target variables, and converts target classes into numerical labels.
- **evaluate_models**: This function splits the dataset into training and testing sets, trains three Naive Bayes classifiers (BernoulliNB, MultinomialNB, and GaussianNB), and evaluates their performance.
  
## Model Performance

The project trains and evaluates three different Naive Bayes models:
1. **BernoulliNB**: Designed for binary or binarized data, but less effective in this case.
2. **MultinomialNB**: Suitable for discrete counts (works well for text classification). This performs very well in this case.
3. **GaussianNB**: Based on the assumption that features follow a normal distribution. Also performs well for this dataset.

