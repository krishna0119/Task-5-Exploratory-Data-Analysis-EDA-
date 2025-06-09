#  Titanic Dataset - Exploratory Data Analysis (EDA)

##  Objective

The goal of this project is to perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The purpose is to uncover insights, identify patterns, and understand the relationships among various features that influenced passenger survival.

---

##  Tools & Technologies Used

- **Python**
- **Pandas** (for data manipulation)
- **Matplotlib & Seaborn** (for data visualization)
- **Jupyter Notebook** (for analysis and reporting)

---

##  Dataset Information

- **Dataset Name**: `titanic.csv`
- **Source**: [Kaggle ]
- **Key Columns**:
  - `survived`: Survival (0 = No, 1 = Yes)
  - `pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
  - `sex`: Gender of passenger
  - `age`: Age in years
  - `fare`: Ticket fare
  - `embarked`: Port of Embarkation (C, Q, S)
  - `sibsp`: # of siblings / spouses aboard
  - `parch`: # of parents / children aboard

---

##  EDA Techniques Used

###  Basic Analysis
- Data shape, structure, and summary (`info()`, `describe()`)
- Missing values detection
- Categorical value distributions

###  Visualizations
- **Histograms**: Distribution of `age` and `fare`
- **Boxplot**: `age` vs `survived`
- **Countplot**: Gender-wise survival count
- **Heatmap**: Correlation between numerical features
- **Pairplot**: Relationship among key features (`survived`, `age`, `fare`, `pclass`)

---

##  Key Insights

- Survival was significantly higher among **females**.
- First-class passengers had a higher chance of survival.
- There is a moderate positive correlation between **fare** and **pclass**.
- Younger passengers had higher survival rates.

---

##  Project Structure

titanic.csv # Dataset
Task 5.ipynb # Jupyter Notebook with code and visuals
README.md # Project documentation
