# Week 3 - Unsupervised Machine Learning

This project was completed as part of my Week 3 Machine Learning Internship task.

## Objective

The main objective of this project is to understand and implement unsupervised machine learning techniques. In this project, K-Means Clustering and Hierarchical Clustering were applied to the Iris dataset.

## Dataset

The Iris dataset was obtained from Scikit-learn.

- Number of samples: 150
- Number of features: 4
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Kaggle

## Steps Performed

1. Imported the required Python libraries.
2. Loaded the Iris dataset.
3. Created a Pandas DataFrame.
4. Checked the dataset and missing values.
5. Standardized the features using StandardScaler.
6. Used the Elbow Method to study the suitable number of clusters.
7. Applied K-Means Clustering with 3 clusters.
8. Visualized the K-Means clusters.
9. Applied Hierarchical Clustering with 3 clusters.
10. Visualized the Hierarchical Clustering results.
11. Evaluated both methods using the Silhouette Score.
12. Compared the clustering results.

## Results

The Silhouette Scores obtained were:

| Model | Silhouette Score |
|---|---:|
| K-Means | 0.4599 |
| Hierarchical Clustering | 0.4467 |

## Conclusion

This project provided practical experience with unsupervised machine learning. K-Means and Hierarchical Clustering were implemented on the Iris dataset, and their results were evaluated using the Silhouette Score. The project also helped in understanding data preprocessing, feature scaling, cluster selection, visualization, and model comparison.

## Files

- `week3_unsupervised_ml.ipynb` - Complete Jupyter/Kaggle notebook
- `README.md` - Project documentation
- `requirements.txt` - Required Python libraries
