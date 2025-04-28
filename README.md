
# 🚢 Titanic Classification - Machine Learning Project

This project applies **machine learning models** to predict survival outcomes on the Titanic dataset. It is inspired by the famous Kaggle competition: [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic).

## 📁 Dataset

- **Source**: [Titanic - Kaggle](https://www.kaggle.com/c/titanic)
- **Attributes**:
  - PassengerId
  - Survived
  - Pclass
  - Name
  - Sex
  - Age
  - SibSp
  - Parch
  - Ticket
  - Fare
  - Cabin
  - Embarked

## 🧪 Project Structure

- **Preprocessing**:
  - Handling missing values
  - Encoding categorical variables
  - Feature selection

- **Exploratory Data Analysis (EDA)**:
  - Visualizing survival rates by different features

- **Modeling**:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - Model evaluation (Accuracy, Confusion Matrix)

- **Visualization Tools**:
  - Matplotlib
  - Seaborn

## 🧰 Libraries Used

```python
numpy, pandas, matplotlib, seaborn,
sklearn.model_selection, sklearn.linear_model, sklearn.tree, sklearn.ensemble
```

## 📊 Sample Output

- Correlation heatmaps
- Survival rate plots by gender and class
- Confusion matrices for model evaluation

## 🚀 How to Run

1. Download the dataset from Kaggle.
2. Open the notebook `Titanic classification.ipynb`.
3. Install required libraries if needed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
