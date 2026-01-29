# 🌸 Iris Flower Classification

This project implements a Machine Learning model to classify Iris flowers into three species: **Setosa, Versicolor, and Virginica**. This is a supervised learning task using the classic Iris dataset.

## 📌 Project Overview
The goal is to build a model that uses physical measurements—Sepal Length, Sepal Width, Petal Length, and Petal Width—to predict the correct species. This project demonstrates a complete ML pipeline from data cleaning to visualization.



## 🛠️ Key Components
- **Data Preprocessing**: Handled missing values and removed unnecessary columns (like `Id`).
- **Feature Scaling**: Implemented `StandardScaler` to normalize the range of independent variables, ensuring faster convergence for the model.
- **Algorithm**: Used **Logistic Regression** (with a high `max_iter` for stability).
- **Visualization**: Used `Seaborn` and `Matplotlib` to create bar charts and pair plots for Exploratory Data Analysis (EDA).

## 💻 Installation & Usage

1. **Clone the Repo**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/iris-classification.git](https://github.com/YOUR_USERNAME/iris-classification.git)
