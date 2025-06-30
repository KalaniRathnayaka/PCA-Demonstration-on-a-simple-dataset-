Project Title: PCA on Iris Dataset – Dimensionality Reduction & Visualization
✅ Project Description
This project demonstrates how to apply Principal Component Analysis (PCA) using Python to reduce the number of dimensions in the classic Iris dataset from 4 features to 2, while preserving the data's variance. The final output is a 2D visualization that highlights the separation between flower species.

📂 Dataset Used
Name: Iris Dataset

Source: Built-in from sklearn.datasets.load_iris()

Description: Contains 150 samples of iris flowers from 3 species (Setosa, Versicolor, Virginica), with 4 features per sample:

Sepal length

Sepal width

Petal length

Petal width

🔧 Technologies & Libraries Used
Python 3.x

pandas – Data handling

numpy – Numerical operations

seaborn, matplotlib – Visualization

scikit-learn – PCA, standardization, dataset loading

📌 Key Tasks Performed
Loaded and explored the dataset

Displayed:

Total number of samples

Number of species/classes

Feature information

Standardized the dataset

Applied PCA to reduce from 4D to 2D

Plotted the PCA result using a scatter plot with color-coded species

🖼️ Sample Output
A 2D scatter plot where each point represents a flower

Points are grouped by species

Principal Component 1 (PC1) and PC2 capture most of the variance

📝 How to Run
Open the .ipynb file (or copy code to your notebook)

Run all cells

Ensure you have the following libraries installed:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
🎓 Learning Outcome
Students will understand:

What PCA is and when to use it

Why data standardization is important

How dimensionality reduction simplifies visualization

How to use scikit-learn for real data science workflows
