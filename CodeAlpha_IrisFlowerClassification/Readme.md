Iris Flower Classification 🌸
A machine learning project that classifies Iris flowers into three species (Setosa, Versicolor, and Virginica) based on their physical measurements (sepal and petal length/width).

📄 Project Overview
This project uses the famous Iris dataset to demonstrate a complete machine learning workflow, including data preprocessing, feature scaling, and classification using Logistic Regression.

🚀 Features
Data Analysis: Exploratory data analysis (EDA) using Seaborn pair plots and bar charts.

Preprocessing: Handling feature scaling with StandardScaler to ensure model convergence.

Machine Learning: Implementation of a Logistic Regression model via Scikit-learn.

Evaluation: performance tracking using Accuracy Scores and Confusion Matrices.

🛠️ Tech Stack
Language: Python 3.12

Libraries: * pandas (Data manipulation)

scikit-learn (Machine Learning)

seaborn & matplotlib (Visualization)

📊 Visualizations
The project includes several plots to understand the data:

Pair Plots: To visualize the clusters of different species.

Bar Graphs: To compare the average dimensions of each flower type.

Confusion Matrix: To visualize where the model predicted correctly vs. where it made errors.

💻 How to Run
Clone the repo:

Bash
git clone https://github.com/your-username/iris-classification.git
Install dependencies:

Bash
pip install pandas scikit-learn seaborn matplotlib
Run the Jupyter Notebook: Place iris.csv in the same directory and open Iris_Classification.ipynb.

📈 Results
The model currently achieves an accuracy of ~97-100% on the test set, demonstrating that Iris species are highly distinguishable based on their petal and sepal dimensions.
