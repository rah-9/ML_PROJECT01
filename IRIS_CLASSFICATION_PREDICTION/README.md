# Iris Classification with KMeans Clustering

This repository contains a Python implementation of an Iris Classification model using KMeans clustering. The model predicts the species of iris flowers based on their petal length and petal width.

## Dataset

The Iris dataset is used for training the model. It includes three species of iris flowers: Setosa, Versicolor, and Virginica. The dataset is loaded using seaborn's `load_dataset` function.

## Dependencies

Make sure you have the following Python libraries installed:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly Express
- Scikit-learn

You can install them using the following command:

```bash
pip install numpy pandas matplotlib seaborn plotly scikit-learn

iris-classification/
│
├── iris_classification.py      # Python script containing the Iris Classification model and user input prediction.
└── README.md                    # Documentation about the project.


## Visualizations

The repository includes 3D scatter plots and a pairplot to visualize the distribution of iris flowers based on their features.

### 3D Scatter Plots

Two 3D scatter plots are generated using Plotly Express, showcasing the distribution of iris flowers based on petal length, petal width, sepal length, and sepal width.

bash ```

python iris_visualizations.py

```
This project is licensed under the MIT License - see the `LICENSE` file  for details.
