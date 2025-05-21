#  Iris Flower Classification using Random Forest

This project demonstrates a complete machine learning workflow using the classic **Iris dataset**. A **Random Forest Classifier** is trained to identify flower species based on their sepal and petal dimensions. The model is evaluated using a **Confusion Matrix** and **Classification Report** to showcase its accuracy and predictive power.

##  Project Overview
- **Objective**: Build a model to classify Iris flowers into Setosa, Versicolor, or Virginica.
- **Dataset**: Built-in Iris dataset from `sklearn.datasets`.
- **Tools Used**: Python, Scikit-learn, Pandas, Matplotlib, Seaborn.

##  Technologies
- Python (Colab)
- scikit-learn
- pandas
- matplotlib
- seaborn

##  Process
1. Load and explore the Iris dataset
2. Split into training and test sets (70-30)
3. Train a Random Forest model
4. Predict on test data
5. Evaluate using:
   - Confusion Matrix (with visualization)
   - Classification Report (precision, recall, F1-score)
   - Accuracy Score
6. Feature importance visualization

##  Sample Output

Confusion Matrix:
[[19 0 0]
[ 0 13 0]
[ 0 0 13]]

Accuracy: **100%**

##  Conclusion

The Random Forest model achieved perfect classification on the test set. This notebook demonstrates fundamental machine learning concepts and is a strong foundation for future model comparison, tuning, or deployment.

##  Files

- `IrisDataset.ipynb`: The full Colab notebook
- `README.md`: This file

##  License

MIT License
